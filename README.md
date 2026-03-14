# Ex09 Event Registration Web Application
## Date:14/03/2026

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
login.html
```
<!DOCTYPE html>
<html>
<head>
<title>Login</title>
<style>

body{
font-family:Arial;
background:#f0f2f5;
display:flex;
justify-content:center;
align-items:center;
height:100vh;
}

.container{
width:300px;
background:#e9ecef;
padding:30px;
border-radius:20px;
text-align:center;
}

img{
width:120px;
margin-bottom:20px;
}

input{
width:100%;
padding:10px;
margin:10px 0;
border:none;
border-radius:20px;
background:#ddd;
}

button{
width:100%;
padding:10px;
border:none;
border-radius:20px;
background:#333;
color:white;
cursor:pointer;
}

a{
display:block;
margin-top:10px;
font-size:13px;
}

</style>
</head>

<body>

<div class="container">

<img src="logo.png">

<input type="text" placeholder="Username">

<input type="password" placeholder="Password">

<button>LOGIN</button>

<a href="#">Forget password?</a>

</div>

</body>
</html>
```
sidebar.html
```
<!DOCTYPE html>
<html>
<head>
<title>Menu</title>

<style>

body{
font-family:Arial;
background:#f0f2f5;
}

.sidebar{
width:250px;
height:100vh;
background:#333;
color:white;
padding:20px;
}

h3{
margin-top:20px;
}

.menu div{
padding:12px;
border-bottom:1px solid #555;
cursor:pointer;
}

.menu div:hover{
background:#444;
}

</style>
</head>

<body>

<div class="sidebar">

<h3>CORE</h3>

<div class="menu">
<div>Schedule</div>
<div>My Reward Points</div>
<div>Bookings</div>
</div>

<h3>MANAGE</h3>

<div class="menu">
<div>Groups</div>
<div>Academics</div>
<div>Activities</div>
</div>

</div>

</body>
</html>
```
booking.html
```
<!DOCTYPE html>
<html>
<head>
<title>Event Session Booking</title>

<style>

body{
font-family:Arial;
background:#f0f2f5;
display:flex;
justify-content:center;
align-items:center;
height:100vh;
}

.container{
width:320px;
background:#e9ecef;
padding:20px;
border-radius:20px;
}

h2{
text-align:center;
}

input,select{
width:100%;
padding:10px;
margin-top:10px;
border:none;
border-radius:10px;
background:#ddd;
}

.buttons{
display:flex;
gap:10px;
margin-top:15px;
}

button{
flex:1;
padding:10px;
border:none;
border-radius:10px;
cursor:pointer;
}

.reset{
background:#aaa;
}

.apply{
background:#3b5bff;
color:white;
}

</style>
</head>

<body>

<div class="container">

<h2>Event Session Booking</h2>

<label>Event Term</label>
<select>
<option>25-26 EVENTDAY-03</option>
</select>

<label>From Date</label>
<input type="date">

<label>To Date</label>
<input type="date">

<label>Event Title</label>
<input type="text" placeholder="Search by slot name">

<label>Session Time</label>
<input type="text">

<div class="buttons">
<button class="reset">Reset</button>
<button class="apply">Apply</button>
</div>

</div>

</body>
</html>
```
calendar.html
```
<!DOCTYPE html>
<html>
<head>
<title>Calendar</title>

<style>

body{
font-family:Arial;
background:#f0f2f5;
display:flex;
justify-content:center;
align-items:center;
height:100vh;
}

.calendar{
width:300px;
background:#e9ecef;
padding:20px;
border-radius:20px;
text-align:center;
}

.days{
display:grid;
grid-template-columns:repeat(7,1fr);
gap:5px;
margin-top:15px;
}

.day{
background:white;
padding:10px;
border-radius:5px;
}

.active{
background:#3b5bff;
color:white;
}

</style>
</head>

<body>

<div class="calendar">

<h3>MARCH 2026</h3>

<div class="days">
<div class="day">11</div>
<div class="day">12</div>
<div class="day">13</div>
<div class="day active">14</div>
<div class="day">15</div>
<div class="day">16</div>
<div class="day">17</div>
</div>

<p style="margin-top:20px">
No schedule found for this date
</p>

</div>

</body>
</html>
```
## OUTPUT:
![alt text](<Screenshot 2026-03-14 094236.png>)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
