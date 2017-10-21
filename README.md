# mMenu
CSS responsive menu no JavaScript and picture
CSSのみで出来たレスポンシブメニュー（JavaScriptと画像は一切使用していません）

## Demo  
[DEMO](http://mo2nabe.com/practice_css/mMenuDEMO.html)  
![demo1](https://raw.githubusercontent.com/motsu0/mMenu/master/DEMOimg/mMenu001.PNG)
![demo2](https://raw.githubusercontent.com/motsu0/mMenu/master/DEMOimg/mMenu002.PNG)
![demo3](https://raw.githubusercontent.com/motsu0/mMenu/master/DEMOimg/mMenu003.PNG)

## Usage
write in `<head>`
```html
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<link rel="stylesheet" href="toYourPath/mMenuDEMO.css">
```
write in `<body>`
```html
<ul id="mMenu">
	<input type="checkbox" id="mMenu_switch">
	<li id="mMenu_title"><!--you can remove-->
		<label for="mMenu_switch"><div><span></span></div>
		</label></li>
	<li id='mMenu_button'>
		<label for="mMenu_switch"><div id="mMenu_buttonBox"><div></div></div>
		</label></li>
	<label for="mMenu_switch"><div id="mMenu_bg"></div></label>
	
	<li class="mMenu_item"><a href="#">item1</a></li>
	<li class="mMenu_item"><a href="#">item2</a></li>
	<li class="mMenu_item"><a href="#">item3</a></li>
	<li class="mMenu_item"><a href="#">item4</a></li>
	<li class="mMenu_item"><a href="#">item5</a></li>
</ul>
```