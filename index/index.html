<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Win a Free Drink!</title>
<style>
body{margin:0;background:#121212;color:#fff;font-family:Arial,sans-serif;display:flex;justify-content:center;align-items:center;min-height:100vh}
.card{background:#1f1f1f;padding:28px;border-radius:18px;max-width:420px;width:90%;box-shadow:0 0 25px rgba(255,215,0,.2);text-align:center}
h1{color:#FFD700;margin-top:0}
.question{font-size:1.4em;font-weight:bold;margin:20px 0}
button{display:block;width:100%;margin:10px 0;padding:15px;border:none;border-radius:10px;background:#333;color:#fff;font-size:1em;cursor:pointer}
button:hover{background:#FFD700;color:#000}
.timer{font-size:48px;color:#FFD700;margin:15px 0}
.correct{color:#7CFC98;font-size:1.8em}
.wrong{color:#ff6b6b;font-size:1.6em}
</style>
</head>
<body>
<div class="card" id="app"></div>
<script>
const questions=[
{question:"In which place did Amelia work the longest?",answers:["x","y","z"],correct:0},
{question:"What is the name of Amelia's university studies?",answers:["abc","efg","hij"],correct:1},
{question:"How many tattoos does Amelia have?",answers:["6","7","67"],correct:2}
];
const q=questions[Math.floor(Math.random()*questions.length)];
const app=document.getElementById("app");

function renderQuestion(){
 app.innerHTML="<h1>🍸 Win a Free Drink!</h1><p>Answer one random question correctly to receive your free drink.</p><div class='question'>"+q.question+"</div>";
 q.answers.forEach((a,i)=>{
   const b=document.createElement("button");
   b.textContent=String.fromCharCode(65+i)+". "+a;
   b.onclick=()=>check(i);
   app.appendChild(b);
 });
}
function check(i){
 if(i===q.correct){
   let s=60;
   app.innerHTML="<div class='correct'>🎉 Correct!</div><p>Show this screen to the bartender.</p><div id='t' class='timer'>60</div><p>Reward expires in 60 seconds.</p>";
   const t=document.getElementById("t");
   const iv=setInterval(()=>{
      s--;
      t.textContent=s;
      if(s<=0){
        clearInterval(iv);
        app.innerHTML="<h1>⏰ Time expired</h1><p>Please scan the QR code again.</p>";
      }
   },1000);
 }else{
   app.innerHTML="<div class='wrong'>❌ Wrong answer</div><p>Better luck next time!</p>";
 }
}
renderQuestion();
</script>
</body>
</html>
