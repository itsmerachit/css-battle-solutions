# [Target #2 - Carrom](https://cssbattle.dev/play/2)

![](https://cssbattle.dev/targets/2.png)

Solution

```HTML
<div class="sqr" id="s1"></div>
<div class="sqr" id="s2"></div>
<div class="sqr" id="s3"></div>
<div class="sqr" id="s4"></div>
<style>
  *{
    padding: 0px;
    margin: 0px;
    background: #62374e;
    position: absolute;
  }
  .sqr {
    width: 50px;
    height: 50px;
    background: #fdc57b;
  }
  #s1{
    left: 50px;
    top: 50px
  }
  #s2{
    left: 300px;
    top: 50px
  }
  #s3{
    top: 200px;
    left: 50px
  }
  #s4{
    left: 300px;
    top: 200px
  }
</style>
```