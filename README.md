# hover-effect-.txt
any one can use 
their is following code 
 
1st the following code write down in html
 
 <!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewpoint" content="width=device-width, initial-scale=1.0">
	<title>classes</title>
	<link rel="stylesheet" type="text/css" href="css/style2.css">
</head>
<body>

     <div class="card">
     	<div class="content">
     		<h2>Class 9th</h2>
     		<p>If you click the button given in below then you can find everything related to your subject. 
     		In the next page you can easily able to get any video lecture related to subject, notes ,sample papers ,questions & answers
     		of any subject </p>
     		<a href="#">Click Here</a>
     	</div>
     <img src="img.png">
    </div>
</body>
</html>

2ND THE FOLLOWING CODE WRITE IN  CSS 

@import url(('https://fonts.googleapis.com/css2?family=Lato&display=swap');
*
{
	margin: 0;
	padding: 0;
	box-sizing: border-box;
	font-family: 'Lato', sans-serif;
}
body
{
	display: flex;
	background: linear-gradient(100deg,);
	justify-content: center;
	align-items: center;
	min-height: 100vh;
}
.card
{
	position: relative;
	width: 600px;
	height: 350px;
	margin: 20px;
	display: flex;
	justify-content: flex-start;
	align-items: center;
	border-radius: 20px;
	background: linear-gradient(105deg,#462446,#b05f6d,#eb6b56,#ffc153,#47b39d);
}
.card img
{
	position: absolute;
	bottom:  0;
	left: 50%;
	transform: translateX(-50%);
	height: 400px;
	transition: 0.5s;
}
.card:hover img
{
	left: 80%;
	height: 500px;
}
.card .content
{
	position: relative;
	width: 50%;
	left: 20%;
	padding: 20px 20px 20px 40px;
	opacity: 0;
	visibility: hidden;
	transition: 0.5s;
}
.card:hover .content
{
     left: 0%;
     visibility: visible;
     opacity: 1;
}
.card .content h2
{
	color: #fff;
	text-transform: uppercase;
	font-size:2.5em;
	line-height: 1em; 
}
.card .content p
{
	color: black;
}
.card .content a
{
	position: relative;
	display: inline-block;
	color: #111;
	padding: 10px 20px;
	border-radius: 10px;
	background: #fff;
	margin-top: 10px;
	text-decoration: none;
}
@media (max-width: 991px)
{

     .card 
     {
            position: relative;
            width: 600px;
            height: 350px;
            transition: 0.5s;
            align-items: flex-start
     }
     .card:hover
     {
     	height: 600px;
     } 
     .card:hover img
   {
	   left: 50%;
	   height: 350px;
   }
   .card .content 
   {

    width: 100%;
    left: 0;
    padding: 40px;
  
   }
}
@media (max-width: 420px)
{
    .card .content 
   {
     padding: 30px;
   }
       .card:hover img
   {
	   height: 300px;
   }
}




