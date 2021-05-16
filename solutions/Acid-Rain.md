# [Target #5 - Acid Rain](https://cssbattle.dev/play/5)

![](https://cssbattle.dev/targets/5.png)

Solution

```HTML
<div id="a" class="leaf"></div>
<div id="b" class="leaf"></div>
<div id="c" class="leaf"></div>
<style>
	body {
	width: 100%;
	height: 100%;
	margin: 0;
	padding: 0;
	background: #0B2429
    }
    .leaf {
        height: 120px;
        width: 120px;
        background: #F3AC3C;
        position: relative
    }
    #a {
        left: 200px;
        top: 30px;
        z-index: 1;
        border-radius: 50%
    }
    #b {
        left: 140px;
        bottom: 30px;
        z-index: 2;
        background: #998235;
        border-radius: 50% 0 50% 50%
    }
    #c {
        z-index: 3;
        bottom: 90px;
        left: 80px;
        border-radius: 50% 0 50% 50%
    }
</style>
```