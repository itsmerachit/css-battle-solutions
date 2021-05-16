# [Target #8 - Forking Crazy](https://cssbattle.dev/play/8)

![](https://cssbattle.dev/targets/8.png)

Solution

```HTML
<div id="wrap">
  <div class="bars"></div>
  <div class="bars"></div>
  <div class="bars"></div>
  <div class="bars"></div>
  <div class="bars"></div>
  <div class="bars"></div>
  <div class="bars"></div>
</div>
<div id="rec"></div>
<div id="circle"></div>
<div id="stand"></div>
<style>
  body {
    padding: 0px;
    margin: 0px;
    background: #6592CF;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
  }
  #fork{
    width: 140px;
    height: 350px;
    //background:#afafaf;
    
    position: relative;
    margin-left: 130px
  }
  #circle{
    background: #060F55;
    width: 140px;
    height: 70px;
    border-radius: 0 0 70px 70px;
    margin-top: -10px;
  }
  #stand{
    position: absolute;
    background: #060F55;
    width: 20px;
    height: 60px;
    z-index: 2;
    margin-top: 240px;
  }
  #wrap{
    margin-top: 20px;
    height: 140px;
    width: 140px;
    display: flex;
  }
  .bars{
    width: 20px;
    height: 120px;
    margin-top:30px
  }
  div.bars:nth-child(2n+1) {
    background:#060F55;
    border-radius: 10px 10px;
  }
  div.bars:nth-child(2n+2) {
    border-radius: 0 0 10px 10px;
    z-index: 2;
    margin-top: 20px
  }
  #rec{
    height: 30px;
    background: #060F55;
    width: 140px;
    z-index: -1;
  }
  
</style>
```