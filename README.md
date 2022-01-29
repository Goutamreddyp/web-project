# web-project code
<html>
<head>
<title>
Smile plz
</title>
<style>
.p {
  font-family: "Comic Sans MS", cursive, sans-serif;
}
body {font-family: Arial, Helvetica, sans-serif;}
/* Full-width input fields */
input[type=text], input[type=password] {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  box-sizing: border-box;
}
/* Set a style for all buttons */
button {
  background-color:black;
  color: white;
  opacity: 0.8;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  border-radius: 80px;
  width: 100%;
}
button:hover {
  opacity: 0.8;
}
/* Center the image and position the close button */
.imgcontainer {
  text-align: center;
  margin: 24px 0 12px 0;
  position: relative;
}

img.avatar {
  width: 30%;
  border-radius: 50%;
}

.container {
  padding: 16px;
}

span.psw {
  float: right;
  padding-top: 16px;
}
/* The Modal (background) */
.modal {
  display: none; /* Hidden by default */
  position: fixed; /* Stay in place */
  z-index: 1; /* Sit on top */
  left: 30%;
  top: 10%;
  opacity: 0.8;
  width: 50%; /* Full width */
  height: 80%; /* Full height */
<!--overflow: auto; /* Enable scroll if needed */-->
  background-color: rgb(0,0,0); /* Fallback color */
  background-color:none; 
  padding-top: 10px;
}
/* Modal Content/Box */
.modal-content {
  background-color: #fefefe;
  margin: 0.1% auto 10% auto; /* 5% from the top, 15% from the bottom and centered */
  border: 1px solid #888;
  width: 40%; /* Could be more or less, depending on screen size */
}
/* The Close Button (x) */
.close {
  position: absolute;
  right: 25px;
  top: 0;
  color: #000;
  font-size: 35px;
  font-weight: bold;
}
.close:hover,
.close:focus {
  color: red;
  cursor: pointer;
}
/* Add Zoom Animation */
.animate {
  -webkit-animation: animatezoom 0.6s;
  animation: animatezoom 0.6s
}
@-webkit-keyframes animatezoom {
  from {-webkit-transform: scale(0)} 
  to {-webkit-transform: scale(1)}
}  
@keyframes animatezoom {
  from {transform: scale(0)} 
  to {transform: scale(1)}
}
/* Change styles for span and cancel button on extra small screens */
@media screen and (max-width: 300px) {
  span.psw {
     display: block;
     float: none;
  }
  .cancelbtn {
     width: 30%;
  }
}
 .header{
		position:fixed;
			height:12.7%;
			width:100%;			
			background-color:none;
			color:none;
			}
			
			Body
{
			background-image:url("slide.jpg");
			background-repeat: no-repeat;
			background-size:cover;
			height:auto;
			width:auto;
  }
  
			 .fotter{
			 position:absolute;
			text-align:center;
			top:90%;
			height:12%;
			width:100%;
			color:black;
			}
	
			ul {
			list-style-type: none;
			margin: 0;
			padding: 0;
			overflow: auto;
			position: sticky;
			background-color:none;
				}
			
			li {
			float:right;
				}

			li a {
			display: block;
			color: black;
			text-align: center;
			padding: 20px 30px;
			text-decoration: none;
					}

			li a:hover {
				background-color:#48C9B0;
			}
input[type=text], select {
  width: 200px;
  padding: 10px 20px;
  margin: 5px 0;
  display: inline-block;
  border: 1px solid #48C9B0;
  border-radius: 80px;
  box-sizing:none;
}
input[type=password], select {
  width: 200px;
  padding: 10px 20px;
  margin: 5px 0;
  display: inline-block;
  border: 1px solid #48C9B0;
  border-radius: 80px;
  box-sizing:none;
}
input[type=number], select {
  width: 200px;
  padding: 10px 20px;
  margin: 5px 0;
  display: inline-block;
  border: 1px solid #48C9B0;
  border-radius: 80px;
  box-sizing:none;
}
input[type=submit] {
  width:250px;
  background-color: #48C9B0;
  color: white;
  padding: 15px 20px;
  margin: 8px 0;
  border: none;
  border-radius: 80px;
  cursor: normal;
}
input[type=submit]:hover {
  background-color: #48C9B0;

}
.Form{

  position:absolute;
	top:150px;
  background-color:none;
  padding: 15px;
}				
		</style>
	
