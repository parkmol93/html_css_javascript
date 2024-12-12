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





<!DOCTYPE html>
<html>
	<head>
		<link rel="stylesheet" href="style.css">
	</head>
	
	<div class="TOC">
		<p>목차</p>
		
		<ol>
			<li>역사
				<ol>
					<li>개발</li>
					<li>최초 규격</li>
					<li>표준 버전의 역사
						<ol>
							<li>HTML 버전 스케줄</li>
							<li>HTML 초안 버전 스케쥴</li>
							<li>XHTML 버전</li>
						</ol>
					</li>
				</ol>
			<li>마크업
				<ol>
					<li>HTML 요소</li>
					<li>데이터 형식</li>
					<li>문서 형식 선언</li>
				</ol>
			</li>
		</ol>
	</div>
	
	
	
	
</html>







<!DOCTYPE html>
<html>
	<head>
		<link rel="stylesheet" href="style.css">
	</head>
	
	<div class="flex-container">
		<div class=pic_1></div>
		<div class=pic_2></div>
		<div class=pic_3></div>
		<div class=pic_4></div>
		<div class=pic_5></div>
		<div class=pic_6></div>
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




*{
	margin: 0;
	padding: 0;
	box-sizing: border-box;
	font-size: 13px;
}

.TOC{
	width: 346px;
	height: 265px;
	padding: 6px; 5px; 12px; 5px;]
	margin: 100px auto;
	border: 1px solid #000;
}





*{
	margin: 0;
	padding: 0;
	box-sizing: border-box;
}

.flex-container{
	display: flex;
	flex-direction: row;
	flex-wrap: wrap;
	width: 510px;
	height: auto; /*스크롤을 위해 고정 높이 제거*/
}

.flex-container > div{
	width: calc(33.33% - 10px); /* 한 줄에 3개씩 배치 */
	height: 240px;
	margin: 5px;
	border: 1px solid #000;
	
}

.flex-container > div:nth-child(1){
	background-image:url("#");
	background-size: cover;
	background-position: center;
	background-attachment: scroll;
}
