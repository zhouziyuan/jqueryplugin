# circle_JT
一个使用canvas编写的圆形进度条

##how to use
```
<body>
	<div id="dom"></div>
	<script>
		$.circleJt({
			domId:'dom',//必需，圆形进度条画布依托的Dom的id
			radius:60,//必需，圆形进度条的半径
			pbColor:'green',//必需，圆形进度条的颜色
  			pbWidth:'5',//非必需，圆形进度条的宽度
	      	value:0,//必需，进度条当前的数值
	      	totalValue:1000,//非必需，进度的总值
	      	percentage:true,//非必需，是否在圆形进度条的中间显示目前进度数
	      	fontSize:18,//非必需，进度数的字号
	      	
            clock:true,//如果clock为真的时候，上述属性除value,totalValue,percentage均无效
            digitalWatch:true//以电子表形式显示
		});
	</script>
</body>
```

##need
```
<script type="text/javascript" src="lib/jquery-1.11.0.js" ></script>
<script type="text/javascript" src="lib/circle_JT.js" ></script>
```



