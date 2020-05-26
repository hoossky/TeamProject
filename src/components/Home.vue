<template>
  <div>
    <header>
      <div class="container">
        <div class="topright">
          <div class="button-1">
            <div class="eff-2"></div>
            <a id="company_button">업체 메뉴 </a>
          </div>
          <div class="button-2">
            <div class="eff-2"></div>
            <a id="user_button">사용자 메뉴 </a>
          </div>
        </div>
      </div>
      <h2>Movin</h2>
    </header>
    <nav class="nav_bar">
      <button>공지사항</button>&nbsp;
      <button>커뮤니티</button>&nbsp;
      <button>업체정보</button>&nbsp;
      <button>견적정보</button>&nbsp;
      <button>이벤트</button>&nbsp;
      <button>고객지원</button>
    </nav>
    <section>

      <iframe width="700" height="500" src="https://www.youtube.com/embed/fKBYdv4s20k?&amp;autoplay=1&amp;loop=1 frameborder=" ></iframe>
      <div style= "height:50px"></div>
      <h2>이사 견적, 내 방에서 알아보세요.</h2>
      <div style= "height:50px"></div>
    </section>
    <section2>
      <div style= "height:50px"></div>
      <h2>방문 없이 견적 받는,</h2>
      <form>
        <img src = "https://miro.medium.com/max/1200/0*TbvZrhoMfgtPAsaa.png"
             style = "width : 70%; height : 70%; margin: 0px 250px">
        <button>이사 가이드</button>&nbsp;<button>견적 보러가기</button>
        <div style= "height:50px"></div>
      </form>
    </section2>
    <section3>

      <h2>후기 및 사례</h2>
      <div style= "height:50px"></div>
      <img src="https://s3-ap-northeast-2.amazonaws.com/icunow.co.kr/2017/12/23002747/appstore.png"
      style="margin: 0px 350px">
      <div style= "height:50px"></div>

    </section3>

    <section4>
      <div style= "height:50px"></div>
      <h2>Application</h2>
      <div style= "height:50px"></div>
      <img src="https://image.freepik.com/free-vector/isometric-people-interfaces-horizontal-composition-with-set-human-characters-with-screens-gadgets_1284-29938.jpg"
           style="width : 50%; height : 50%; margin: 0px 450px">
      <div style= "height:50px"></div>
      <h2>어플리케이션으로 더 편하게 만나보세요.</h2>
      <div style= "height:50px"></div>
      <button style="border:1px solid #34495e; margin: 0px 850px" >Download</button>
      <div style= "height:50px"></div>

    </section4>
    <footer>
      <p>© 2020 Bit move Inc.</p>
    </footer>
  </div>
</template>

<script>
  export default {

    data: () => ({

    }),
  }
</script>
<style scoped>

  .container{
    position: absolute;
    left: 300px;
    top: 50px;

  }
  .nav_bar{
    text-align: center;
    font-size: 25px;
    color: #34495e;
  }
  .button-1{
    width:140px;
    height:50px;
    border:2px solid #34495e;
    float:left;
    text-align:center;
    cursor:pointer;
    position:relative;
    box-sizing:border-box;
    overflow:hidden;
    margin:0 0 30px 0;
  }
  .button-1 a{
    font-family:arial;
    font-size:16px;
    color:#34495e;
    text-decoration:none;
    line-height:50px;
    transition:all .5s ease;
    z-index:2;
    position:relative;
  }
  /*.eff-1{
    width:140px;
    height:50px;
    top:-50px;
    background:#34495e;
    position:absolute;
    transition:all .5s ease;
    z-index:1;
  }*/
  .button-1:hover .eff-2{
    top:0;
  }
  .button-1:hover a{
    color:#fff;
  }

  .button-2{
    width:140px;
    height:50px;
    border:2px solid #34495e;
    float:left;
    text-align:center;
    cursor:pointer;
    position:relative;
    box-sizing:border-box;
    overflow:hidden;
    margin:0 0 40px 30px;
  }
  .button-2 a{
    font-family:arial;
    font-size:16px;
    color:#34495e;
    text-decoration:none;
    line-height:50px;
    transition:all .5s ease;
    z-index:2;
    position:relative;
  }
  .eff-2{
    width:140px;
    height:50px;
    top:-50px;
    background:#34495e;
    position:absolute;
    transition:all .5s ease;
    z-index:1;
  }
  .button-2:hover .eff-2{
    top:0;
  }
  .button-2:hover a{
    color:#fff;
  }


  body {
    background-color: #f1d5cf;
    font-family: Sans-Serif;
    text-align: center;
    color: #34495e;

  }

  header {
    background-color: #f1d5cf;
    padding: 30px;
    text-align: center;
    font-size: 35px;
    color: #34495e;
  }
  .container {
    position: relative;
  }
  .topright {
    position: absolute;
    top: 8px;
    right: 16px;
    font-size: 18px;
  }
  section {
    background-color: #f1d5cf;
    padding: 10px;
    text-align: center;
    font-size: 25px;
    color: #34495e;
  }
  section2 {
    background-color: white;
    padding: 10px;
    text-align: center;
    font-size: 25px;
    color: #34495e;
  }
  section3 {
    background-color: #f1d5cf;
    padding: 10px;
    text-align: center;
    font-size: 25px;
    color: #34495e;
  }
  section4 {
    background-color: white;
    padding: 10px;
    text-align: center;
    font-size: 25px;
    color: #34495e;
  }

  nav {
    float: left;
    width: 100%;
    height: 100px;
    background: #f1d5cf;
    padding: 20px;
    text-align: center;
    color: #34495e;
  }

  nav ul {
    list-style-type: none;
    padding: 0;
  }

  article {
    float: left;
    padding: 20px;
    width: 70%;
    background-color: #f1d5cf;
    height: 300px;
  }

  section:after {
    content: "";
    display: table;
    clear: both;
  }

  footer {
    background-color: #f1d5cf;
    padding: 10px;
    text-align: center;
    font-size: 20px;
    color: white;
  }
</style>
