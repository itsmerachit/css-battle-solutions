# [Target #15 - Overlap](https://cssbattle.dev/play/15)

![](https://cssbattle.dev/targets/15.png)

Solution

```HTML
<div class="circle" id="lt"></div>
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
    }
    #lt{
        transform: translateX(25px);
    }
    #rt{
        background: #E78481;
        transform: translateX(-25px);
    }
</style>
```