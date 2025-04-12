<!DOCTYPE html>  <html lang="ko">  
<head>  
<title>올인원 뉴스</title>  
<meta charset="utf-8">  
 <meta name="viewport" content="width=device-width, initial-scale=1.0">  
   <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@700&display=swap" rel="stylesheet">  
<style>  
body {background-color:#5BFF7B;  
transition:background-color 0.5s, color 0.5s;}  
button {width: 300px; height: 75px; border-radius:20px;}  
a:not(.no-style) {font-size:45px; text-decoration:none; color:black;}  
h1 {text-align:center; color:white;}  
h2 {text-align:center; color:white;}  
button {background-color:#FDFEC2; margin:2px;}  
 .btn-container {position: fixed; right: 20px; top: 20px; display: flex; gap: 10px;}  
 input {margin:0px; height:40px; font-size:23px;}  
 p {margin:30px;}  
 .popularnews {background-color:#666666; width:500px; margin-left: 400px; color:white; border-radius:15px; border: 5px solid black; padding:20px; text-align:center;}  
 input[type="text"] {border:2px solid; border-radius:8px;}  
 input[type="button"] {border:2px solid; border-radius:8px;}  
 iframe {width:500px; height:300px; border-radius:20px;}  
 .ad {border-top:5px solid; padding:15px; background-color:#E6E6E6; width:1300px;}  
 .adli {width:400px; height:200px; border:7px solid; background-color:white;}  
li {line-height:1.3; color:black;}  
 .mbc {width:31%; height:220px;}  
 @media (max-width:800px) {.news button {width:49%; height:90px;} .popularnews {margin-left:120px;}  
  .ad {width:100%;}  
  .btn-container {top:10px;}  
  .mbc {width:45%; height:200px;}
 }  
 #clock {font-family:orbitron;}  
  #date {font-family:orbitron; font-weight:bold;}  
 </style>  
</head>  
<body>  
 <div style="display:flex; gap:25px;">  
  <div id="date">----년 --월 --일 (---)</div>  
 <div id="clock">--:--:--</div>  
 </div>  
<h1>국내•외 주요 언론사의 뉴스를 한곳에서 보세요.</h1>  
<div class="btn-container">  
    <button style="width: 60px; height: 23px; background-color:#0063FF;" onclick="document.body.style.backgroundColor='#212121'; document.body.style.color='white'">🌙</button>  
    <button style="width: 60px; height: 23px; background-color:#0063FF;" onclick="document.body.style.backgroundColor='#5BFF7B'; document.body.style.color='black'">☀️</button>  
</div>  
 <div class="news">  
<h2>국내</h2>  
<button><a href="https://imnews.imbc.com">MBC</a></button>  
<button><a href="https://news.sbs.co.kr">SBS</a></button>  
<button><a href="https://news.kbs.co.kr">KBS</a></button>  
<button><a href="https://www.ytn.co.kr">YTN</a></button>  
<button><a href="https://www.chosun.com">조선일보</a></button>  
<button><a href="https://www.hani.co.kr">한겨레</a></button>  
<h2>해외</h2>  
<button><a href="https://www.nytimes.com">뉴욕타임스</a></button>  
<button><a href="https://www.bbc.com/news">BBC</a></button>  
<button><a href="https://www.cnn.com">CNN</a></button>  
<button><a href="https://www3.nhk.or.jp/news/">NHK</a></button>  
<button><a href="https://www.theguardian.com">가디언</a></button>  
 <button><a href="https://tv.cctv.com/cctvnews/">CCTV</a></button>  
 </div>  
 <div class="popularnews" style="margin-top:30px; margin-bottom:20px;">  
  <p style="font-size:30px; text-align:center;">인기뉴스</p>  
  <iframe src="https://m.news.nate.com/rank/list?mid=m2001"></iframe>  
 </div>  
 <div style="display:flex; gap:20px;">  
 <div style="background-color:#F9FF99; border-radius:15px; width:400px; border:solid 5px black;">  
  <div style="text-align:center;">  
 <h3 style="color:#333333;">언론사 앱 다운로드(안드로이드)</h3>  
  </div>  
 <ul>  
  <li><a href="https://play.google.com/store/apps/details?id=com.imbc.imnews.mbcnews" class="no-style" style="color:blue;"><strong>MBC 뉴스 앱</strong></a></li>  
  <li><a href="https://play.google.com/store/apps/details?id=com.cubeflux.news" class="no-style" style="color:blue;"><strong>SBS 뉴스 앱</strong></a></li>  
  <li><a href="https://play.google.com/store/apps/details?id=kr.co.kbs.news301" class="no-style" style="color:blue;"><strong>KBS 뉴스 앱</strong></a></li>  
  <li><a href="https://play.google.com/store/apps/details?id=com.estsoft.android.ytn" class="no-style" style="color:blue;"><strong>YTN 뉴스 앱</strong></a></li>  
  <li><a href="https://play.google.com/store/apps/details?id=com.chosunmedia.android" class="no-style" style="color:blue;"><strong>조선일보 앱</strong></a></li>  
  <li><a href="https://play.google.com/store/apps/details?id=kr.co.hani.news" class="no-style" style="color:blue;"><strong>한겨레 앱</strong></a></li>  
  <li><a href="https://play.google.com/store/apps/details?id=com.nytimes.android" class="no-style" style="color:blue;"><strong>뉴욕타임스 앱</strong></a></li>  
  <li><a href="https://play.google.com/store/apps/details?id=bbc.mobile.news.ww" class="no-style" style="color:blue;"><strong>BBC 뉴스 앱</strong></a></li>  
  <li><a href="https://play.google.com/store/apps/details?id=com.cnn.mobile.android.phone" class="no-style" style="color:blue;"><strong>CNN 뉴스 앱</strong></a></li>  
  <li><a href="https://play.google.com/store/apps/details?id=jp.or.nhk.nhkworld.tv" class="no-style" style="color:blue;"><strong>NHK 뉴스 앱</strong></a></li>  
  <li><a href="https://play.google.com/store/apps/details?id=com.guardian" class="no-style" style="color:blue;"><strong>가디언 앱</strong></a></li>  
  <li><a href="https://play.google.com/store/apps/details?id=com.imib.cctv" class="no-style" style="color:blue;"><strong>CGTN(CCTV)뉴스 앱</strong></a></li>  
 </ul>  
 </div>  
 <div style="background-color:#ADFFFD; border-radius:15px; width:400px; border:solid 5px black;">  
  <div style="text-align:center;">  
   <h3 style="color:#333333;">언론사 앱 다운로드(ios)</h3>  
  </div>  
  <ul>  
   <li><a href="https://apps.apple.com/kr/app/mbc-%EB%89%B4%EC%8A%A4/id387713617" class="no-style" style="color:blue;"><strong>MBC 뉴스 앱</strong></a></li>  
   <li><a href="https://apps.apple.com/kr/app/sbsnews/id371932445" class="no-style" style="color:blue;"><strong>SBS 뉴스 앱</strong></a></li>  
   <li><a href="https://apps.apple.com/kr/app/kbs-%EB%89%B4%EC%8A%A4/id376746898" class="no-style" style="color:blue;"><strong>KBS 뉴스 앱</strong></a></li>  
   <li><a href="https://apps.apple.com/kr/app/ytn/id353117998" class="no-style" style="color:blue;"><strong>YTN 뉴스 앱</strong></a></li>  
   <li><a href="https://apps.apple.com/kr/app/%EC%A1%B0%EC%84%A0%EC%9D%BC%EB%B3%B4/id360677289" class="no-style" style="color:blue;"><strong>조선일보 앱</strong></a></li>  
   <li><a href="https://apps.apple.com/kr/app/%ED%95%9C%EA%B2%A8%EB%A0%88/id420600963" class="no-style" style="color:blue;"><strong>한겨레 앱</strong></a></li>  
   <li><a href="https://apps.apple.com/kr/app/the-new-york-times-live-news/id284862083" class="no-style" style="color:blue;"><strong>뉴욕타임스 앱</strong></a></li>  
   <li><a href="https://apps.apple.com/us/app/bbc-world-news-stories/id364147881" class="no-style" style="color:blue;"><strong>BBC 뉴스 앱</strong></a></li>  
   <li><a href="https://apps.apple.com/us/app/cnn-breaking-us-world-news/id331786748" class="no-style" style="color:blue;"><strong>CNN 뉴스 앱</strong></a></li>  
   <li><a href="https://apps.apple.com/kr/app/nhk-world-japan/id350732480" class="no-style" style="color:blue;"><strong>NHK 뉴스 앱</strong></a></li>  
   <li><a href="https://apps.apple.com/kr/app/the-guardian-live-world-news/id409128287" class="no-style" style="color:blue;"><strong>가디언 앱</strong></a></li>  
   <li><a href="https://apps.apple.com/cn/app/%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB/id467289231" class="no-style" style="color:blue;"><strong>CCTV 뉴스 앱</strong></a></li>  
  </ul>  
 </div>  
 </div>  
 <br>  
 <p style="font-size:25px;">개발자 나이퀴즈:<input type="text" id="ageInput" placeholder="개발자의 나이를 맞춰보세요">  
  <input type="button" value="확인" onclick="확인();" style="height:46px;">  
 </p>    
<h6>v1.1.2</h6>  
 <div class="ad">  
  <h3 style="color:black;">뉴스 미리보기</h3>  
   <iframe src="https://imnews.imbc.com" style="background-color:white;margin:10px;" class="mbc"></iframe> 
     <iframe src="https://news.sbs.co.kr" style="background-color:white;margin:10px;" class="mbc"></iframe> 
     <iframe src="https://news.kbs.co.kr" style="background-color:white;margin:10px;" class="mbc"></iframe> 
     <iframe src="https://www.ytn.co.kr" style="background-color:white;margin:10px;" class="mbc"></iframe> 
     <iframe src="https://www.chosun.com" style="background-color:white;margin:10px;" class="mbc"></iframe> 
     <iframe src="https://www.hani.co.kr" style="background-color:white;margin:10px;" class="mbc"></iframe> 
     <iframe src="https://www3.nhk.or.jp/news/" style="background-color:white;margin:10px;" class="mbc"></iframe> 
     <iframe src="https://tv.cctv.com/cctvnews/" style="background-color:white;margin:10px;" class="mbc"></iframe> 
   </div>  
 <script>  
function 확인() {  
    var age = document.getElementById("ageInput").value.trim().toLowerCase();  if (age === "13" || age === "13살" || age === "13세" || age === "13살." ||age === "13세." ||age === "13 years old") {  
    alert('맞았습니다'); //13살일때 맞음  

}  
 else if (age === "2013" || age === "2013년") {alert('제가 태어난 연도입니다. 근데 제 나이가 2013이요?');} //2013이라고 했을때 메세지가 뜨게

else if (age === "bluescreen") {
alert('새로고침을 하면 블루스크린을 없앨수 있습니다. 확인을 눌러 블루스크린을 체험해보세요.');
// 파란색 배경을 추가할 새로운 div 생성
let bluescreen = document.createElement('div');

document.body.style.backgroundColor='#207CAD';  

//블루스크린 스타일 설정  
bluescreen.style.position = 'fixed'; // 고정 위치로 설정  
bluescreen.style.top = '0';  
bluescreen.style.left = '0';  
bluescreen.style.width = '100%'; // 전체 화면 너비  
bluescreen.style.height = '100%'; // 전체 화면 높이  
bluescreen.style.padding = '50px';  
bluescreen.style.backgroundColor = '#207CAD'; // 배경 색 파란색  
bluescreen.style.zIndex = '9999'; // 다른 요소들 위에 표시  

//기존 내용 안보이게 설정  
bluescreen.style.display = 'flex';  
bluescreen.style.alignItems = 'top';  
bluescreen.style.justifyContent = 'center';

bluescreen.innerHTML = `

 <div style="display: flex; flex-direction: column;">  
        <p style="font-size:140px; margin: 0; color:white;">:(</p>  
        <p style="color:white; font-size:30px; margin-top: 10px;">  
            PC에 문제가 발생하여 다시 시작해야 합니다.<br>  
            일부 오류 정보를 수집하고 있습니다.<br>  
            그런 다음 자동으로 다시 시작합니다. (42% 완료)  
        </p>  
    </div>  
`; //블루스크린 화면  
    document.body.appendChild(bluescreen);  
}  
 else if (age === "" ) {alert('텍스트를 입력하세요');}  
 else {  
        alert('틀렸습니다. 힌트:두자릿수');  
     } //아닐때 틀림  
}  
     function updateClock() {  
      const now = new Date();  
      const hours = String(now.getHours()).padStart(2, '0');  
      const minutes = String(now.getMinutes()).padStart(2, '0');  
      const seconds = String(now.getSeconds()).padStart(2, '0');  
      document.getElementById('clock').textContent = `${hours}:${minutes}:${seconds}`;  
    }  // 최초 실행 후 매초마다 업데이트  
updateClock();  
setInterval(updateClock, 1000);

function updateDate() {
const now = new Date();
const year = now.getFullYear();
const month = now.getMonth() + 1;
const date = now.getDate();
const dayNames = ['일', '월', '화', '수', '목', '금', '토'];
const day = dayNames[now.getDay()];

document.getElementById('date').textContent = `${year}년 ${month}월 ${date}일 (${day})`;

}

updateDate();
</script>

</body>  
</html>
