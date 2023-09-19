<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">


<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
<title>Welcome to My Web Site</title>


<style type="text/css" media="all">
:link,:visited { text-decoration:none }
ul,ol { list-style:none }
h1,h2,h3,h4,h5,h6,pre,code { font-size:small; }ul,ol,li,h1,h2,h3,h4,h5,h6,pre,form,body,html,p,blockquote,fieldset,input{ margin:0; padding:0 }
a img,:link img,:visited img { border:none }
address { font-style:normal }


body {
margin:0px;
padding:0px;
background-color:#fff;
overflow-x:hidden;
}

img.bg {
position:absolute;
left:0px;
top:0px;
z-index:0;
}



div.og {
position:absolute;
top:0px;
/*
left:60%;
float:right;
width:40%;
*/
z-index:5;
left:0;
width:100%;
margin:0px;
}

#contentblock{
	display:block;
	width:600px;
	height:2500px;
	background-color:#fff;
	margin:0px auto;
}


</style>
<script type="text/javascript">
function resizeImg() {

var mybg = document.getElementById('mybgimg');
var winW = (window.innerWidth) ? window.innerWidth : document.body.offsetWidth;
var winH = (window.innerHeight) ? window.innerHeight : document.body.offsetHeight;
var newImgH = 0;
var newImgW = 0;
var imgW = mybg.getAttribute('width');
var imgH = mybg.getAttribute('height');
var winR = winW/winH
var oldRatio = imgW/imgH;
var newRatio;


if(winR <= oldRatio)
{
newImgH = winH;
newImgW = Math.round(winH * (imgW/imgH));
}
else
{
newImgH = Math.round(winW * (imgH/imgW));
newImgW = winW;
}
newRatio = newImgW/newImgH;

// these document.write is what I used to see what was going on and it helped
// figure out the math for the if else statement above.
//document.write("width = " + winW + " and height = " + winH + "<br />");
//document.write("pic width = " + imgW + " and height = " + imgH + "<br />");
//document.write("new pic width = " + newImgW + " and height =" + newImgH + "<br />");
//document.write("window ratio = " + (winW/winH) + "<br />");
//document.write("Old Pic ratio = " + oldRatio + "<br />");
//document.write("New Pic ratio = " + newRatio + "<br />");


//mybg.style.height = null; don't need these next three lines after all
//mybg.style.width = null;

//(winH <= winW) ? mybg.style.height = winH + 'px' : mybg.style.width = winW + 'px';

mybg.setAttribute('width',newImgW);
mybg.setAttribute('height',newImgH);
}

window.onload = resizeImg;
window.onresize = resizeImg;
</script>



</head>

<body>

<img class="bg" border="0" src="./car.jpg" id="mybgimg" width="1024" height="682" alt="test" />







<div class="og">

	<div id="contentblock">
			<h1>Welcome to My Web Site</h1>
			<h3>This web site is still under construction and some parts will always be changed or added to.</h3>
			<h4>Updated October 2005&nbsp;&nbsp;</h4>
	</div>

</div>





</body>

</html>
<h1 align="center">Hi 👋, I'm Aditya Kumar</h1>
<h3 align="center">A Passionate software Engineer Developer from India</h3>
<img align="right" alt="coding" width="400" src=" https://user-images.githubusercontent...
">
<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=adityakumarcs" alt="adityakumarcs" /></a> </p>

<p align="left"> <a href="https://twitter.com/adityayada35632" target="blank"><img src="https://img.shields.io/twitter/follow/adityayada35632?logo=twitter&style=for-the-badge" alt="adityayada35632" /></a> </p>

- 🌱 I’m currently learning **java**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://twitter.com/adityayada35632" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="adityayada35632" height="30" width="40" /></a>
<a href="https://instagram.com/thisisadityadav" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="thisisadityadav" height="30" width="40" /></a>
<a href="https://www.hackerrank.com/@adityadav9917831" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/hackerrank.svg" alt="@adityadav9917831" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=adityakumarcs&show_icons=true&locale=en&layout=compact" alt="adityakumarcs" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=adityakumarcs&show_icons=true&locale=en" alt="adityakumarcs" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=adityakumarcs&" alt="adityakumarcs" /></p>
