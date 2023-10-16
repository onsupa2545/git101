<template>
    <v-app>
      <v-container>
        <div class="box">
        <v-row>
          <v-col cols="4" >
            <h2>ค้นหา</h2>
          </v-col>
        </v-row>
        <v-row>
          <v-col cols="4" >
            <p class="search-info">ปีการศึกษา<span class="info-space"></span><span class="info-space"></span>ภาคการศึกษา</p>
            <select name="เลือกปีการศึกษา" id="app" class="pe--text">
                <option value="select" selected="selected"><p>เลือกปีการศึกษา</p></option>
                <option value="2560">2560</option>
                <option value="2561">2561</option>
                <option value="2562">2562</option>
                <option value="2563">2563</option>
                <option value="2564">2564</option>
                <option value="2565">2565</option>
                <option value="2566">2566</option>
            </select>
          </v-col>
          <v-col cols="4">
            <select name="เลือกภาคการศึกษา" id="app" class="pk--text" >
                <option value="select" selected="selected"><p>เลือกภาคการศึกษา</p></option>
                <option value="1">1</option>
                <option value="2">2</option>
            </select>
          </v-col>
        </v-row>
        <v-divider></v-divider>
        <v-col cols="4">
            <v-row align="right">
                <v-col cols="12">
                    <p class="search-button" >
                    ค้นหา
                    </p>
                </v-col>
            </v-row>
        </v-col>
        </div>
        <v-row>
          <v-col cols="12">
            <p class="green--text">
              สถิติผู้สำเร็จการศึกษา<br>
              จำนวนผู้สำเร็จการศึกษา (คน)<br>
              <h1 class="num1">336</h1> 
            </p>
          </v-col>
          <v-col cols="12">
            <p class="orange--text">
              สถิติบัณฑิตที่ว่างงาน<br>
              จำนวนบัณฑิตที่ว่างงาน (คน) <br> 
              <h1 class="num2">4</h1>
            </p>
          </v-col>
          <v-col cols="12">
            <p class="pink--text">
              สถิติบัณฑิตที่ศึกษาต่อ<br>
              จำนวนบัณฑิตที่ศึกษาต่อ (คน) <br>
              <h1 class="num3">14</h1>
            </p>
          </v-col>
          <v-col cols="12">
            <p class="yl--text">
              สถิติบัณฑิตที่มีงานทำ<br>
              จำนวนบัณฑิตที่มีงานทำ (คน) <br>
              <h1 class="num4">318</h1><br>
              <p class="yo--text">&deg; หน่วยงานของรัฐ</p><h4 class="right-align">100</h4>
              <p class="yo--text">&deg; รัฐวิสาหกิจ</p><h4 class="right-align">2</h4>
              <p class="yo--text">&deg; หน่วยงานเอกชน </p><h4 class="right-align">200</h4>
              <p class="yo--text">&deg; ประกอบธุรกิจส่วนตัว </p><h4 class="right-align">14</h4>
              <p class="yo--text">&deg; องค์การรต่างประเทศ </p><h4 class="right-align">2</h4>
            </p>
          </v-col>          
          </v-row>
      </v-container>
    </v-app>
  </template>
  
 

  <script>

  </script>
  
  <style>
  h2 {
    background-color: #f3f7f7;
    padding: 2px;
    margin-left: 50px;
  }
  

  .num1 {
    color: rgb(72, 211, 183);
  }
  .num2 {
    color: rgb(223, 105, 46);
  }
  .num3 {
    color: rgb(244, 95, 152);
  }
  .num4 {
    color: rgb(69, 164, 219);
  }

  .green--text {
    background-color: #f3f7f7;
    color: rgb(13, 11, 11);
    margin-top: 2rem;
    padding: 4px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    margin-right: 800px;
    margin-left: 70px;
  }

  .orange--text {
    background-color: #f3f7f7;
    color: rgb(6, 7, 7);
    padding: 4px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    margin-right: 800px;
    margin-left: 70px;
  }

  .pink--text {
    background-color: #f3f7f7;
    color: rgbrgb(228, 143, 184) ;
    border-radius: 5px;
    padding: 4px 20px;
    margin-right: 800px;
    margin-left: 70px;
  }

  .search-button {
      background-color: #54c3b4;
      color: rgb(255, 255, 255);
      padding: 10px 25px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      margin-left: 1020px;
      margin-right: 270px;
      margin-top: 2rem;
   }

  .pk--text {
    color: rgb(7, 7, 7);
    margin-left: 280px; 
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
    width: 300px;
   }

  .pe--text {
    color: rgb(7, 7, 7);
    margin-left: 100px;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
    width: 300px;
   }
  
  .search-info {
   text-align: center;
   margin-top: -10px;
   margin-top: 2rem; 
   margin-right: 500px;
  }

  .info-space {
   margin-right: 250px;
  } 
  .yl--text  {
    background-color: #f3f7f7;
    color: rgb(0, 0, 0);
    margin-left: 725px;
    border-radius: 5px;
    border: none;
    padding: 10px 25px;
    margin-top: -434px; 
    content: "&deg;";
    margin-right: 70px;

  }

  .yo--text {
    background-color: #f3f7f7;
  }

  .box {
    background-color: #f3f7f7;
    margin-left: 70px;
    margin-right: 70px;
    border-radius: 5px;
  }  

  .right-align {
   background-color: #f3f7f7;
   color: rgb(69, 164, 219);
   text-align: right; 
   margin-top: -40px;
  }

  </style>

