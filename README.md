<!DOCTYPE html>
<html lang="zh-HK">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>正在跳轉…</title>
  <script>
  !function(e,t,n,s,u,a){e.twq||(s=e.twq=function(){s.exe?s.exe.apply(s,arguments):
  s.queue.push(arguments);},s.version='1.1',s.queue=[],u=t.createElement(n),
  u.async=!0,u.src='https://static.ads-twitter.com/uwt.js',
  a=t.getElementsByTagName(n)[0],a.parentNode.insertBefore(u,a))}(window,document,'script');
  twq('config','q1c3c'); /* Pixel ID */
  </script>
</head>
<body>
  <p style="text-align:center;font-family:system-ui,Segoe UI,Roboto,Helvetica,Arial">正在為你連接 WhatsApp… 若未自動跳轉，<a id="fallback" href="#" target="_blank" rel="noopener">點此開啟</a></p>

  <script>
    const LINKS = [
      "https://wa.me/85268837643",
      "https://wa.me/85295648609",
      "https://wa.me/85266104290",
      "https://wa.me/85265211659",
      "https://wa.me/85253812254",
      "https://wa.me/85267263590"
    ];
    const sp = new URLSearchParams(location.search);
    let idx = parseInt(sp.get('force'), 10);
    if (!Number.isInteger(idx) || idx < 0 || idx >= LINKS.length) idx = Math.floor(Math.random()*LINKS.length);
    const target = LINKS[idx];
    document.getElementById('fallback').href = target;

    try{ twq('event','tw-q1c3c-qiev1', { value: 1, currency: 'HKD' }); }catch(e){}
    setTimeout(function(){ window.location.replace(target); }, 200);
  </script>
</body>
</html>
