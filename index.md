
<html>
<head>
<style>
.button {
	padding: 15 px 25px;
	font-size: 24 px;
	text-align: center;
	cursor: pointer;
	outline: none;
	color: #fff;
	background-color: #4CAF50;
	border: none;
	border-radius: 15px;
	box-shadow: 0 9px #999;
	float: center;
}

.button:hover {
	background-color: #3e8e41;
}

.button:active {
	background-color: #3e8e41;
	box-shadow: 0 5px #666;
	transform: translateY(4px);
}

.button {
	border-radius: 4px;
	background-color: #d63d54;
	border: none;
	color: #FFFFFF;
	text-align: center;
	font-size: 28px;
	padding: 20px;
	width: 200px;
	transition: all 0.5s;
	cursor: pointer;
	margin: 0 0 555px 560px;
}

.button span {
	cursor: pointer;
	display: inline-block;
	position: relative;
	transition: 0.5s;
}

.button span:after {
	content: '>>';
	position: absolute;
	opacity: 0;
	top: 0;
	right: -20px;
	transition: 0.5s;
}

.button:hover span {
	padding-right: 25px;
}

.button:hover span: after {
	opacity: 1;
	right: 0;
}

img {
	border-radius: 50%;
	float: center;
	margin: 0 0 50px 465px;
}

</style>
	<link rel="stylesheet" href="background page.css">
</head>
<body>

<h2 style="font-family: helvetica" align="center"><marquee>Welcome to my Personal Website.</marquee></h2>
<img src="B612-2017-11-12-14-32-33.jpg" width="400px" height="300px">
<a href="bio.html">
<button class="button">Continue</button></a>


</body>
</html>
