three_column_layout
===================

Simple HTML/CSS header, footer, and three column layout
=======================================================

HTML

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>3 column layout</title>
<link rel="stylesheet" type="text/css" href="style.css" />
</head>

<body>
<div id="container">
<div class="header">
<h1>HEADER</h1>
</div>
<div class="left">
<h2>Left</h2> <br />
Column
</div>
<div class="center">
<h2>Center</h2>
</div>
<div class="right">
<h2>Right </h2><br />
Column
</div>
<div class="footer">
<h1>FOOTER</h1>
</div>
</div>
</body>
</html>
====================
CSS
@charset "utf-8";
/* CSS Document */

#container{
margin: 0 auto;
width: 960px;	
}
.header{
height: 150px;
background-color:#3C0;	
text-align:center;
}
.left{
width: 30%;
height: 325px;
background-color:#300;	
float:left;
text-align:center;
}
.center{
width: 55%;
height: 325px;
background-color: fff;	
float: left;
text-align:center;
}
.right{
width: 15%;
height: 325px;
background-color:#C0C;
float:right;
text-align:center;	
}
.footer{
clear:both;
height:150px;
background-color:#006;	
text-align:center;
}
h1 {
font-family:"Comic Sans MS", cursive;
color:#F00;	
}
h2 {
font-family:Georgia, "Times New Roman", Times, serif;
color:#3CF;
font-size:16px;	
}


