# [Target #11 - Eye of Sauron](https://cssbattle.dev/play/11)

![](https://cssbattle.dev/targets/11.png)

Solution

```HTML
<div id="ls" class="wave"></div>
<div id="circle"></div>
<div id="rs" class="wave"></div>
  <style>
  body{
    padding: 0px;
    margin: 0px;
    background: #191210;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  #circle{
    width: 140px;
    height: 140px;
    border-radius: 50%;
    background: radial-gradient(#84271C 0%,#84271C 25%,#191210 25%, #191210 50%, #ECA03D 50%, #ECA03D 100%);
    position: fixed;
  }
  #ls{
    border-radius: 0 0 70px 70px;
    margin-right: 100px;
    border-top: 0;
    margin-top: 50px
  }
  #rs{
    border-bottom: 0;
    border-radius: 70px 70px 0 0;
    margin-bottom: 50px
  }
  .wave{
    background: #191210;
    z-index: 2;
    width: 60px;
    height: 30px;
    border: 20px solid #ECA03D;
  }
</style>
```