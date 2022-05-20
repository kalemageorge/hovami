<!DOCTYPE html>
<meta charset="UTF-8">
<html>
	<head>
	<link rel="stylesheet" href="design.css">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>HOVAMI ||HOME</title><!--<img src="webpic5.jpg" alt="H" style="border-radius:50%;">-->
	<script>//src="http://code.jquery.com/jquery-3.6.0.js"
								
				function show(){
					alert("Not available yet");
							}
				function dr(){
						toggle(5000);
								}
	
		</script>
		<style>
				.flip-box {
				  background-color: transparent;
				  width: 550px;
				  height: 300px;
				  border: 1px solid #f1f1f1;
				  border-radius:20px 20px 20px 20px;
				  perspective: 1000px;
				}

				.flip-box-inner {
				  position: relative;
				  width: 100%;
				  height: 100%;
				  text-align: center;
				  transition: transform 0.8s;
				  transform-style: preserve-3d;
				}

				.flip-box:hover .flip-box-inner {
				  transform: rotateY(180deg);
				}

				.flip-box-front, .flip-box-back {
				  position: absolute;
				  width: 100%;
				  height: 100%;
				  -webkit-backface-visibility: hidden;
				  backface-visibility: hidden;
				}

				.flip-box-front {
				  background-color: #bbb;
				  color: black;
				  border-radius:20px 20px 20px 20px;
				  text-align:right;
				  font-size:1px;
				}
				.flip-box-front a{
					text-decoration:none;
					font-size:3rem;
					color:white;
					}

				.flip-box-back {
				  background: grey;
				  border-radius:20px 20px 20px 20px;
				  color: white;
				  transform: rotateY(180deg);
				}
		@media screen and (min-width:400px)and (max-width:600px){		
					.dropdown-content{
							max-width:330px;
							display:none;
						}
		.flip-box {
				  width: 100%;
				  height: 250px;
				  font-size:10px;
				  }
		.flip-box-inner {
			 font-size:1.7em;
				  }
				}
				
		.dropbtn {
		border-radius:20px 20px 20px 20px;
  background-color: transparent;
  padding: 50px;
  font-size: 50px;
  border: none;
  cursor: pointer;
}

.dropbtn:hover, .dropbtn:focus {
  background-color: transparent;
}

.dropdown {
  position: relative;
  display: inline-block;
}

.dropdown-content {
		background-size:100%;
		width: 1150px;
		background:url("back.jpeg");
	    display: none;
	    position: absolute;
	    background-color: #f1f1f1;
	    min-width: 160px;
	    overflow: auto;
	    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
	    z-index: 1;
		line-height:10px;
}

.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
}

