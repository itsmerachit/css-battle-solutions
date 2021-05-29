# [Target #15 - Overlap](https://cssbattle.dev/play/15)

![](https://cssbattle.dev/targets/15.png)

Solution

```HTML
<div class="circle" id="lt">
  <div class="circle" id="center"></div>
</div>
<div class="circle" id="rt"></div>
<style>
  body{
    background: #09042A;
    margin:0;
    padding:0;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .circle{
    width: 150px;
    height: 150px;
    background: #7B3F61;
    border-radius: 50%;
    position: relative;
  }
  #lt{
    left: 25px;
    overflow: hidden
  }
  #rt{
    background: #E78481;
    left: -25px;
  }
  #center{
    background: #09042A;
    position: absolute;
    left: 100px;
    z-index: 2;
  }
</style>
```