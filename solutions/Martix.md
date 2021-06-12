# [Target #18 - Matrix](https://cssbattle.dev/play/18)

![](https://cssbattle.dev/targets/18.png)

Solution

```HTML
<div class="r">
	<div class="c d"></div>
	<div class="c"></div>
	<div class="c d"></div>
</div>
<div class="r">
	<div class="c"></div>
	<div class="c d"></div>
	<div class="c"></div>
</div>
<div class="r">
	<div class="c d"></div>
	<div class="c"></div>
	<div class="c d"></div>
</div>
<div class="r">
	<div class="c"></div>
	<div class="c d"></div>
	<div class="c"></div>
</div>
<style>
    body {
        background:#5C434C;
        display:flex;
        align-items:center;
        justify-content:center;
        margin:0;
        padding:0px
    }
    .c {
        background:#F5D6B4;
        height:60px;
        width:60px;
        padding:10px;
        border-radius:80px 0px 0px 0px;
        argin:10px
    }
    .d {
        background:#F09462
    }
    .r :nth-child(2n) {
        margin-top:20px;
        margin-bottom:20px
    }
    </style>

```