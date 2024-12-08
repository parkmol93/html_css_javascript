<!DOCTYPE html>
<html>
	<head>
		<link rel="stylesheet" href="style.css">
	</head>
	
	<div class="login">
		<button type="submit">
			Log in with Google
		</button>
		
		<fieldset>
			<legend>OR</legend>
			<p>or</p>
		</fieldset>
		
		<label for="USERNAME">아이디
			<form action="#" method="post">
				<input type="text" id="USERNAME" name="username" placeholder="Username" value="Null">
			</form>
				</label>
		
		<label for="PASSWORD">비밀번호
			<form action="#" method="post">
				<input type="password" id="PASSWORD" name="passwrod" placeholder="Password" value="Null">
			</form>
		</label>
		
		<button type="submit">
			LOGIN
		</button>
		<p>
			<a href="#" target="_blank" title="find-password">
			Forgot your password?
		</a>
		</p>
	</div>
	
	
	
	
</html>




*{
	margin: 0;
	padding: 0;
	box-sizing: border-box;
}

.login{
	margin: 100px 0;
	padding: 28px 38px;
	border: 1px solid #000;
	text-align: center;
}

label input{
	background-color:#eaeaea;
	
}

button[type="submit"]:nth-of-type(2){
	background-color:#373F3C;
}

fieldset{
	border:none;
}

legend{
	position:absolute; /*display:absolute; (X) */
	top:-9999px;
}

a{
	text-decoration: none;
}
