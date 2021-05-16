# [Target #3 - Push Button](https://cssbattle.dev/play/3)

![](https://cssbattle.dev/targets/3.png)

Solution

```HTML
<div class="wrap">
	<div class="rec">
		<div id="o-ring" class="circle">
			<div id="i-ring" class="circle">
				<div id="bullseye" class="circle"></div>
			</div>
		</div>
	</div>
</div>
<style>
	body {
	margin: 0;
	padding: 0;
	background: #6592cf
    }
    .wrap {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100%
    }
    .rec {
        width: 300px;
        height: 150px;
        background: #243d83;
        top: 100px;
        display: flex;
        justify-content: center;
        align-items: center
    }
    .circle {
        border-radius: 50%
    }
    #o-ring {
        background: #6592cf;
        height: 250px;
        width: 250px;
        display: flex;
        justify-content: center;
        align-items: center
    }
    #i-ring {
        background: #243d83;
        height: 150px;
        width: 150px;
        display: flex;
        justify-content: center;
        align-items: center
    }
    #bullseye {
        background: #eeb850;
        height: 50px;
        width: 50px
    }
</style>
```