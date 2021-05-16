# [Target #9 - Tesseract](https://cssbattle.dev/play/9)

![](https://cssbattle.dev/targets/9.png)

Solution

```HTML
<div id="sq">
	<div id="isq">
		<div id="cir"></div>
	</div>
</div>
<style>
	body {
	padding: 0px;
	margin: 0px;
	background: linear-gradient(#222730 0%, #222730 25%, #4CAAB3 25%, #4CAAB3 75%, #222730 75%);
	display: flex;
	justify-content: center;
	align-items: center
    }
    #sq {
        width: 250px;
        height: 250px;
        background: #222730;
        transform: rotate(45deg);
        display: flex;
        justify-content: center;
        align-items: center
    }
    #isq {
        width: 150px;
        height: 150px;
        background: #4CAAB3;
        display: flex;
        justify-content: center;
        align-items: center
    }
    #cir {
        width: 50px;
        height: 50px;
        border-radius: 50%;
        background: #393E46
    }
</style>
```