<script language="javascript" type="text/javascript">
  function textFname()
  {
document.getElementById("Fname").innerHTML="Only Alphabets"
  }
function blurFname()
{
var pat1=/[0-9]{10}$/;
var a=document.SAPLAB.Fname.value;
if(a.search(pat1)==-1)
{
document.getElementById("Fname").innerHTML="not valid!!!!";
}
else
{
document.getElementById("Fname").innerHTML="Done!!";
}
}
		function textLname()
  {
document.getElementById("Lname").innerHTML="Only Alphabets"
  }
function blurLname()
{
var pat2=/[0-9]{5}/;
var b=document.SAPLAB.Lname.value;
if(b.search(pat2)==-1)
{
document.getElementById("Lname").innerHTML="Contains Other than Alpha Values!!!";
}
else
{
document.getElementById("Lname").innerHTML="";
}
}	
        </script>	
		</head>

		<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
		<body >
		  <div class="header">
<ul>
<a href="Home.html">
<img src="logo.png" width="150" height="75" href="Home.html" alt="">  
</a>
<li><a class="active" onclick="document.getElementById('id01').style.display='block'" >Login</a></li>
<li><a class="active" href="Contact.html">Contact Us</a></li>
<li><a class="active" href="Ourteam.html">Our Team</a></li>
<li><a class="active" href="OurServices.html">Our Services</a></li>
<li><a class="active" href="AboutUs.html">About us</a></li>
  <li><a class="active" href="Home.html">Home</a></li>
</ul>
 </div>
<div class="p">
<div class="form">

<div id="id01" class="modal">
  
  <form class="modal-content animate" action="/action_page.php">
    <div class="imgcontainer">
      <span onclick="document.getElementById('id01').style.display='none'" class="close" title="Close Modal">&times;</span>
      <img src="admin.jpg" alt="Avatar" class="avatar">
    </div>

    <div class="container">
	<center>
      <label for="uname"><b>Username</b></label>
      <input type="text" placeholder="Enter Username" name="uname" required>
		<br>
      <label for="psw"><b>Password</b></label>
      <input type="password" placeholder="Enter Password" name="psw" required>
        </center>
      <button type="submit">Login</button>
      <label>
        <input type="checkbox" checked="checked" name="remember"> Remember me
      </label>
    </div>

    <!----<div class="container" style="background-color:#f1f1f1">
      <button type="button" onclick="document.getElementById('id01').style.display='none'" class="cancelbtn">Cancel</button>
      <span class="psw">Forgot <a href="#">password?</a></span>
    </div>  ---->
  </form>
</div>
<table>
  <form method="post" action="appointment.php"> 
<tr>
<th><h2>BOOK APPOINTMENT</h2></th> 
</tr>
<tr>
<th><label>Name:</label></th>
<td><input type="text" id="fname" name="name" placeholder="Name" onfocus="textFname();" onblur="blurFname();" required></td>
</tr><br>
<tr>
<th><label>Phone No:</label></th>
    <td><input type="number" id="phone" name="Phone" placeholder="Phone No" required></td>
</tr><br>
<tr>
<th><label>Email:</label></th>
    <td><input type="text" id="email" name="email" placeholder="Email" required></td>
</tr><br>
<tr>
<tr>
<th>
  <center><input type="submit" value="Book Appointment" name="ap" ></center>
  </th>
  
  </form>
   <?php 
 if(isset($_POST['ap']))
  {
$name=$_POST["name"]; 
$ph=$_POST["phone"];
 $em=$_POST["email"]; 
 
$conn=mysql_connect("localhost","root","");
 if(!$conn)
 {    
    die("could not connect" . mysql_error());
 }
 
 mysql_select_db("smile"); 
 
 $insert="insert into appointment(name,phone,email) values('$name','$ph','$em')"; 
 $insertresult=mysql_query($insert,$conn);  
 if(!$insertresult)  
 {      
      die("Query not executed" . mysql_error());   
 }   
 mysql_close($conn);
 print "Your booking is confirm......";
 //header("location:http://localhost/smile_pls/Home.html");
}
 ?> 
  </table>
  </div>
