# [Target #4 - Ups n Downs](https://cssbattle.dev/play/4)

![](https://cssbattle.dev/targets/4.png)

Solution

```HTML
<div class="iwrap">
	<div class="pill bg"></div>
	<div class="pill d"></div>
</div>
<div class="iwrap">
	<div class="pill u"></div>
	<div class="pill bg"></div>
</div>
<div class="iwrap">
	<div class="pill bg"></div>
	<div class="pill d"></div>
</div>
<style>
	body{
	    width:100%;
	    height:100%;
	    background:#62306D;
	    margin:0;
	    padding:0;
	    display:flex;
	    justify-content:center;
	    align-items:center;
	  }
	  .bg{
	    background: #62306D !important;
	  }
	  .pill{
	    height:100px;
	    width:100px;
	    background:#F7EC7D;
	  }
	  .u{
	    border-radius: 50% 50% 0 0;
	  }
	  .d{
	    border-radius: 0 0 50% 50%
	  }
</style>
```