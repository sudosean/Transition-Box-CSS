Transition-Box-CSS
==================
.box {
	position: relative;
	background: gold;
	float: left;
	width: 360px;
	height: 360px;
	margin: 20px;
	overflow: hidden;
	padding: 20px;

	-webkit-transition: all 1s ease;
	-moz-transition: all 1s ease;
	-ms-transition: all 1s ease;
	transition: all 1s ease;
}

.box .more {
	padding: 20px;
	opacity: 0;
	background-color: rgba(0,0,0,.6);
	position: absolute;
	top:0;
	bottom:0;
	left: 0;
	right: 0;

	-webkit-transition: all .5s ease;
	-moz-transition: all .5s ease;
	-ms-transition:all .5s ease;
	transition: all .5s ease;
boxes styled in CSS with a 1s ease transition into content 
