# [Target #16 - Eye of the Tiger](https://cssbattle.dev/play/16)

![](https://cssbattle.dev/targets/16.png)

Solution

```HTML
<div id="tleft"></div>
<div id="circle"></div>
<div id="tright"></div>

<style>
    body {
        background: #0B2429;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    #circle {
        z-index: 2;
        width: 50px;
        height: 50px;
        border-radius: 50%;
        box-shadow: 
            0 0 0 45px #F3AC3C,
            0 0 0 65px #0B2429,
            0 0 0 75px #998235
    }
    #tleft {
        margin-right: 56px;
        width: 0;
        height: 0;
        border-top: 60px solid transparent;
        border-bottom: 60px solid transparent;
        border-right: 60px solid #998235;
    }
    #tright {
        margin-left: 56px;
        width: 0;
        height: 0;
        border-top: 60px solid transparent;
        border-bottom: 60px solid transparent;
        border-left: 60px solid #998235;
    }
</style>
```