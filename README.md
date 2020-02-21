# dom-elective
DOM manipulation, web browser-based PKU elective killer

## 声明
本工具仅供学习、观察使用，本人不声明其具有声称的任何功能或其是否能在目前版本的elective上正常使用。另外，使用刷课机会收到严厉处分。

## Instructions
1. Launch Chrome/Chromium with custom arguments (mandatory):
```
--disable-web-security --user-data-dir="C:\Chrome dev session"
```

2. Edit index.html with your credentials:
```javascript
var myUsername = "1000000000";
var myPwd = "my_password_here";
```
3. Follow instructions on screen

Optionally:
* Supply your `notify.mp3` to play a winning song.
* Choose 主修/辅双 in code:
```javascript
// IAAA authentication successful
try {
	window.elective.getElementById("div1").click() // 主修
	// window.elective.getElementById("div2").click() // 辅双
}
```

## License
Written in late 2017, revised spring 2018 and fall 2018.

Licensed under the GNU General Public License, version 2 (excluding later versions).