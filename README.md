
<p float="left">
  <img src="image1.png" width="400" />
</p>
# Informational Page
<p float="left">
  <img src="calfire1.jpeg" width="400" />
  <img src="calfire2.jpeg" width="400" /> 
</p>
# Importance 




/**
 * Layout with the two lines at both sides without using additional elements (only :after and :before)
 */

div {
	background: #fff;
	width:100%;
	height:30px;
	text-align: center;
	position: relative;
}

div:before,
div:after {
	background:#0a0;
	content: "";
	height:30px;
	width:30%;
	right:0;
	position: absolute;
	z-index: 1;
}

div:before{
	left:0;
	right:auto;
}

div > ul {
	display:inline-block;
	position: relative;
	z-index:2;
}

div > ul li {
	float:left;	
}
