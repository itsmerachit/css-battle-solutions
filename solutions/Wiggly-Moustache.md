# [Target #12 - Wiggly Moustache](https://cssbattle.dev/play/12)

![](https://cssbattle.dev/targets/12.png)

Solution

```HTML
<div class="sc"></div>
<div id="ls" class="wave"></div>
<div id="circle"></div>
<div id="rs" class="wave"></div>
<div class="sc"></div>
<style>
	body {
	padding: 0px;
	margin: 0px;
	background: #F5D6B4;
	display: flex;
	justify-content: center;
	align-items: center
    }
    #circle {
        width: 60px;
        height: 30px;
        border-radius: 60px 60px 0 0;
        border: 20px solid #D86F45;
        border-bottom: 0;
        position: fixed;
        margin-bottom: 50px
    }
    #ls {
        margin-right: 60px
    }
    .wave {
        z-index: 2;
        width: 60px;
        height: 30px;
        border: 20px solid #D86F45;
        border-radius: 0 0 70px 70px;
        border-top: 0;
        margin-top: 50px
    }
    .sc {
        width: 20px;
        height: 20px;
        background: #D86F45;
        border-radius: 50%;
        margin-left: -20px;
        margin-right: -20px
    }
</style>
```