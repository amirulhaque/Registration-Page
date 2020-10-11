# Registration-Page
For new user registration by using html
<!D0CTYPE html>
<html>
<head>
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Registration Form</title>
	<style>
 body {font-family: Arial, Helvetica, sans-serif;}
/** {box-sizing: border-box;}*/

input[type=text], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}

input[type=password], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}


input[type=submit] {
  background-color: #4CAF50;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}

.container {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
  position: relative;
}



</style>
</head>
<body>

<h1>Registration Form</h1>


<form  method="get">
  <div class="container">
  	<label for="fname"><b>First Name</b></label>
    <input type="text" id="fname" name="firstname" placeholder="Your name">

    <label for="lname"><b>Last Name</b></label>
    <input type="text" id="lname" name="lastname" placeholder="Your last name">

    <label for="email"><b>Email</b></label>
    <input type="text" id="email" required placeholder="Enter Email">

     <label for="phone"><b>phone number</b></label><br>
  <input type="text" id="phone" name="phone" placeholder="Enter Number" pattern="[0-9]{10}" required>

    <label for="psw"><b>Password</b></label>
    <input type="password" placeholder="Enter Password" name="psw" id="psw" required>

    <label for="psw-confirm"><b>Confirm Password</b></label>
    <input type="password" placeholder="Confirm Password" name="psw-confirm" id="psw-confirm" required>
    <h3>Gender</h3>
     <input type="radio" id="male" name="gender" value="male">
    <label for="male">Male</label><br>
    <input type="radio" id="female" name="gender" value="female">
    <label for="female">Female</label><br>
    <input type="radio" id="Other" name="gender" value="Other">  
    <label for="other">Other</label>
    <br><br>
    <input type="submit" value="Submit">

  </div>
</form>
</body>
</html>

    
