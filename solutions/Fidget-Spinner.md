# [Target #5 - Firget Spinner](https://cssbattle.dev/play/17)

![](https://cssbattle.dev/targets/17.png)

Solution

```HTML
<div class='oc t'></div>
<div class="w">
  <div class='c'></div>
  <div class='s'></div>
  <div class='c'></div>
</div>
<div class='oc b'></div>
<style>
  body{
    background: #09042A
  }
  .w{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%
  }
  .c{
    height: 60px;
    width: 60px;
    box-shadow: 0 0 0 10px #E78481;
    border-radius: 50%;
  }
  .s{
    width: 60px;
    background: #E78481;
    height: 70px
  }
  .oc {
    background: #F5BB9C;
    height: 60px;
    width: 60px;
    position: absolute;
    border-radius: 50%;
    box-shadow: 0 0 0 10px #09042A;
    left: 170px;
  }
  .t{
    top: 67px;
  }
  .b{
    bottom: 67px;
  }
</style>
```