</div>
  <div class="fotter">
  <p>follow us:</p><a href="#" class="fa fa-facebook"></a>
<a href="#" class="fa fa-twitter"></a>
<a href="#"  class="fa fa-instagram"></a>
<a href="#"  class="fa fa-skype"></a>
  </div>
<script>
// Get the modal
var modal = document.getElementById('id01');
// When the user clicks anywhere outside of the modal, close it
window.onclick = function(event) {
    if (event.target == modal) {
        modal.style.display = "none";
    }
}
</script>
		</body>
		</html>
(about us)
<html>
<head>
<title>
Smile plz
</title>
<style>

.p {
  font-family: "Comic Sans MS", cursive, sans-serif;
}
 .header{
		position:fixed;
			height:12.7%;
			width:100%;			
			background-color:none;
			color:none;
			}
			
			body{
			background-image:url("slide.jpg");
			opacity: 0.8;
			filter: alpha(opacity=50);
			background-repeat: no-repeat;
			background-size:cover;
			height:auto;
			width:auto;
  }
  
			 .fotter{
			 position:absolute;
			text-align:center;
			top:90%;
			height:12%;
			width:100%;
			color:black;
			}
      		 .center{
			 position:fixed;
			 text-align:center;
			top:68px;
			height:78%;
			width:100%;
			background-color:#48C9B0;
			color:white;
			}
			ul {
			list-style-type: none;
			margin: 0;
			padding: 0;
			overflow: auto;
			position: sticky;
			background-color:none;
				}
			li {
			float:right;
				}
			li a {
			display: block;
			color: black;
			text-align: center;
			padding: 20px 30px;
			text-decoration: none;
					}
			li a:hover {
				background-color:#48C9B0;
			}
		</style>
		</head>
		<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
		<body >
		  <div class="header">
<ul>
<a href="Home.html">
<img src="logo.png" width="150" height="75" href="Home.html" alt="">  
</a>
<li><a class="active" href="Contact.html">Contact Us</a></li>
<li><a class="active" href="Ourteam.html">Our Team</a></li>
<li><a class="active" href="OurServices.html">Our Services</a></li>
<li><a class="active" href="AboutUs.html">About us</a></li>
  <li><a class="active" href="Home.html">Home</a></li>
</ul>
 </div>

<div class="center">
<form>
  <fieldset>
  <div class="p">
    <h3><u>ABOUT US</u></h3>
  Here at Smile Care our patients come first.<br>
We have friendly staff, a clean facility and excellent customer service.
<h5><u>*CUSTOMIZATION*</u></h5>
We Built Dental Care Treatment Services For All Your Requirements.
<h5><u>*DOCTORS SUPPORT*</u></h5>
Doctors will Provide good Advice For Your Dentistry.
 <h5><u>*CUSTOMIZED TREATMENT LABS*</u></h5>
Smile Care is primarily build Better Infrastructure labs and Operation Theatres ready to You.
 <h5><u>*SATISFIED CUSTOMERS*</u></h5>
Smile Care given Satisfaction to Every Patients.
  </fieldset>
</form>
</div>
</div>
  <div class="fotter">
  <p>follow us:</p><a href="#" class="fa fa-facebook"></a>
<a href="#" class="fa fa-twitter"></a>
<a href="#"  class="fa fa-instagram"></a>
<a href="#"  class="fa fa-skype"></a>
  </div>
		</body>
		</html>
(our team)

<html>
<head>
<title>
Smile plz
</title>
<style>

 .header{
		position:fixed;
			height:12.7%;
			width:100%;			
			background-color:none;
			color:none;
			}
			
			body{
			background-image:url("slide.jpg");
			background-repeat: no-repeat;
			background-size:cover;
			height:auto;
			width:auto;
  }
 
			 .fotter{
			 position:absolute;
			text-align:center;
			top:90%;
			height:12%;
			width:100%;
			color:black;
			}
			ul {
			list-style-type: none;
			margin: 0;
			padding: 0;
			overflow: auto;
			position: sticky;
			background-color:none;
				}
			li {
			float:right;
				}
			li a {
			display: block;
			color: black;
			text-align: center;
			padding: 20px 30px;
			text-decoration: none;
					}
			li a:hover {
				background-color:#48C9B0;
			}

