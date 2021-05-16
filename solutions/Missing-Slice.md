# [Target #6 - Missing Slice](https://cssbattle.dev/play/6)

![](https://cssbattle.dev/targets/6.png)

Solution

```HTML
<div class="wrap">
	<div class="sqr" id="s1"></div>
	<div class="sqr" id="s2"></div>
</div>
<div class="wrap">
	<div class="sqr" id="s3"></div>
	<div class="sqr" id="s4"></div>
</div>
<style>
  body {
    width: 100%;
    height: 100%;
    padding: 0px;
    margin: 0px;
    background: #E3516E;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .sqr {
    height: 100px;
    width: 100px
  }
  #s1{
    background:#51B5A9;
    border-radius: 100% 0 0 0;
  }
  #s2{
    background:#F7F3D7;
    border-radius: 0 0 0 100%;
  }
  #s3{
    background:#FADE8B;
    border-radius: 0 100% 0 0;
  }
  
</style>
```