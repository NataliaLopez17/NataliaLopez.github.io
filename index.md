body, html {
	height: 100%;
	margin: 0;
	background-image: url(https://res.cloudinary.com/natalialopez17/image/upload/v1581794482/online%20portfolio/photo-1517260911058-0fcfd733702f_u5hjhs.jpg);
	min-height: 1000px;

	background-attachment: fixed;
	background-position: center;
	background-repeat: no-repeat;
	background-size: cover;
}

.parallax{
	/* The image used */
	background-image: 
	url("https://res.cloudinary.com/natalialopez17/image/upload/v1581972911/online%20portfolio/photo-1476733753947-ae6bd5805081_jvigtz.jpg");

	/* Full height */ 
	min-height: 1000px;
	width: 100%;

	/* Center and scale the image nicely */
	background-attachment: fixed;
	background-position: center;
	background-repeat: no-repeat;
	background-size: cover;

}

.name{
	font-size: 150px;
	position: absolute;
	margin-top: 150px;
	margin-left: 500px;
	font-family: 'Lemonada', cursive;

}
.info{
	font-size: 50px;
	position: absolute;
	margin-top: 370px;
	margin-left: 450px;
	font-family: 'Amatic SC', cursive;
}

.projects a:hover{
	text-decoration: none;
}


/*-------------------------------------------------------------------------------------------------------------------------------*/
.about{
	width: 200px;
	padding: 10px;
	border: 5px solid black;
	margin: 5px;
	text-align: center;
	line-height: 38px;
	font-size: 30px;
	text-transform: uppercase;
	letter-spacing: 2px;
	background-color: #5B6C5B;
	color: white;
	display: block;
	font-family: 'Lemonada', cursive;

}
.about-word{
	font-size: 30px;
}
.about-description{
	margin-top: 50px;
	font-size: 15px;
}
.row {
	display: flex;
	flex-wrap: wrap;
	padding: 0 4px;
}

/* Create four equal columns that sits next to each other */
.column {
	flex: 25%;
	max-width: 25%;
	padding: 0 4px;
}

.column img {
	margin-top: 8px;
	vertical-align: middle;
	width: 100%;
}

/* Responsive layout - makes a two column-layout instead of four columns */
@media screen and (max-width: 800px) {
	.column {
		flex: 50%;
		max-width: 50%;
	}
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
	.column {
		flex: 100%;
		max-width: 100%;
	}
}

/*----------------------------------------------------------------------------------------------------------------------------------*/


.menu-bar{
	height: auto;
	text-align: center;
}
.natalia{
	display: block;
	background-color: #5B6C5B;
}

.menu-bar > ul> li{
	display: inline-block;
	padding: 10px;
	padding-right: 50px;
	font-family: 'Amatic SC', cursive;
}
.menu-bar ul li{
	position: relative;
}
li{
	box-sizing: -webkit-match-parent;
}
.menu-bar ul{
	font-size: 0;
	list-style: none;
}

.menu-bar ul li a{
	display: block;
	text-decoration: none;
	line-height: 45px;
	font-size: 12px;
	text-transform: uppercase;
	letter-spacing: 2px;
	color: white;
}
a{
	background: transparent;
}
a:hover{
	background-color: black;
	opacity: 50%;
	padding: 5px;
	text-decoration: none;
}

/*-----------------------------------------------------------------------------------*/
/* Style inputs with type="text", select elements and textareas */
input[type=text], select, textarea {
	width: 100%; /* Full width */
	padding: 12px; /* Some padding */ 
	border: 1px solid #ccc; /* Gray border */
	border-radius: 4px; /* Rounded borders */
	box-sizing: border-box; /* Make sure that padding and width stays in place */
	margin-top: 6px; /* Add a top margin */
	margin-bottom: 16px; /* Bottom margin */
	resize: vertical; /* Allow the user to vertically resize the textarea (not horizontally) */

}

/* Style the submit button with a specific background color etc */
input[type=submit] {
	padding: 12px 20px;
	border: none;
	border-radius: 4px;
	cursor: pointer;
	text-transform: uppercase;
	letter-spacing: 2px;
	color: black;
	font-family: 'Lemonada', cursive;
}

input[type=email]{
	width: 100%; /* Full width */
	padding: 12px; /* Some padding */ 
	border: 1px solid #ccc; /* Gray border */
	border-radius: 4px; /* Rounded borders */
	box-sizing: border-box; /* Make sure that padding and width stays in place */
	margin-top: 6px; /* Add a top margin */
	margin-bottom: 16px; /* Bottom margin */
	resize: vertical /* Allow the user to vertically resize the textarea (not horizontally) */
}

/* When moving the mouse over the submit button, add a darker green color */
input[type=submit]:hover {
	background-color: black;
	opacity: 50%;
	color: white;
}

/* Add a background color and some padding around the form */
.container {
	border-radius: 5px;
	background-color: #f2f2f2;
	padding: 20px;
}
.email-form{
	background-color: #5B6C5B;
	border: 5px solid black;
	margin: 5px;
	text-transform: uppercase;
	letter-spacing: 2px;
	color: white;
	font-family: 'Lemonada', cursive;
}


/*-------------------------------------------------------------------------------------------------------------*/
.pInterests{
	background-color: #F9B31F;
	font-size: 50px;
	width: 25%;
	text-align: center;
	padding: 10px;
	position: relative;
	z-index: 1;
	border-radius: 25px;
	margin-left: 100px;
	text-transform: uppercase;
	letter-spacing: 2px;
	font-family: 'Lemonada', cursive;
}
.inline-rectangle{
	width: 100%;
	height: 160px;
	position: relative;
	background-color: #5B6C5B;
	margin-top: -70px;
	border-radius: 25px;
}
.interests-content{
	background-color: #D9AA52;
	color: white;
	width: 75%;
	border-radius: 25px;
	height: 300px;
	margin-top: -100px;
	z-index: 1;
	position: relative;
	margin-left: 200px;
	font-family: 'Amatic SC', cursive;

}
.word-list-i{
	text-transform: uppercase;
	letter-spacing: 2px;
	height: 100%;
	width: 100%; 
	font-size: 20px;
	list-style-type: none;

}
.word-list-i li{
	position: relative;
	padding: 10px;
}
.reading:before{
	font-family: FontAwesome;
	display: inline-block;
	padding: 10px;
	left: -5px;
	content: "\f02d";
}
.tv:before{
	font-family: FontAwesome;
	display: inline-block;
	padding: 10px;
	left: -5px;
	content: "\f26c";
}
.german:before{
	font-family: FontAwesome;
	display: inline-block;
	padding: 10px;
	left: -5px;
	content: "\f1ab";
}
.travel:before{
	font-family: FontAwesome;
	display: inline-block;
	padding: 10px;
	left: -5px;
	content: "\f072";
}
.videogames:before{
	font-family: FontAwesome;
	display: inline-block;
	padding: 10px;
	left: -5px;
	content: "\f11b";
}
/*----------------------------------------------------------------------------------------------------------------------------------*/


.pClasses{
	background-color: #F9B31F;
	font-size: 50px;
	width: 50%;
	text-align: center;
	padding: 10px;
	position: relative;
	z-index: 1;
	border-radius: 25px;
	margin-left: 700px;
	margin-top: -470px;
	text-transform: uppercase;
	letter-spacing: 2px;
	font-family: 'Lemonada', cursive;
}
.classes-content{
	color: white;
	width: 75%;
	border-radius: 25px;
	height: 300px;
	margin-top: 20px;
	z-index: 1;
	position: relative;
	margin-left: 800px;

}
.word-list-c{
	text-transform: uppercase;
	letter-spacing: 2px;
	height: 100%;
	width: 100%; 
	font-size: 20px;
	list-style-type: none;
	font-family: 'Amatic SC', cursive;

}
.word-list-c li{
	position: relative;
	padding: 10px;
}
.ciic3011:before{
	font-family: FontAwesome;
	display: inline-block;
	padding: 10px;
	left: -5px;
	content: "\f121";
}
.ciic4010:before{
	font-family: FontAwesome;
	display: inline-block;
	padding: 10px;
	left: -5px;
	content: "\f121";
}
.ciic4020:before{
	font-family: FontAwesome;
	display: inline-block;
	padding: 10px;
	left: -5px;
	content: "\f121";
}
/*---------------------------------------------------------------------------------------------------------------------------------*/
.chevron-up{
	background-color: #CC684E;
	width: 100%;
	position: relative;
	padding: 10px;
	margin-top: 50px;
	border-radius: 20px;
	

}
