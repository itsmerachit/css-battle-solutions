# [Target #10 - Cloaked Spirits](https://cssbattle.dev/play/10)

![](https://cssbattle.dev/targets/10.png)

Solution

```HTML
<div class="wrap">
	<div class="bar">
		<div class="cir"></div>
	</div>
	<div class="bar" id="up">
		<div class="cir" id="top"></div>
	</div>
	<div class="bar">
		<div class="cir"></div>
	</div>
</div>
<style>
	* {
	margin: 0;
	padding: 0
}
body {
	background: #62306D;
	display: flex;
	justify-content: center;
	align-items: flex-end
}
.wrap {
	width: 300px;
	height: 250px;
	background: #f7ec7d;
	display: flex;
	justify-content: center;
	align-items: flex-start
}
.bar {
	background: linear-gradient(to bottom, #62306D 0%, #62306D 75%, #F7EC7D 75%);
	width: 100px;
	height: 200px;
	display: flex;
	justify-content: center;
	align-items: flex-end
}
.cir {
	width: 60px;
	height: 60px;
	background: #E38F66;
	border: 20px solid #AA445F;
	border-radius: 50%
}
#top {
	align-self: flex-start;
	background: #AA445F;
	border: 20px solid #E38F66
}
#up {
	background: linear-gradient(to bottom, #62306D 0%, #62306D 25%, #F7EC7D 25%)
}
</style>
```