.dropdown a:hover {background-color: #ddd;}

.show {display: block;}														}
				  
		</style>

	</head>
	
	<header style="background-image: url(back.jpeg); border-radius:20px 20px 20px 20px;">
			<div class="row1">
				<div class="column1">
					<div class="dropdown">
						<!--<p style="font-family:agency fb; text-align:left" class="dropp"><b>Ministries</b></p>-->
						<button onclick="myFunction()" class="dropbtn">|||</button>
							<div id="myDropdown" class="dropdown-content">
							<div class="row">
								<div class="column">
									<p class="pic3" style="text-align:center">Ministries</p>
									<a href="#" onclick="show()">Golden Sky Chior</a>
									<a href="#" onclick="show()">Precious Obadiah</a>
									<a href="#" onclick="show()">Worship Team</a>
									<a href="#" onclick="show()">Evangelism</a>
									<a href="#" onclick="show()">Daughters of Destiny</a>
								</div>
								<div class="column">
									<p class="pic3"> ...</p>
									<a href="#" onclick="show()">Sunday School</a>
									<a href="#" onclick="show()">Victorious Youths</a>
									<a href="#" onclick="show()">Sound</a>
									<a href="#" onclick="show()">Media</a>
								</div>
								<div class="column">
									<p class="pic3">About us</p>
									<a href="history.html" onclick="show()">History</a>
									<a href="https://www.google.com/maps/place/HOVAMI/@0.3351071,32.5545173,17z/data=!3m1!4b1!4m5!3m4!1s0x177dbb05cba95185:0x1a640951184363e6!8m2!3d0.3351071!4d32.556706" target="_blank">Location</a>
								
								</div>
								<div class="column">
									<p class="pic3">Connect</p>
									<a href="#" target="_blank">Facebook</a>
									<a href="https://www.instagram.com/" target="_blank">Instagram</a>
									<a href="https://www.google.com/search?client=firefox-b-d&ei=h9epXZeEF4XawQKarqPwDA&q=hovami-youtube&oq=hovami-youtube&gs_l=psy-ab.3..0i8i13i30l5.6004.13051..13438...0.0..0.277.1948.2-8......0....1..gws-wiz.LumW6Rcd4AE&ved=0ahUKEwjX49WnjablAhUFbVAKHRrXCM4Q4dUDCAo&uact=5" target="_blank">Youtube</a>
							
								</div>
							</div>

							<!--<a href="#" target="_blank">Golden Sky Chior</a>
								<a href="#" target="_blank">Precious Obadiah</a>
								<a href="#" target="_blank">Worship Team</a>
								<a href="#" target="_blank">Door to Door Evangelism</a>
								<a href="#" target="_blank">Open Air Evangelism</a>
								<a href="#" target="_blank">Daughters of Destiny</a>
								<a href="#" target="_blank">Sunday School</a>
								<a href="#" target="_blank">Victorious Youths</a>
								<a href="#" target="_blank">Sound</a>
								<a href="#" target="_blank">Media</a>
								<a href="history.html" target="_blank">History</a>
								<a href="https://www.google.com/maps/place/HOVAMI/@0.3351071,32.5545173,17z/data=!3m1!4b1!4m5!3m4!1s0x177dbb05cba95185:0x1a640951184363e6!8m2!3d0.3351071!4d32.556706" target="_blank">Location</a>
								<a href="https://accounts.google.com/ServiceLogin/signinchooser?service=mail&passive=true&rm=false&continue=https%3A%2F%2Fmail.google.com%2Fmail%2F&ss=1&scc=1&ltmpl=default&ltmplcache=2&emr=1&osid=1&flowName=GlifWebSignIn&flowEntry=ServiceLogin" target="_blank">Email</a>
								<a href="https://www.instagram.com/" target="_blank">Instagram</a>
								<a href="https://www.google.com/search?client=firefox-b-d&ei=h9epXZeEF4XawQKarqPwDA&q=hovami-youtube&oq=hovami-youtube&gs_l=psy-ab.3..0i8i13i30l5.6004.13051..13438...0.0..0.277.1948.2-8......0....1..gws-wiz.LumW6Rcd4AE&ved=0ahUKEwjX49WnjablAhUFbVAKHRrXCM4Q4dUDCAo&uact=5" target="_blank">Youtube</a>-->
							</div>
					</div>
				</div>
				<div class="column1">
					<div class="deliv2">
				HOVAMI
		</div>
					<!--<p class="p1">HOVAMI</p>-->
				</div>
			</div>
	</header>
	<br />
	<script>
/* When the user clicks on the button, 
toggle between hiding and showing the dropdown content */
function myFunction() {
  document.getElementById("myDropdown").classList.toggle("show");
}

