


<!DOCTYPE html> 
<head> 
	<meta charset="UTF-8">
	<meta name="description" content="Bedr00mZ Website">
	<meta name="author" content="Viktor Tibay">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<meta name="p:domain_verify" content="d40a85ef1a4c40d40c42ca70a2927c16"/> 
			<title>Bedr00mZ</title>
			<link rel="icon" type="image/x-icon" href="images/logo3.png?">
			<link href="style.css" rel="stylesheet" type="text/css" />
			<link rel="preload" href="images/Desk-2024_Viktor_Tibay3.gif" as="image" type="image/gif" />
			<link rel="preload" href="images/characterz3_2023-Viktor_Tibay.gif" as="image" type="image/gif" />
			<link rel="preload" href="images/L0go_YT.jpg" as="image" type="image/jpg" />
			<link rel="preload" href="images/L0go_YT_halo.jpg" as="image" type="image/jpg" />
			<link rel="preload" href="images/L0go_NG.jpg" as="image" type="image/jpg" />
			<link rel="preload" href="images/L0go_NG_halo.jpg" as="image" type="image/jpg" />
			<link rel="preload" href="images/L0go_Shop.jpg" as="image" type="image/jpg" />
			<link rel="preload" href="images/L0go_Shop_halo.jpg" as="image" type="image/jpg" />
			<link rel="preload" href="images/L0go_Insta.jpg" as="image" type="image/jpg" />
			<link rel="preload" href="images/L0go_Insta_halo.jpg" as="image" type="image/jpg" />
			<link rel="preload" href="images/L0go_Tiktok.jpg" as="image" type="image/jpg" />
			<link rel="preload" href="images/L0go_Tiktok_halo.jpg" as="image" type="image/jpg" />
	<style>
 @import url('https://fonts.googleapis.com/css2?family=EB+Garamond:ital@0;1&display=swap');
body {
	background-color: black;
}
.Fr4me {
	width: 1270px;
	margin: 0 auto;
	border: 2px solid black;
	margin:auto;
}
.transform {
  width: 80%;
  overflow: hidden;
  margin: 0 auto;
}
.transform img {
  width: 100%;
  transition: 0.17s all ease-in-out;
}
.transform:hover img {
  transform: scale(1.04);
}
/* Logo_unbr34k4bL */
.Logo {
	display: flex;
	justify-content: center;
	overflow: auto;
	white-space:nowrap;
	width: 1050px;
}
.Logo2 {
	display: flex;
	justify-content: center;
	overflow: auto;
	white-space:nowrap;
	width: 1250px;
	height:150px;
}
.unbr34k4bL {
 	-ms-overflow-style: none;
	scrollbar-width: none;
}
.unbr34k4bL::-webkit-scrollbar {
  display: none;
}
a.button:hover {
position:relative;
top:2px;
left:2px;
}
.sub:hover {
position:relative;
bottom:2px;
right:2px;	    
}

.Donate {
  margin-top: 52px;
  }
.sub {
  margin-top: 40px;
  }
	</style>
</head>

<body>
    <audio id="SFX1" src="https://files.catbox.moe/hngo8j.mp3" type="audio/mp3" preload="auto"></audio>    
    <script>
      var audio = document.getElementById("SFX1");
      audio.volume = 0.05;
    </script>
    <script type="text/javascript">
// <![CDATA[
var colour="lime"; // in addition to "random" can be set to any valid colour eg "#f0f" or "red"
var sparkles=50;

/****************************
*  Tinkerbell Magic Sparkle *
*(c)2005-13 mf2fm web-design*
****************************/
var x=ox=400;
var y=oy=300;
var swide=800;
var shigh=600;
var sleft=sdown=0;
var tiny=new Array();
var star=new Array();
var starv=new Array();
var starx=new Array();
var stary=new Array();
var tinyx=new Array();
var tinyy=new Array();
var tinyv=new Array();

window.onload=function() { if (document.getElementById) {
  var i, rats, rlef, rdow;
  for (var i=0; i<sparkles; i++) {
    var rats=createDiv(3, 3);
    rats.style.visibility="hidden";
    rats.style.zIndex="999";
    document.body.appendChild(tiny[i]=rats);
    starv[i]=0;
    tinyv[i]=0;
    var rats=createDiv(5, 5);
    rats.style.backgroundColor="transparent";
    rats.style.visibility="hidden";
    rats.style.zIndex="999";
    var rlef=createDiv(1, 5);
    var rdow=createDiv(5, 1);
    rats.appendChild(rlef);
    rats.appendChild(rdow);
    rlef.style.top="2px";
    rlef.style.left="0px";
    rdow.style.top="0px";
    rdow.style.left="2px";
    document.body.appendChild(star[i]=rats);
  }
  set_width();
  sparkle();
}}

