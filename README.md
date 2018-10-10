# HelloMyWorld
我喜欢你的代码！


<!DOCTYPE HTML>
<html>
	<head>
		<meta charset="utf-8" />
		<title></title>
	</head>
	<style type="text/css">
		
		body{
			-webkit-font-smoothing: antialiased;
			background: #000000;
		}
		p{
			color: black;
			text-align: center;
			line-height: 70px;
			font: "楷体";
			font-size:30px;
		}
		.box{
			width: 200px;
			height: 500px;
			position: relative;
			margin: 0 auto;
		}
		.bbb{
			user-select: none;
			cursor: pointer;
			transition: all 0.5s ease;
			position: absolute;
			top: 30px;
			box-shadow: 0 5px 25px black;
			width:250px;
			height: 150px;
			border-radius: 10px;
			transform:  rotateX(45deg) rotateY(-15deg) rotate(35deg);
		}
		.first{
			color: #ADFF2F;
			z-index: 5;
			background: #ADFF2F;
			margin-top: 10px;
		}
		.second{
			color:#FFD700;
			z-index: 4;
			background: #FFD700;
			margin-top: 100px;
		}
		.third{
			color:dodgerblue;
			z-index: 3;
			background: dodgerblue;
			margin-top: 190px;
		}
		.forth{
			color:  darkcyan;
			z-index: 2;
			background: darkcyan;
			margin-top: 280px;
		}
		.fifth{
			color: royalblue;
			z-index: 1;
			background:royalblue;
			margin-top: 370px;
		}
		.bbb:hover{
			box-shadow: 0 0 30px currentColor;
			transform: rotateX(35deg) rotateY(-15deg) rotate(20deg) translate(-35px,40px);
		}
	</style>
	<body>
		<div id="" class="box">
			<div class="bbb first"><p>三国演义</p></div>
			<div class="bbb second"><p>水浒传</p></div>
			<div class="bbb third"><p>西游记</p></div>
			<div class="bbb forth"><p>红楼梦</p></div>
			<div class="bbb fifth"><p>聊斋志异</p></div>
		</div>
	</body>
</html>