.left1{
			position:fixed;
			top:170px;
			height:50%;
			left:17px;
			background-image:url("doctor3.jpg");
			width:23%;
			background-repeat: no-repeat;
			background-size:cover;
			border-style: double;
			background-color:white;
			color:none;
			border-radius: 50px;
			}		
	.left2{
		position:fixed;
		top:170px;
		left:350px;
			height:50%;
			border-style: double;
			width:23%;			
			background-image:url("doctor2.jpg");
			background-repeat: no-repeat;
			background-size:cover;
			background-color:white;
			color:none;
			border-radius: 50px;
}	
	.left3{
		position:fixed;
		top:170px;
		border-style: double;
		left:680px;
		background-image:url("doctor1.jpg");
		background-repeat: no-repeat;
			background-size:cover;
			height:50%;
			width:23%;			
			background-color:white;
			color:none;
			border-radius: 50px;
			}
	.left4{
		position:fixed;
		top:170px;
		border-style: double;
		left:1010px;
			height:50%;
			background-image:url("doctor.png");
		background-repeat: no-repeat;
			background-size:cover;
			width:23%;			
			background-color:white;
			color:none;
			border-radius: 50px;
			}		
	.center{
		position:fixed;
		top:100px;
		left:620px;
		color:black;
			}
	.text-block {
		position: absolute;
		top: 280px;
		right: 120px;
		background-color:none;
		color:black;
		align:center;
}		
		</style>
		
		</head>
		<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
		<body >
		  <div class="header">
<ul>
<a href="Home.html">
<img src="logo.png" width="150" height="75" href="Home.html" alt="">  
</a>
<li><a class="active" href="Contact.html">Contact Us</a></li>
<li><a class="active" href="Ourteam.html">Our Team</a></li>
<li><a class="active" href="OurServices.html">Our Services</a></li>
<li><a class="active" href="AboutUs.html">About us</a></li>
  <li><a class="active" href="Home.html">Home</a></li>
</ul>
 </div>
 <div class="center">
 <h2><u><b>OUR TEAM</b></u></h2>
</div>
<div class="left1">
<div class="text-block">
<b>DR. Leana Wen</b>
</div>
</div>
<div class="left2">
<div class="text-block">
<b>DR. Will Kirby</b>
</div>
</div>
<div class="left3">
<div class="text-block">
<b>DR. Michael Klaper</b>
</div>
</div>
<div class="left4">
<div class="text-block">
<b>DR. Lucian Leape</b>
</div>
</div>
  <div class="fotter">
  <p>follow us:</p><a href="#" class="fa fa-facebook"></a>
<a href="#" class="fa fa-twitter"></a>
<a href="#"  class="fa fa-instagram"></a>
<a href="#"  class="fa fa-skype"></a>
  </div>
		</body>
		</html>

(contact)

<html>
<head>
<title>
Smile plz
</title>
<style>
.p {
  font-family: "Comic Sans MS", cursive, sans-serif;
}
 .header{
		position:fixed;
			height:12.7%;
			width:100%;			
			background-color:none;
			color:none;
			}
			body{
			background-image:url("slide1.jpg");
			background-repeat: no-repeat;
			background-size:cover;
			height:auto;
			width:auto;
  }

  .fotter{
			 position:absolute;
			text-align:center;
			top:90%;
			height:12%;
			width:100%;
			color:black;
			}
			ul {
			list-style-type: none;
			margin: 0;
			padding: 0;
			overflow: auto;
			position: sticky;
			background-color:none;
				}
			li {
			float:right;
				}
			li a {
			display: block;
			color: black;
			text-align: center;
			padding: 20px 30px;
			text-decoration: none;
					}
			li a:hover {
				background-color:#48C9B0;
			}
.left{
			 position:absolute;
			left:50px;
			top:20%;
			height:12%;
			width:50%;
			color:black;
			}
.down{
			 position:absolute;
			left:50px;
			top:50%;
			height:12%;
			width:50%;
			color:black;
			}
