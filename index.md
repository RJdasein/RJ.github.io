<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>RJ Dasein｜芮洁 · 岱生</title>

<style>
body{
    margin:0;
    background:#F8F6F2;
    color:#222;
    font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",sans-serif;
    line-height:1.8;
}

.container{
    max-width:760px;
    margin:auto;
    padding:70px 30px;
}

h1{
    font-size:54px;
    margin-bottom:10px;
    font-weight:300;
}

h2{
    margin-top:70px;
    font-weight:500;
}

.subtitle{
    color:#666;
    margin-bottom:50px;
}

.lang{
    position:fixed;
    top:20px;
    right:25px;
}

button{
    border:none;
    background:none;
    font-size:15px;
    cursor:pointer;
    color:#666;
}

button:hover{
    color:black;
}

.hidden{
    display:none;
}

footer{
    margin-top:80px;
    color:#888;
    font-size:14px;
    text-align:center;
}
a{
    color:#222;
    text-decoration:none;
}
</style>
</head>

<body>

<div class="lang">
<button onclick="showEN()">EN</button> |
<button onclick="showCN()">中文</button>
</div>

<div class="container">

<div id="en">

<h1>RJ Dasein</h1>

<p class="subtitle">
Ruijie (Eagle) Wu<br>
Existential Psychotherapist<br>
Dance Movement Therapist
</p>

<p><strong>Living. Moving. Becoming.</strong></p>

<h2>About</h2>

<p>
Hi, I'm Ruijie (Eagle) Wu.
</p>

<p>
I'm an existential psychotherapist and dance movement therapist.
This website is my digital garden—a place where I share my work,
thoughts, movement, and ongoing journey.
</p>

<h2>Now 🌱</h2>

<p>
July 2026<br>
📍 Hanoi, Vietnam
</p>

<ul>
<li>Figure skating and pole dance</li>
<li>Learning Germany</li>
<li>Preparing an online workshop</li>
<li>Building this website</li>
</ul>

<h2>Contact</h2>

<p>
📧 hello@rjdasein.com
</p>

<p>
Xiaohongshu · Spotify · Xiaoyuzhou · LinkedIn
</p>

</div>

<div id="cn" class="hidden">

<h1>RJ Dasein｜芮洁 · 岱生</h1>

<p class="subtitle">
伍芮洁<br>
存在主义心理治疗师<br>
舞动治疗师
</p>

<p><strong>生活 · 移动 · 成为</strong></p>

<h2>关于我</h2>

<p>
你好，我是伍芮洁。
</p>

<p>
这里不是传统意义上的个人官网，
而是一座属于我的数字花园。
我会在这里分享工作、思考、研究、旅行，以及仍在发生的生活。
</p>

<h2>近况 🌱</h2>

<p>
2026 年 7 月<br>
📍 越南 · 河内
</p>

<ul>
<li>练习滑冰与钢管舞</li>
<li>学习德语</li>
<li>准备线上舞动工作坊</li>
<li>建设 rjdasein.com</li>
</ul>

<h2>联系我</h2>

<p>
📧 hello@rjdasein.com
</p>

<p>
小红书｜Spotify｜小宇宙｜LinkedIn
</p>

</div>

<footer>

This garden is always growing. 🌱

</footer>

</div>

<script>

function showCN(){
document.getElementById("cn").classList.remove("hidden");
document.getElementById("en").classList.add("hidden");
}

function showEN(){
document.getElementById("en").classList.remove("hidden");
document.getElementById("cn").classList.add("hidden");
}

</script>

</body>
</html>