function sparkle() {
  var c;
  if (Math.abs(x-ox)>1 || Math.abs(y-oy)>1) {
    ox=x;
    oy=y;
    for (c=0; c<sparkles; c++) if (!starv[c]) {
      star[c].style.left=(starx[c]=x)+"px";
      star[c].style.top=(stary[c]=y+1)+"px";
      star[c].style.clip="rect(0px, 5px, 5px, 0px)";
      star[c].childNodes[0].style.backgroundColor=star[c].childNodes[1].style.backgroundColor=(colour=="random")?newColour():colour;
      star[c].style.visibility="visible";
      starv[c]=50;
      break;
    }
  }
  for (c=0; c<sparkles; c++) {
    if (starv[c]) update_star(c);
    if (tinyv[c]) update_tiny(c);
  }
  setTimeout("sparkle()", 40);
}

function update_star(i) {
  if (--starv[i]==25) star[i].style.clip="rect(1px, 4px, 4px, 1px)";
  if (starv[i]) {
    stary[i]+=1+Math.random()*3;
    starx[i]+=(i%5-2)/5;
    if (stary[i]<shigh+sdown) {
      star[i].style.top=stary[i]+"px";
      star[i].style.left=starx[i]+"px";
    }
    else {
      star[i].style.visibility="hidden";
      starv[i]=0;
      return;
    }
  }
  else {
    tinyv[i]=50;
    tiny[i].style.top=(tinyy[i]=stary[i])+"px";
    tiny[i].style.left=(tinyx[i]=starx[i])+"px";
    tiny[i].style.width="2px";
    tiny[i].style.height="2px";
    tiny[i].style.backgroundColor=star[i].childNodes[0].style.backgroundColor;
    star[i].style.visibility="hidden";
    tiny[i].style.visibility="visible"
  }
}

function update_tiny(i) {
  if (--tinyv[i]==25) {
    tiny[i].style.width="1px";
    tiny[i].style.height="1px";
  }
  if (tinyv[i]) {
    tinyy[i]+=1+Math.random()*3;
    tinyx[i]+=(i%5-2)/5;
    if (tinyy[i]<shigh+sdown) {
      tiny[i].style.top=tinyy[i]+"px";
      tiny[i].style.left=tinyx[i]+"px";
    }
    else {
      tiny[i].style.visibility="hidden";
      tinyv[i]=0;
      return;
    }
  }
  else tiny[i].style.visibility="hidden";
}

document.onmousemove=mouse;
function mouse(e) {
  if (e) {
    y=e.pageY;
    x=e.pageX;
  }
  else {
    set_scroll();
    y=event.y+sdown;
    x=event.x+sleft;
  }
}

window.onscroll=set_scroll;
function set_scroll() {
  if (typeof(self.pageYOffset)=='number') {
    sdown=self.pageYOffset;
    sleft=self.pageXOffset;
  }
  else if (document.body && (document.body.scrollTop || document.body.scrollLeft)) {
    sdown=document.body.scrollTop;
    sleft=document.body.scrollLeft;
  }
  else if (document.documentElement && (document.documentElement.scrollTop || document.documentElement.scrollLeft)) {
    sleft=document.documentElement.scrollLeft;
    sdown=document.documentElement.scrollTop;
  }
  else {
    sdown=0;
    sleft=0;
  }
}

window.onresize=set_width;
function set_width() {
  var sw_min=999999;
  var sh_min=999999;
  if (document.documentElement && document.documentElement.clientWidth) {
    if (document.documentElement.clientWidth>0) sw_min=document.documentElement.clientWidth;
    if (document.documentElement.clientHeight>0) sh_min=document.documentElement.clientHeight;
  }
  if (typeof(self.innerWidth)=='number' && self.innerWidth) {
    if (self.innerWidth>0 && self.innerWidth<sw_min) sw_min=self.innerWidth;
    if (self.innerHeight>0 && self.innerHeight<sh_min) sh_min=self.innerHeight;
  }
  if (document.body.clientWidth) {
    if (document.body.clientWidth>0 && document.body.clientWidth<sw_min) sw_min=document.body.clientWidth;
    if (document.body.clientHeight>0 && document.body.clientHeight<sh_min) sh_min=document.body.clientHeight;
  }
  if (sw_min==999999 || sh_min==999999) {
    sw_min=800;
    sh_min=600;
  }
  swide=sw_min;
  shigh=sh_min;
}

function createDiv(height, width) {
  var div=document.createElement("div");
  div.style.position="absolute";
  div.style.height=height+"px";
  div.style.width=width+"px";
  div.style.overflow="hidden";
  return (div);
}

