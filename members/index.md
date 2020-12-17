<style>
  body {
    margin: 0;
    height: 100vh;
    overflow: scroll;
}

.open-popup {
    box-sizing: border-box;
    color: black;
    font-size: 16px;
    font-family: sans-serif;
    width: 10em;
    height: 4em;
    border: 1px solid;
    text-align: center;
    line-height: 4em;
    text-decoration: none;
    text-transform: capitalize;
    margin: 1em;
}

.open-popup:hover {
    border-width: 2px;
}

/* popup page layout */

.popup {
    position: absolute;
    top: 0;
    width: 100%;
    height: inherit;
    flex-direction: column;
    justify-content: flex-start;
    display: none;
}

.popup:target {
    display: flex;
}

.popup .back {
    font-size: 20px;
    font-family: sans-serif;
    text-align: center;
    height: 2em;
    line-height: 2em;
    background-color: #ddd;
    color: black;
    text-decoration: none;
}

.popup .back:visited {
    color: black;
}

.popup .back:hover {
    background-color: #eee;
}

.popup p {
    font-size: 100px;
    text-align: center;
    margin: 0.1em 0.05em;
}

/* animation effects */

.popup > * {
    filter: opacity(0);
    animation: fade-in 0.5s ease-in forwards;
    animation-delay: 1s;
}

@keyframes fade-in {
    to {
        filter: opacity(1);
    }
}

.popup::before {
    content: '';
    position: absolute;
    width: 100%;
    height: 0;
    top: 50%;
    background-color: #7289DA;
    animation: open-animate 0.5s cubic-bezier(0.8, 0.2, 0, 1.2) forwards;
    animation-delay: 0.5s;
}

@keyframes open-animate {
    to {
        height: 100vh;
        top: 0;
    }
}

.popup::after {
    content: '';
    position: absolute;
    width: 0;
    height: 2px;
    background-color: #7289DA;
    top: calc((100% - 2px) / 2);
    left: 0;
    animation: line-animate 0.5s cubic-bezier(0.8, 0.2, 0, 1.2);
}

@keyframes line-animate {
    50%, 100% {
        width: 100%;
    }
}

  a {
    text-decoration: none;
  }
  
  .popup a {
    color: white;
  }
  </style>
  <a href="#every" class="open-popup">애브리띵</a>
  <a href="#yeomoon" class="open-popup">여무니</a>
  <a href="#pukk" class="open-popup">푸끄</a>
  <a href="#sean" class="open-popup">셔니</a>

<section id="every" class="popup">
  <a href="#" class="back">&lt; back</a>
  <center>
  <img src="https://cdn.discordapp.com/avatars/694017913723682946/3e57e7027906ab900d3f0fcfc08a24fd.png" width="100px">
  <h1>애브리띵 - 봇 개발자, 서버 관리자, 웹사이트(블로그) 관리자, 디자이너</h1>
<h2 id="애브리띵은-팀-텝의-1번째-멤버이자-창립자에요">애브리띵은 팀 텝의 1번째 멤버이자 창립자에요!</h2>
현재는 띵이봇을 개발하고 있답니다 :D
<br><br>
    <a href="https://discord.com/users/694017913723682946" target="_blank">디스코드</a>
    </center>
</section>

<section id="yeomoon" class="popup">
  <a href="#" class="back">&lt; back</a>
    <center>
  <img src="https://cdn.discordapp.com/avatars/724862211251765250/124ac0e7d02545b0efa5a060e6559c4e.png?size=256" width="100px">
  <h1>여무니 - 봇 개발자, 디자이너</h1>
<h2 id="여무니는-애브리띵을-뺀-팀-텝의-1번째-멤버에요">여무니는 애브리띵을 뺀 팀 텝의 1번째 멤버에요!</h2>
현재는 게임봇인 연두봇을 개발하고 있답니다! 아직 출시도 안했어요 :0<br><br>
    <a href="https://discord.com/users/724862211251765250" target="_blank">디스코드</a>
    </center>
</section>

<section id="pukk" class="popup">
  <a href="#" class="back">&lt; back</a>
    <center>
        <img src="https://images-ext-2.discordapp.net/external/pAGW-EmS6XkLtVTIWmx0zGxsZ19Bi-Nr_eO6EYPmgXs/%3Fsize%3D1024/https/cdn.discordapp.com/avatars/681403207620100135/a_50e8ecd650780f71dd294e3c95dadeed.gif" width="100px">
      <h1>푸끄 - 서버 관리자</h1>
      <h2>푸끄는 팀 텝의 단 1명뿐인 포럼 관리자에요!</h2><br><br>
    <a href="https://discord.com/users/681403207620100135" target="_blank">디스코드</a>
      </center>
</section>

<section id="sean" class="popup">
  <a href="#" class="back">&lt; back</a>
    <center>
        <img src="https://images-ext-2.discordapp.net/external/WBQsdH_AYhDXZKXE8FE73aYFsvpKY8XFUJ9aeJbPZD4/%3Fsize%3D1024/https/cdn.discordapp.com/avatars/713589002242097343/854ed654b04814b53bea3017bfe19100.webp" width="100px">
      <h1>셔니 - 봇 개발자, 웹사이트 관리자</h1>
      <br><br>
    <a href="https://discord.com/users/713589002242097343" target="_blank">디스코드</a>
      </center>
</section>
