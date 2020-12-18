[텝에 대하여](/about.teb) | [문의/연락하기](/contact.teb) | [띵이위키](/wiki.teb) | [띵이봇](/bot/thinge.teb)

# 안녕하세요! 디스코드를 더욱더 즐겁게! 저희는 띵이봇을 개발하고 있는 팀 텝입니다!
<style>
.button {
  background-color: #4CAF50; /* Green */
  border: none;
  color: white;
  padding: 16px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  transition-duration: 0.4s;
  cursor: pointer;
}

.button1 {
  background-color: white;
  color: black;
  border: 2px solid #4CAF50;
}

.button1:hover {
  background-color: #4CAF50;
  color: white;
}

.button2 {
  background-color: white;
  color: black;
  border: 2px solid #008CBA;
}

.button2:hover {
  background-color: #008CBA;
  color: white;
</style><div class="animate__animated animate__bounceInLeft"><a href="http://invite.thingebot.kro.kr" target="_blank"><button class="button button1">봇 초대</button></a>
<a href="https://discord.gg/nrsVh8EUHE" target="_blank"><button class="button button2">지원 서버</button></a><a href="https://koreanbots.dev/bots/776239926684811314" target="_blank"><button class="button button1">한국 디스코드봇 리스트</button></a>
<a href="https://top.gg/bot/776239926684811314"><button class="button button2">탑지지(top.gg)</button></a><a href="http://blog.teb.kro.kr" target="_blank"><button class="button button1">공식 블로그</button></a></div>

[개인정보 처리방침](/bot/privacypolicy) | [오픈소스 이용약관](/bot/opensource) | [팀원들](https://teb.kro.kr/members/)
<!-- Channel Plugin Scripts -->
<script>
  (function() {
    var w = window;
    if (w.ChannelIO) {
      return (window.console.error || window.console.log || function(){})('ChannelIO script included twice.');
    }
    var ch = function() {
      ch.c(arguments);
    };
    ch.q = [];
    ch.c = function(args) {
      ch.q.push(args);
    };
    w.ChannelIO = ch;
    function l() {
      if (w.ChannelIOInitialized) {
        return;
      }
      w.ChannelIOInitialized = true;
      var s = document.createElement('script');
      s.type = 'text/javascript';
      s.async = true;
      s.src = 'https://cdn.channel.io/plugin/ch-plugin-web.js';
      s.charset = 'UTF-8';
      var x = document.getElementsByTagName('script')[0];
      x.parentNode.insertBefore(s, x);
    }
    if (document.readyState === 'complete') {
      l();
    } else if (window.attachEvent) {
      window.attachEvent('onload', l);
    } else {
      window.addEventListener('DOMContentLoaded', l, false);
      window.addEventListener('load', l, false);
    }
  })();
  ChannelIO('boot', {
    "pluginKey": "367b2cbd-11c1-47f5-81bd-8aa49840f9db"
  });
</script>
<!-- End Channel Plugin -->
