<!DOCTYPE html>
<html>
<head>
	<title>字体变大或变小</title>
	<meta charset="utf-8"/>
	<script>
	window.onload = function () {
		var oBtn1 = document.getElementById("btn1");
		var oBtn2 = document.getElementById("btn2");
		var oBtn3 = document.getElementById("btn3");
		var oBtn4 = document.getElementById("btn4");
		var oP = document.getElementById("p1");
		var num = 16;
		oBtn1.onclick = function () {
			num++;
			oP.style.fontSize = num + "px";
		};
		oBtn2.onclick = function () {
			num--;
			oP.style.fontSize = num + "px";
		};
		oBtn3.onclick = function () {
			oP.className = "red";
		};
		oBtn4.onclick = function () {
			oP.className = "yellow";
		};
	};
	</script>
	<style>
	.red {
		width: 300px;
		background: red;
		color: white;
		padding: 20px;
		border: 10px solid #ccc;
	}
	.yellow {
		width: 500px;
		background: yellow;
		color: black;
		padding: 50px;
		border: 10px solid #ccc;
	}
	</style>
</head>
<body>
<input type="button" value="+" id="btn1" />
<input type="button" value="-" id="btn2" />
<input type="button" value="红" id="btn3" />
<input type="button" value="黄" id="btn4" />
<p id="p1" class="">CCTV-4（中文国际频道）于1992年10月1日正式开播。当时还未呼号“国际频道”，只有中央电视台4套节目，定位于“以文化为主的综合频道”，并开始对外播出。当初播出的节目除中文外，还包括了英语在内的外语节目，以及包括粤语在内的汉语方言节目。目前，CCTV-4分别面向亚洲、欧洲、美洲播出，为中国中央电视台以海外华人、华侨和香港、澳门、台湾作为主要观众对象的频道，在中国内地也有相当规模的收视人群。</p>
</body>
</html>