input[type=text], select {
  width: 200px;
  height: 40px;
  padding: 10px 20px;
  margin-right: 5px;
  margin-top:25px;	
  display: inline-block;
  border: 1px solid #48C9B0;
  border-radius: 50px;
  box-sizing:none;
}
input[type=number], select {
  width: 200px;
  height: 40px;
  padding: 10px 20px;
  margin-right: 5px;
  margin-top:25px;	
  display: inline-block;
  border: 1px solid #48C9B0;
  border-radius: 50px;
  box-sizing:none;
}
input[type=submit] {
  width:250px;
  background-color: #48C9B0;
  color: white;
  padding: 15px 20px;
  margin-top: 70px;
  border: none;
  border-radius: 80px;
  cursor: normal;
}

input[type=submit]:hover {
  background-color: #48C9B0;
}
.Form{
  position:none;
  top:150px;
  background-color:none;
  padding: 15px;
}		
		</style>
</head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<body >
		  <div class="header">
<ul>
<a href="Home.html">
<img src="logo.png" width="150" height="75" href="Home.html" alt="">  
</a>
<li><a class="active" href="Contact.html">Contact Us</a></li>
<li><a class="active" href="Ourteam.html">Our Team</a></li>
<li><a class="active" href="OurServices.html">Our Services</a></li>
<li><a class="active" href="AboutUs.html">About us</a></li>
  <li><a class="active" href="Home.html">Home</a></li>
</ul>
 </div>
<div class="p">
<div class="left">
<h4>VISIT OUR CLINIC</h4>
Smile Care Dental Clinic<br>
274, 2nd cross, Cambridge Layout,<br>
Halasuru, Bangalore - 560008<br>
(Near Sai Baba Temple )
</div>
<div class="down">
OFFICE HOURS<br>
Monday to Sunday :<br>
9.30 am to 1pm | 4.30 pm to 8 pm<br>
</div>
<div class="form">
<table align="right">
  <form method="post" action="feedback.php">
<tr>
<th><h2>SEND US A MESSAGE</h2></th> 
</tr>
<tr>
<th><label>Name:</label></th>
<td><input type="text" id="fname" name="name" placeholder="Name" required></td>
</tr><br>
<tr>
<th><label>Phone No:</label></th>
    <td><input type="number" id="phone" name="phone" placeholder="Phone No" required></td>
</tr><br>
<tr>
<th><label>Email:</label></th>
    <td><input type="text" id="email" name="email" placeholder="Email" required></td>
</tr><br>
<tr>
<th><label>Give Us Details</label></th>
    <td><input type="text" id="details" name="details" placeholder="Details" required></td>
</tr><br>
<tr>
	<th>
    <center><input type="submit" value="SEND MESSAGE" name="fb"></center>
  </th>
  
  </form>
  <?php 
 if(isset($_POST['fb']))
  {
$name=$_POST["name"]; 
$ph=$_POST["phone"];
 $em=$_POST["email"]; 
 $dt=$_POST["details"];
 
$conn=mysql_connect("localhost","root","");
 if(!$conn)
 {    
    die("could not connect" . mysql_error());
 }
 mysql_select_db("smile"); 
 
 $insert="insert into feedback(name,phone,email,details) values('$name','$ph','$em','$dt')"; 
 $insertresult=mysql_query($insert,$conn);  
 if(!$insertresult)  
 {      
      die("Query not executed" . mysql_error());   
 }   
 mysql_close($conn);
 print "feedback sent succesfully!!!!!!!";
 //header("location:http://localhost/smile_pls/Home.html");
}
 ?> 
</table>
  </div>
</div>
  <div class="fotter">
  <p>follow us:</p><a href="#" class="fa fa-facebook"></a>
<a href="#" class="fa fa-twitter"></a>
<a href="#"  class="fa fa-instagram"></a>
<a href="#"  class="fa fa-skype"></a>
  </div>
</body>
</html>

(admin login)

