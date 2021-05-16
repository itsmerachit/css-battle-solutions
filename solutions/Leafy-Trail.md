# [Target #7 - Leafy Trail](https://cssbattle.dev/play/7)

![](https://cssbattle.dev/targets/7.png)

Solution

```HTML
<div id="a" class="leaf"></div>
<div id="b" class="leaf"></div>
<div id="c" class="leaf"></div>
<style>
  body {
    width: 100%;
    height: 100%;
    margin:0;
    padding:0;
    background: #0B2429;;
    display:flex;
    align-items: center;
    justify-content: center;
    
  }
  .leaf{
    height:150px;
    width:150px;
    background:#F3AC3C;
    position: relative;
  }
  #a{
    width: 150px;
    left:0px;
    z-index:1;
    left: 75px;
    background: #1A4341;
    border-radius: 100px 0 0 0;
  }
  #b{
    width: 150px;
    z-index:2;
    background:#998235;
    border-radius: 100px 0 20px 0;
  }
  #c{
    width:180px;
    z-index:3;
    right: 75px;
    background: #F3AC3C;
    border-radius: 100px 0 100px 0;
  }
</style>

```