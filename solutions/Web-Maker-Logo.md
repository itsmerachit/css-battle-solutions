# [Target #14 - Web Maker Logo(https://cssbattle.dev/play/14)

![](https://cssbattle.dev/targets/14.png)

Solution

```HTML
<div class="wrap">
	<div class="triangle1" id="up"></div>
	<div class="triangle1" id="down"></div>
	<div class="triangle2" id="up2"></div>
	<div class="triangle2" id="down2"></div>
</div>
<style>
	body {
        background: #F2F2B6;
        padding: 0;
        margin: 0
    }
    .triangle1, .triangle2 {
        width: 0;
        height: 0;
        border-left: 75px solid transparent;
        border-right: 75px solid transparent
    }
    #up {
        border-top: 130px solid #FF6D00;
        transform: translateX(160px);
        z-index: 2
    }
    #down {
        border-bottom: 130px solid #FF6D00;
        transform: translateX(140px)
    }
    #up2 {
        border-top: 130px solid #FD4602;
        transform: translateX(-120px)
    }
    #down2 {
        border-bottom: 130px solid #FD4602;
        transform: translateX(-180px);
        z-index: 2
    }
    .wrap {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100%
    }
</style>
```