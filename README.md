<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Surprise</title>
	<meta http-equiv="refresh" content="41;url=file:///C:/Users/Владимир/Desktop/ДляSait/Surprise2.html">
	<script type="text/javascript">
  function startTimer() {
    var my_timer = document.getElementById("my_timer");
    var time = my_timer.innerHTML;
    var arr = time.split(":");
    var h = arr[0];
    var m = arr[1];
    var s = arr[2];
    if (s == 0) {
      if (m == 0) {
        if (h == 0) {
          alert("Время вышло");
          window.location.reload();
          return;
        }
        h--;
        m = 60;
        if (h < 10) h = "0" + h;
      }
      m--;
      if (m < 10) m = "0" + m;
      s = 59;
    }
    else s--;
    if (s < 10) s = "0" + s;
    document.getElementById("my_timer").innerHTML = h+":"+m+":"+s;
    setTimeout(startTimer, 1000);
  }
</script>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
 <script src="https://atuin.ru/demo/ripples/jquery.ripples-min.js"></script>
 
</head>
<style type="text/css">
	body,html{
		width: 100%;
		height: 100%;
	}
	body{
		margin: 0px;
		padding: 0px;
		background: #223C6D;
background: -webkit-linear-gradient(top left, #223C6D, #E35BFF);
background: -moz-linear-gradient(top left, #223C6D, #E35BFF);
background: linear-gradient(to bottom right, #223C6D, #E35BFF);
		
	}
	.sparkl{
		position: absolute;
    	top: 18%;
    	left: 46%;
    	transform: translate(-50%,-50%);
    	opacity: .2;
	}
	.txt {

    font-size: 70px;

    text-align: center;
   
    color: #fff;
    -webkit-background-clip: text;

    -webkit-text-fill-color: transparent;
	.txt--cover,
}
    .mid{
    	position: absolute;
    	top: 80%;
    	left: 40%;
    	transform: translate(-50%,-50%);
    }
    
    a{
    	text-align: center;
    	
		width: 50px;
		height: 50px;
		top: 80%;
    	left: 40%;
    	transform: translate(-50%,-50%);
		
    }
    

    .full-landing-image{
		width: 40%;
		height: 40%;
		background: url('https://cdn.discordapp.com/attachments/462637806041301003/599920420375887872/deals3w5432.png')no-repeat center;
		filter: blur(1px);
		z-index: 2px;
		}

		.landing-image{
			left: 20px;
			top: 20px;
		width: 40%;
		height: 50%;
		transform: translate(100%,-80%);
		filter: blur(1px);
		z-index: 2px;
		
		}

.txt {
    background-image: url('https://i.pinimg.com/736x/2d/19/e7/2d19e76e484781d0197498a463d20698--sakura-anime-purple-thoughts.jpg');
}
     .pisat{
     	font-size: 30px;
     	text-align: center;
     	
     	color: #fff;
    -webkit-background-clip: text;

    -webkit-text-fill-color: transparent;
     }
     .pisat{
     	background-color: #BF70F0;
     }
     .pIs{
     	text-transform: uppercase;
     	font-size: 20px;
     	text-align: center;
     	
     	color: #fff;
    -webkit-background-clip: text;

    -webkit-text-fill-color: transparent;
     }
     .pIs{
     	background-color: #DB85A5;
     }
     .PS{
     	text-transform:uppercase;
     	font-size: 15px;
     	text-align: center;
     	
     	color: #fff;
    -webkit-background-clip: text;

    -webkit-text-fill-color: transparent;
     }
     .PS{
     	background-color: #ECA7D6;
     }
	


	.BubleS{
		position: absolute;
		width: 100%;
		height: 100%;
		z-index: 0px;
		overflow: hidden;
        top: 0px;
        left: 0px; 

	}
	.bubl{
		position: absolute;
		bottom: 0px;
	    z-index: 0px;
		background-color: #EED2F9;
		border-radius: 50%;
		opacity: 0.5;
		animation: flying 10s infinite ease-in;
	}
	.bubl:nth-child(1){
			width: 40px;
		height: 40px;
		left: 10%;
		animation-direction: 8s;

	}
	.bubl:nth-child(2){
		width: 20px;
		height: 20px;
		left: 20%;
		animation-direction: 5s;
		animation-delay: 1s;
	}
	.bubl:nth-child(3){
		width: 50px;
		height: 50px;
		left: 35%;
		animation-direction: 10s;
		animation-delay: 2s;
	}
	.bubl:nth-child(4){
		width: 80px;
		height: 80px;
		left: 50%;
		animation-direction: 7s;
		animation-delay: 0s;
	}
	.bubl:nth-child(5){
		width: 34px;
		height: 34px;
		left: 55%;
		animation-direction: 6s;
		animation-delay: 2s;
	}
	.bubl:nth-child(6){
		width: 45px;
		height: 45px;
		left: 65%;
		animation-direction: 8s;
		animation-delay: 4s;
	}
	.bubl:nth-child(7){
		width: 25px;
		height: 25px;
		left: 75%;
		animation-direction: 7s;
		animation-delay: 2s;
	}
	.bubl:nth-child(8){
		width: 80px;
		height: 80px;
		left: 80%;
		animation-direction: 6s;
		animation-delay: 1s;
	}
	.bubl:nth-child(9){
		width: 15px;
		height: 15px;
		left: 70%;
		animation-direction: 9s;
		animation-delay: 0s;
	}
	.bubl:nth-child(10){
		width: 50px;
		height: 50px;
		left: 85%;
		animation-direction: 5s;
		animation-delay: 3s;
	}
	@keyframes flying{
		0%{
			bottom: -100px;
			transform: translateX(0px);
		}
		50%{
			transform: translateX(100px);
		}
		100%{
			bottom: 1080px;
			transform: translateX(-200px);
		}
	}

</style>
<body onload="startTimer()">
	<p><span id="my_timer" style="color: #8C65D7; font-size: 120%; font-weight: bold; text-transform: uppercase; ">▻ Подожди еще.. 0:0:42 </span></p>
	<img class="sparkl" src="https://avatars.mds.yandex.net/get-pdb/1025599/eb0262fb-016e-43a6-9863-805baa992219/orig">
	<div class="txt">○ ◦mini_Surprise◦ ○</div>
	<h3 class="pisat"> ◦Хей-хей!◦</h3>
	<h4 class="pIs">Хотела показать этот мини сюрприз for you)
	Надеюсь вам понравиться)</h4>
	<p class="PS">❍ На деле тут мало что интересного ,но можно глянуть картинки и пожмякать ссылки, посмотреть за плавающими шариками на заднем фоне) ❍</p>
<div class="full-landing-image"></div>
<img class="landing-image" src="https://cdn.discordapp.com/attachments/462637806041301003/599920340772192267/2018-08-19_03-13-162.png">
    
  <div class="BubleS">
  	 <div class="bubl"></div>
  	 <div class="bubl"></div>
  	 <div class="bubl"></div>
  	 <div class="bubl"></div>
  	 <div class="bubl"></div>
  	 <div class="bubl"></div>
  	 <div class="bubl"></div>
  	 <div class="bubl"></div>
  	 <div class="bubl"></div>
  	 <div class="bubl"></div>
  </div>
  <script type="text/javascript">
  $('full-landing-image').ripples({
    resolution: 256,
    dropRadius: 20,
    perturbance: 0.04,
});
  
  
  


  </script>
</body>
</html>
