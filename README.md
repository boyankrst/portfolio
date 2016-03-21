# portfoliobody {
	
	background-image: url("../img/backgr.jpg");
	background-repeat:repeat-x;
	background-size:100px;	
	
	
} 
	
.main {
width:1160px;
height:550px;
border:6px solid  #999999;
border-radius:35px;  
 margin-left:auto;
  margin-right:auto;
  margin-top:45px;
  background-image: url("../img/back1.png");
	background-repeat:repeat-x;
	background-size:18px;
}



.logo {
	padding-top:10px;
	  width: 150px;
	  height: 140px; 
   -moz-border-radius: 80px; 
   -webkit-border-radius: 80px; 
   border-radius: 80px;
	position:relative;
	left:496px;
	top:-420px;
	
}
.knob {
	z-index: 0;
	position:relative;
	left:365px;
	top:154px;
	-webkit-animation: turn 3s linear infinite;
	animation: turn 3s linear infinite;
	-moz-animation: turn 3s linear infinite;
	-ms-animation: turn 3s linear infinite;
}
@-moz-keyframes turn { 100% { -moz-transform: rotate(360deg); } }
@-webkit-keyframes turn { 100% { -webkit-transform: rotate(360deg); } }
@keyframes turn { 100% { -webkit-transform: rotate(360deg); transform:rotate(360deg); } }

@-webkit-keyframes turn {
	100% {
		-webkit-transform: rotate(360deg);
		-moz-transform: rotate(360deg);
		-ms-transform: rotate(360deg);
		transform: rotate(360deg);
	}
}

.logotext {
position:relative;
left:132px;
top:60px;
font-size:36px;
font-family:"Papyrus";
color:black;
}
 


.content {
position:relative;
top:150px;
right:760px;
 margin-left:auto;
  margin-right:auto;
  
}

.content1 {
position:relative;
top:-180px;
left:730px;
 margin-left:auto;
  margin-right:auto;

}

#menu {
position:relative;
left:30px;
}
#menu1 {
position:relative;
left:-30px;
}

#menu2 {
position:relative;
left:30px;
}

#menu3 {
position:relative;
left:-30px;
}

.a-btn1{
    padding-left:145px;
    padding-right:180px;
	text-decoration: none;
    height:75px;
	width:10px;
    display:inline-block;
    position:relative;
    border:1px solid #5d81ab;

    -webkit-box-shadow:0px 1px 1px rgba(255,255,255,0.8) inset, 1px 1px 3px rgba(0,0,0,0.2);
    -moz-box-shadow:0px 1px 1px rgba(255,255,255,0.8) inset, 1px 1px 3px rgba(0,0,0,0.2);
    box-shadow:0px 1px 1px rgba(255,255,255,0.8) inset, 1px 1px 3px rgba(0,0,0,0.2);

   -webkit-border-radius:15px;
    -moz-border-radius:20px;
     border-radius:15px;
    float:left;
    clear:both;
    margin:16px 0px;
    overflow:hidden;
    -webkit-transition:all 0.3s ease-out;
    -moz-transition:all 0.3s ease-out;
    -o-transition:all 0.3s ease-out;
    transition:all 0.3s ease-out;
	
}

.a-btn-text1{
    padding-top:15px;
    padding-left:25px;
    display:block;
    font-size:25px;
	
    white-space:nowrap;
    text-shadow:0px 1px 1px rgba(255,255,255,0.3);
    color:#007FFF;
    -webkit-transition:all 0.2s linear;
    -moz-transition:all 0.2s linear;
    -o-transition:all 0.2s linear;
    transition:all 0.2s linear;
	
}
.a-btn-slide-text1{
    position:absolute; 
    height:100%;
    top:-1px;
    left:25px;
    width:1px;
    background-image: url("../img/kabel1.jpg");
	 background-size:110px;
	 background-position:center;
    color:blue;
    font-size:18px;
    white-space:nowrap;
    text-transform:uppercase;
    text-align:right;
    text-indent:10px;
    overflow:hidden;
    line-height:38px;
    -webkit-box-shadow:-1px 0px 1px rgba(255,255,255,0.4), 1px 1px 2px rgba(0,0,0,0.2) inset;
    -moz-box-shadow:-1px 0px 1px rgba(255,255,255,0.4), 1px 1px 2px rgba(0,0,0,0.2) inset;
    box-shadow:-1px 0px 1px rgba(255,255,255,0.4), 1px 1px 2px rgba(0,0,0,0.2) inset;
    -webkit-transition:width 0.3s linear;
    -moz-transition:width 0.3s linear;
    -ms-transition:width 0.3s linear;
    -o-transition:width 0.3s ease-out;
    transition:width 0.3s ease-out;
}




.a-btn-icon-right1{
    position:absolute;
    left:-80px;
    top:1px;
    height:100%;
    width:102px;
    border-left:1px solid #5d81ab;
    -webkit-box-shadow:1px 0px 1px rgba(255,255,255,0.4) inset;
    -moz-box-shadow:1px 0px 1px rgba(255,255,255,0.4) inset;
    box-shadow:1px 0px 1px rgba(255,255,255,0.4) inset;
}
.a-btn-icon-right1 span{
    width:48px;
    height:58px;
    position:absolute;
    left:85%;
    top:20%;
    margin:-18px 0px 0px -30px;
    background: url(../img/kabel-side.jpg);
	background-size:150px;
    -webkit-transition:all 0.3s linear;
    -moz-transition:all 0.3s linear;
    -o-transition:all 0.3s linear;
    transition:all 0.3s linear;
}

.a-btn1:hover{
    padding-right:180px;
        -webkit-box-shadow:0px 1px 1px rgba(255,255,255,0.2) inset, 1px 1px 3px rgba(0,0,0,0.2), 0px 0px 0px 4px rgba(188,188,188,0.5);
    -moz-box-shadow:0px 1px 1px rgba(255,255,255,0.2) inset, 1px 1px 3px rgba(0,0,0,0.2), 0px 0px 0px 4px rgba(188,188,188,0.5);
    box-shadow:0px 1px 1px rgba(255,255,255,0.2) inset, 1px 1px 3px rgba(0,0,0,0.2), 0px 0px 0px 4px rgba(188,188,188,0.5);
   

}
.a-btn1:hover .a-btn-text1{
    text-shadow:0px 1px 1px #5d81ab;
    color:black;
	
}
.a-btn1:hover .a-btn-slide-text1{
    width:100px;
		
}
.a-btn1:hover .a-btn-icon-right1 span{
    opacity:1;
}
.a-btn1:active{
    position:relative;
    top:8px;
    background:#5d81ab;
    -webkit-box-shadow:1px 1px 2px rgba(0,0,0,0.4) inset;
    -moz-box-shadow:1px 1px 2px rgba(0,0,0,0.4) inset;
    box-shadow:1px 1px 2px rgba(0,0,0,0.4) inset;
    border-color:#80a9da;

}
