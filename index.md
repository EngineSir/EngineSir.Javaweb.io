<!DOCTYPE html>
<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<link rel="stylesheet" href="styles/login.css"/>
<!-- 引入jquery -->
<script type="text/javascript" src="scripts/jquery.min.js">
</script>
<script type="text/javascript" src="scripts/login.js"></script>
<script type="text/javascript" src="scripts/path.js"></script>
<script type="text/javascript" src="scripts/cookie_util.js"></script>
<script type="text/javascript">
//加载完body后调用该函数
	$(function(){
		//登录功能
		$("#login").click(userLogin);
	});
</script>
</head>
	<body>
		<div class="global">
			<div class="log log_in" tabindex='-1' id='dl'>
				<dl>
					<dt>
						<div class='header'>
							<h3>登&nbsp;录</h3>
						</div>
					</dt>
					<dt></dt>
					<dt>
						<div class='letter'>
							用户名:&nbsp;<input type="text" name="" id="count" tabindex='1'/>
							<span id="count_span" hidden="hidden">*</span>
						</div>
					</dt>
					<dt>
						<div class='letter'>
							密&nbsp;&nbsp;&nbsp;码:&nbsp;<input type="password" name="" id="password" tabindex='2'/>
							<span id="password_span" hidden="hidden">*</span>
						</div>
					</dt>
					<dt>
						<div>
							<input type="button" name="" id="login" value='&nbsp登&nbsp录&nbsp' tabindex='3'/>
						</div>
					</dt>
				</dl>
			</div>	
		</div>
	</body>
</html>
© 2018 GitHub, Inc.