// Close the dropdown if the user clicks outside of it
window.onclick = function(event) {
  if (!event.target.matches('.dropbtn')) {
    var dropdowns = document.getElementsByClassName("dropdown-content");
    var i;
    for (i = 0; i < dropdowns.length; i++) {
      var openDropdown = dropdowns[i];
      if (openDropdown.classList.contains('show')) {
        openDropdown.classList.remove('show');
      }
    }
  }
}
</script>	

	<body>	
					<!-- basis of the church-->
		<div class="deliv">
				DELIVERANCE
		</div><br />		
	
	<br />
	<!--the first row for the site explaining the founders-->
		<div class="row2">
			<div class="column2">
				<div class="flip-box">
				  <div class="flip-box-inner">
					<div class="flip-box-front" style="background:url(webpic5.jpg); background-size:cover">
					<a href="#" onclick="show()">Read more</a><!--<img src="webpic5.jpg" alt="HOVAMI" style="width:100%;height:100%;border-radius:20px 20px 20px 20px;">-->
					</div>
					<div class="flip-box-back">
					  <h2>SENIOR PASTOR</h2>
					  <p><b><i><u>Pr Yiga Peter Abyokya</u></i></b>,the founder of House of victory and miracles international church Kasubi-kawaala. A living testimony, here to save the Lord, to help you understand the Authority one has on earth</p>
					  <a href="#" target="_blank">Read more</a>
					</div>
				  </div>
				</div>
			</div>
	
			<div class="column2">
				<div class="flip-box">
				  <div class="flip-box-inner">
					<div class="flip-box-front" style="background:url(bk11.jpg); background-size:cover">
						<a href="#" onclick="show()">Read more</a><!--<img src="bk11.jpg" alt="Paris" style="width:100%;height:100%;border-radius:20px 20px 20px 20px;">-->
					</div>
					<div class="flip-box-back">
					  <h2>Paris</h2>
					  <p>What an amazing city</p>
					</div>
				  </div>
				</div>
			</div>
		</div><br />
							<!-- displaying pictures that change randomly with time duration 10s-->
		<div class="movingpics">
			
		</div><br />
							<!-- the worshiping and praising teams in the church-->
		<div class="row2">
			<div class="column2">
				<div class="flip-box">
				  <div class="flip-box-inner">
					<div class="flip-box-front" style="background:url(webpic5.jpg); background-size:cover">
					  <a href="#" onclick="show()">Read more</a><!--<img src="webpic5.jpg" alt="HOVAMI" style="width:100%;height:100%;border-radius:20px 20px 20px 20px;">-->
					</div>
					<div class="flip-box-back">
					  <h2>GOLDEN SKY CHIOR</h2>
					  <p>Once small now inspiring lives. The team makes praise and worship special. Travels in many worship places just to bring the sound of music to the ears of God's people. The love to worship the Lord Almighty</p>
					  <a href="#" target="_blank">Read more</a>
					</div>
				  </div>
				</div>
			</div>
			
			<div class="column2">
				<div class="flip-box">
				  <div class="flip-box-inner">
					<div class="flip-box-front" style="background:url(webpic11.jpg); background-size:cover">
					   <a href="#" onclick="show()">Read more</a><!--<img src="webpic11.jpg" alt="Paris" style="width:100%;height:100%;border-radius:20px 20px 20px 20px;">-->
					</div>
					<div class="flip-box-back">
					  <h2>WORSHIP TEAM</h2>
					  <p>The team one of kind, praise and worship at another level. You want dance to the Lord, come see how to do it. There is passion to dance for Him.</p>
					  <a href="#" target="_blank">Read more</a>
					</div>
				  </div>
				</div>
			</div>
		</div><br />
		
		<div class="movingpics">
			
		</div><br />
		
					<!--The row2 explaing the evagelism and sunday school teams-->
			<div class="row2">
			<div class="column2">
				<div class="flip-box">
				  <div class="flip-box-inner">
					<div class="flip-box-front" style="background:url(webpic15.jpg); background-size:cover">
					    <a href="#" onclick="show()">Read more</a><!--<img src="webpic15.jpg" alt="Paris" style="width:100%;height:100%;border-radius:20px 20px 20px 20px;">-->
					</div>
					<div class="flip-box-back">
					  <h2>Evangelism</h2>
					  <p>Once small now inspiring lives. The team makes praise and worship special. Travels in many worship places just to bring the sound of music to the ears of God's people. The love to worship the Lord Almighty</p>
					  <a href="#" target="_blank">Read more</a>
					</div>
				  </div>
				</div>
			</div>
			
			<div class="column2">
				<div class="flip-box">
				  <div class="flip-box-inner">
					<div class="flip-box-front" style="background:url(webpic2.jpg); background-size:cover">
					  <a href="#" onclick="show()">Read more</a><!-- <img src="webpic2.jpg" alt="Paris" style="width:100%;height:100%;border-radius:20px 20px 20px 20px;">-->
					</div>
					<div class="flip-box-back">
					  <h2>SUNDAY SCHOOL</h2>
					  <p>Teaching the chidren of God, naturing, the future tomorrow. Let the children come to me and do not stop them, because the Kingdom of heaven belongs to such as these. Matthew 19:14</p>
					  <a href="#" target="_blank">Read more</a>
					</div>
				  </div>
				</div>
			</div>
		</div><br />
		
		<div class="righ">
			<a href="#" target="_blank">F </a><br />
			<a href="#" target="_blank">Y </a><br />
			<a href="#" target="_blank">I  </a><br />
			<a href="#" target="_blank">T  </a><br />
			<a href="#" target="_blank">W  </a><br />
		</div>
		
	</body>

	<footer>
		<div class="foot">
			<a href="#" target="_blank">Facebook </a>||
			<a href="#" target="_blank">Youtube </a>||
			<a href="#" target="_blank">Twitter </a>||
			<a href="#" target="_blank">Instagram </a>||
			<a href="#" target="_blank">whatsup </a>||
			<a href="#" target="_blank">Location</a> <br />
			© All rights reserved
		</div>
	</footer>
	
</html>

