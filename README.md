<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dummy Website</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:#f4f4f4;
    color:#333;
}

header{
    background:#1f2937;
    color:white;
    padding:20px 60px;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:20px;
    transition:.3s;
}

nav a:hover{
    color:#00d4ff;
}

.hero{
    height:90vh;
    display:flex;
    justify-content:center;
    align-items:center;
    flex-direction:column;
    text-align:center;
    background:linear-gradient(135deg,#4f46e5,#06b6d4);
    color:white;
}

.hero h1{
    font-size:55px;
    margin-bottom:20px;
}

.hero p{
    font-size:20px;
    margin-bottom:30px;
}

.hero button{
    padding:15px 35px;
    border:none;
    border-radius:30px;
    background:white;
    color:#4f46e5;
    font-size:18px;
    cursor:pointer;
    transition:.3s;
}

.hero button:hover{
    transform:scale(1.05);
}

.features{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:30px;
    padding:70px;
}

.card{
    background:white;
    padding:30px;
    border-radius:15px;
    box-shadow:0 5px 15px rgba(0,0,0,.15);
    transition:.3s;
}

.card:hover{
    transform:translateY(-10px);
}

.card h3{
    margin-bottom:15px;
}

footer{
    background:#1f2937;
    color:white;
    text-align:center;
    padding:25px;
}
</style>

</head>
<body>

<header>
<h2>DummySite</h2>

<nav>
<a href="#">Home</a>
<a href="#">About</a>
<a href="#">Services</a>
<a href="#">Contact</a>
</nav>

</header>

<section class="hero">

<h1>Welcome to My Test Website</h1>

<p>This website is hosted using GitHub Pages.</p>

<button onclick="showMessage()">Click Me</button>

</section>

<section class="features">

<div class="card">
<h3>Fast</h3>
<p>Simple website for testing GitHub Pages deployment.</p>
</div>

<div class="card">
<h3>Responsive</h3>
<p>Looks good on desktop, tablet, and mobile devices.</p>
</div>

<div class="card">
<h3>Modern</h3>
<p>Built using only HTML, CSS, and JavaScript.</p>
</div>

</section>

<footer>

<p>© 2026 Dummy Website | Hosted on GitHub Pages</p>

</footer>

<script>
function showMessage(){
    alert("Congratulations! Your GitHub Pages website is working!");
}
</script>

</body>
</html>
