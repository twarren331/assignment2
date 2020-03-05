# assignment2
this is my html code for assignment 2
==============loginHTML===========================
<!DOCTYPE html>
<html lang=“en”>

<head>
	<meta charset=“utf-8”>
	<title>Login</title>
</head>

<body>

	<h1>Login form</h1>

	<form>
		<label for="username">Username</label>
		<input type="text" name="username"/>


		<label for="password">Password</label>
		<input type="password" name="password"/>

		<input type="submit" value="submit">
	</form>

</body>

</html>
===============================registrationHTML====================
<!DOCTYPE html>
<html lang=“en”>

<head>
	<meta charset=“utf-8”>
	<title>Registration</title>
</head>

<body>

	<h1>registration form</h1>

	<form>
		<label for="username">Username</label>
		<input type="text" name="username"/>

		<label for="email">Email</label>
		<input type="email" name="email"/>

		<label for="password">Password</label>
		<input type="password" name="password"/>
		
		<label for="confirmpassword">Confirm Password</label>
		<input type="password" name="confirmpassword"/>

		<input type="checkbox" name="checkbox"/>
		<label for="checkbox">I am at least 13+ years of age</label><br>

		<label for="checkboxPR">I accept <a href="https://...com">TOS and Privacy Rules</a></label>
		<input type="checkbox" name="checkboxPR"/>

		<input type="submit" value="submit">
	</form>

</body>

</html>
================postImageHTML================
<!DOCTYPE html>
<html lang=“en”>

<head>
	<meta charset=“utf-8”>
	<title>Post Image</title>
</head>

<body>

	<h1>Post Image form</h1>

	<form>
		<label for="posttitle">input post title:</label>
		<input type="text" name="posttitle"/>

		<label for="postdescription">input post description:</label>
		<textarea> </textarea>

		<label for="img">input an image:</label>
		<input type="file" name="img"/><br>


		<label for="checkboxAC">Must accept <a href="https://...com">Acceptable use policy for uploading images</a></label>
		<input type="checkbox" name="checkboxAC"/>

		<input type="submit" value="submit image post">
	</form>

</body>

</html>