function newColour() {
  var c=new Array();
  c[0]=255;
  c[1]=Math.floor(Math.random()*256);
  c[2]=Math.floor(Math.random()*(256-c[1]/2));
  c.sort(function(){return (0.5 - Math.random());});
  return ("rgb("+c[0]+", "+c[1]+", "+c[2]+")");
}
// ]]>
</script>
<div class="Fr4me">

	<center>
		<div class="transform">
		  <a href="h0me">
		    <img src="images/Desk-2024_Viktor_Tibay3.gif">
		  </a>
		</div>
		<div class="Logo unbr34k4bL">
		  <a href="https://www.youtube.com/@bedr00mz/featured" target="_blank" onmouseover="document.getElementById('SFX1').play()"><img src="images/L0go_YT.jpg" onmouseover="this.src='images/L0go_YT_halo.jpg'" onmouseout="this.src='images/L0go_YT.jpg'" title="Y0uTube" width="100px"></a>
		  <a href="https://tiktok.com/@bedr00mz" target="_blank" onmouseover="document.getElementById('SFX1').play()"><img src="images/L0go_Tiktok.jpg" onmouseover="this.src='images/L0go_Tiktok_halo.jpg'" onmouseout="this.src='images/L0go_Tiktok.jpg'" title="Tikt0k" width="100px"></a>
		  <a href="https://ko-fi.com/bedr00mz" target="_blank" onmouseover="document.getElementById('SFX1').play()"><img src="images/L0go_Ko-fi.jpg" onmouseover="this.src='images/L0go_Ko-fi_halo.jpg'" onmouseout="this.src='images/L0go_Ko-fi.jpg'" title="Supp0rt Bedr00mZ on K0-fi" width="100px"></a>
		  <a href="../h0me#Sh0p" target="_blank" onmouseover="document.getElementById('SFX1').play()"><img src="images/L0go_Shop.jpg" onmouseover="this.src='images/L0go_Shop_halo.jpg'" onmouseout="this.src='images/L0go_Shop.jpg'" title="Sh0p" width="170px"></a>
    </div>
    </center>
    <br>
    <center>
    <div class="Logo2 unbr34k4bL">
    
    <a class="sub" href="https://www.youtube.com/@bedr00mz?sub_confirmation=1" target="blank"><img src="images/subzkribe.gif" alt="Subzkribe gif" width="200px"></a>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    <div id="mc_embed_shell">
      		<link href="//cdn-images.mailchimp.com/embedcode/classic-061523.css" rel="stylesheet" type="text/css">
				<div id="mc_embed_signup">
  			
    			<form action="https://neocities.us21.list-manage.com/subscribe/post?u=febff1303a62768155780747d&amp;id=28f23929e4&amp;f_id=004adce6f0" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank">
        		<div id="mc_embed_signup_scroll">
        			<h2>NewZletter</h2>   
            	<div class="mc-field-group">
            		<label for="mce-EMAIL">
            			<h3>Type your email :</h3>		
            		</label>
            			<input type="email" name="EMAIL" class="required email" id="mce-EMAIL" required="" value="">
            	</div>
        		<div id="mce-responses" class="clear foot">
            		<div class="response" id="mce-error-response" style="display: none;"></div>
            		<div class="response" id="mce-success-response" style="display: none;"></div>
        		</div>
    			<div aria-hidden="true" style="position: absolute; left: -5000px;">

        	<!-- do not remove this or risk form bot signups -->

        			<input type="text" name="b_febff1303a62768155780747d_28f23929e4" tabindex="-1" value="">
    			</div>
    		
        	<div class="optionalParent">
            	<div class="clear foot">
                	<input type="submit" name="subscribe" id="mc-embedded-subscribe" class="button" value="SubZkribe">
            	</div>
        	</div>
    	</div>
	</form>
</div>
</div>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <a href='https://bedr00mz.neocities.org/Donations' onmouseover="document.getElementById('SFX7').play()" class='Donate' title="you're s0 gener0us!">Donate</a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;


      
</div>
</center>
</div>
</body>
<!-- Code by Viktor Tibay - © All rights reserved -->


















# 💫 HELLO ITS ME HAFIZH SALAM KENAL💫:


---

# 💻 Tech Stack:
<p align="center">
  <img src="https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" alt="JavaScript" />
  <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/adobe-%23FF0000.svg?style=for-the-badge&logo=adobe&logoColor=white" alt="Adobe" />
  <img src="https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" />
  <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React" />
  <img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white" alt="MariaDB" />
  <img src="https://img.shields.io/badge/sql-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/expo-1C1E24?style=for-the-badge&logo=expo&logoColor=#D04A37" alt="Expo" />
  <img src="https://img.shields.io/badge/CodeIgniter-%23EF4223.svg?style=for-the-badge&logo=codeIgniter&logoColor=white" alt="CodeIgniter" />
  <img src="https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel" />
  <img src="https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure" />
  <img src="https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase" alt="Firebase" />
  <img src="https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="React Native" />
</p>

# 📊 GitHub Stats:
<div id="header" align="center">
  <div id="header">
    <a href="https://github-readme-streak-stats.herokuapp.com/?user=HFZH-SC&theme=dark&hide_border=false">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=HFZH-SC&theme=dark&hide_border=false" alt="GitHub Streak" />
    </a>
    <br/>
    <a href="https://github-readme-stats.vercel.app/api/top-langs/?username=HFZH-SC&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=HFZH-SC&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact" alt="Top Languages" />
    </a>
  </div>
</div>