<html>
<head>
<title>
Smile plz
</title>
<style>
.p {
  font-family: "Comic Sans MS", cursive, sans-serif;
}
 .header{
		position:fixed;
			height:12.7%;
			width:100%;			
			background-color:none;
			color:none;
			}
			body{
			background-image:url("slide.jpg");
			opacity: 0.8;
			filter: alpha(opacity=50);
			background-repeat: no-repeat;
			background-size:cover;
			height:auto;
			width:auto;
  }
			 .fotter{
			 position:absolute;
			text-align:center;
			top:90%;
			height:12%;
			width:100%;
			color:black;
			}
			ul {
			list-style-type: none;
			margin: 0;
			padding: 0;
			overflow: auto;
			position: sticky;
			background-color:none;
				}
			li {
			float:right;
				}
			li a {
			display: block;
			color: black;
			text-align: center;
			padding: 20px 30px;
			text-decoration: none;
					}
			li a:hover {
				background-color:#48C9B0;
			}
		</style>
		</head>
		<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
		<body >
		  <div class="header">
<ul>
<a href="Home.html">
<img src="logo.png" width="150" height="75" href="Home.html" alt="">  
</a>
<li><a class="active" href="Contact.html">Contact Us</a></li>
<li><a class="active" href="Ourteam.html">Our Team</a></li>
<li><a class="active" href="OurServices.html">Our Services</a></li>
<li><a class="active" href="AboutUs.html">About us</a></li>
  <li><a class="active" href="Home.html">Home</a></li>
</ul>
 </div>
  <div class="fotter">
  <p>follow us:</p><a href="#" class="fa fa-facebook"></a>
<a href="#" class="fa fa-twitter"></a>
<a href="#"  class="fa fa-instagram"></a>
<a href="#"  class="fa fa-skype"></a>

  </div>
		</body>
		</html>

(admin )

<html>
<head>
<title>
Smile plz
</title>
<style>
.p {
  font-family: "Comic Sans MS", cursive, sans-serif;
}
 .header{
		position:fixed;
			height:12.7%;
			width:100%;			
			background-color:none;
			color:none;
			}
			
			body{
			background-image:url("slide.jpg");
			opacity: 0.8;
			filter: alpha(opacity=50);
			background-repeat: no-repeat;
			background-size:cover;
			height:auto;
			width:auto;
  }
			 .left{
			 position:absolute;
			left:100px;
			top:20%;
			height:12%;
			width:50%;
			color:black;
			}
			 .right{
			 position:absolute;
			left:1200px;
			top:20%;
			height:12%;
			width:50%;
			color:black;
			}
			 .fotter{
			 position:absolute;
			text-align:center;
			top:90%;
			height:12%;
			width:100%;
			color:black;
			}
			ul {
			list-style-type: none;
			margin: 0;
			padding: 0;
			overflow: auto;
			position: sticky;
			background-color:none;
				}
			li {
			float:right;
				}
			li a {
			display: block;
			color: black;
			text-align: center;
			padding: 20px 30px;
			text-decoration: none;
					}
			li a:hover {
				background-color:#48C9B0;
			}

input[type=button] {
  width:250px;
  background-color: #48C9B0;
  color: white;
  padding: 15px 20px;
  margin: 8px 0;
  border: none;
  border-radius: 80px;
  cursor: normal;
}	
		</style>
		</head>
		<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
		<body >
		  <div class="header">
<ul>
<a href="Home.html">
<img src="logo.png" width="150" height="75" href="Home.html" alt="">  
</a>
<li><a class="active" href="Contact.html">Contact Us</a></li>
<li><a class="active" href="Ourteam.html">Our Team</a></li>
<li><a class="active" href="OurServices.html">Our Services</a></li>
<li><a class="active" href="AboutUs.html">About us</a></li>
  <li><a class="active" href="Home.html">Home</a></li>
</ul>
 </div>
<div class="left">
 <form>
         <input type="button" onclick=; value="Show Appointment"/>
      </form>
</div>
<div class="right">
 <form>
         <input type="button" onclick=; value="Show Feedback"/>
      </form>
</div>
  <div class="fotter">
  <p>follow us:</p><a href="#" class="fa fa-facebook"></a>
<a href="#" class="fa fa-twitter"></a>
<a href="#"  class="fa fa-instagram"></a>
<a href="#"  class="fa fa-skype"></a>

  </div>
		</body>
		</html>
