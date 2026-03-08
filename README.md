# Zainuu
For my begum🤍
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Secret Message</title>

<style>
body{
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg,#ff9a9e,#fad0c4);
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
}

.container{
    background:white;
    padding:30px;
    border-radius:15px;
    box-shadow:0 10px 25px rgba(0,0,0,0.2);
    max-width:600px;
}

.envelope{
    font-size:80px;
    cursor:pointer;
}

.hidden{
    display:none;
}

input{
    padding:10px;
    margin:10px;
    border-radius:8px;
    border:1px solid #ccc;
}

button{
    padding:10px 20px;
    border:none;
    border-radius:8px;
    background:#ff6b81;
    color:white;
    cursor:pointer;
}

.message{
    white-space:pre-line;
    text-align:left;
}
</style>
</head>

<body>

<div class="container">

<div id="envelopePage">
<div class="envelope" onclick="openEnvelope()">✉️</div>
<p>Click the envelope to open</p>
</div>

<div id="pass1" class="hidden">
<h3>Enter Password</h3>
<input type="password" id="p1">
<br>
<button onclick="checkPass1()">Submit</button>
</div>

<div id="pass2" class="hidden">
<h3>Enter Second Password</h3>
<input type="password" id="p2">
<br>
<button onclick="checkPass2()">Submit</button>
</div>

<div id="messagePage" class="hidden">
<h2>Secret Message ❤️</h2>

<div class="message">

Ma jane se pehle ye kahna chahta k  

I promise that k nikah k bad tm ne jasa Socha hua hm wase h life guzre g  
Blkay us se b kahin gunah zayda axhe  

Ma gurente deta k hmre life same wase h ho g jasa tm chahti jasa hm dono ne mil kr socha hua ❤️  

Jasa tm ne muje call pr bataya thaaaaaaa bilkul wasaaa hiiiii  

Jasa tm chahti ek ghr ho us ma srf ma or tm  
Hm mil kr cooking krein  

Ma talwat kru or mere shoulder pr tmra sr  

Bilkul asa he ho ga begum  
I promise 🤍  

Ma talwat pr ke sunao ga tm mere shoulder pr sr rkna 🤍  

Dherrr sare batein krein ge hr topic k relatedd  

Kabheeee ma bolo gaaa tm sunaaa  
Kabhe tm bolna ma suno gaaaa  

Sameeeee dressing krein g jaha b jain ge  

Tme khd apne hatho se kana kilaua kro ga  
Tme khd apne hato se mehndi lagaya kro gaa  

Apne hatho se tmre hatho ma churian pehnaya kru ga ❤️  

Khd tme rings pehnaya kro ga apne se 🤍  

Tmre balo pr brush b ma h kia kru ga 🫠❤️  

Hr chzzz hm mil kr krein h  

Bs ma itna kahna chahta jasa tm chahti hm waseeee h life gusre g mere ladlyyyy begummmmm 🤍  

Tmra hathh kabhii ni chorne wala  

Begummmm ma tm se behadd pyar krta  
Khd se b zaydaaaaaaaaaaaaaaa  

Maaaa srfff tmraaaaa huuuuuuu  

SRF TMAAAHARAAAA  

I will really missss uhh alotttt Begummmmmm 🫠❤️  

And I will alwaysssss love uhhhh the way uh want 🫠🤍  

Loveeeee uh alottt begummm 🤍

</div>
</div>

</div>

<script>

function openEnvelope(){
document.getElementById("envelopePage").classList.add("hidden");
document.getElementById("pass1").classList.remove("hidden");
}

function checkPass1(){
let p1=document.getElementById("p1").value;
if(p1==="Zanoor"){
document.getElementById("pass1").classList.add("hidden");
document.getElementById("pass2").classList.remove("hidden");
}else{
alert("Wrong Password");
}
}

function checkPass2(){
let p2=document.getElementById("p2").value;
if(p2==="10-8-2005"){
document.getElementById("pass2").classList.add("hidden");
document.getElementById("messagePage").classList.remove("hidden");
}else{
alert("Wrong Password");
}
}

</script>

</body>
</html>
