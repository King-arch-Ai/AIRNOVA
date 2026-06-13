<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Maduka University Students Note Portal</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:#0f172a;
    color:white;
}

header{
    min-height:100vh;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    text-align:center;
    padding:20px;
    background:
    radial-gradient(circle at top left,#22c55e33,transparent 30%),
    radial-gradient(circle at bottom right,#3b82f633,transparent 30%);
}

header h1{
    font-size:4rem;
    margin-bottom:20px;
    background:linear-gradient(90deg,#22c55e,#38bdf8);
    -webkit-background-clip:text;
    color:transparent;
}

header p{
    max-width:800px;
    color:#cbd5e1;
    font-size:1.1rem;
    line-height:1.8;
}

.btn{
    margin-top:30px;
    padding:15px 35px;
    border:none;
    border-radius:50px;
    background:#22c55e;
    color:white;
    font-size:1rem;
    cursor:pointer;
    transition:.3s;
}

.btn:hover{
    transform:translateY(-5px);
    box-shadow:0 0 25px #22c55e;
}

section{
    padding:80px 10%;
}

.section-title{
    text-align:center;
    margin-bottom:50px;
    font-size:2.5rem;
}

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:#1e293b;
    padding:25px;
    border-radius:20px;
    transition:.4s;
}

.card:hover{
    transform:translateY(-10px);
    box-shadow:0 0 30px rgba(34,197,94,.25);
}

.card h3{
    margin-bottom:15px;
    color:#22c55e;
}

.tech{
    text-align:center;
    padding:15px;
    background:#1e293b;
    border-radius:15px;
}

.screenshot{
    width:100%;
    height:250px;
    border-radius:20px;
    background:#1e293b;
    display:flex;
    justify-content:center;
    align-items:center;
    color:#94a3b8;
}

.code-box{
    background:#020617;
    padding:20px;
    border-radius:15px;
    overflow:auto;
    margin-top:20px;
    color:#22c55e;
}

.timeline li{
    margin-bottom:15px;
}

.stats{
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    gap:40px;
}

.stat{
    text-align:center;
}

.stat h2{
    font-size:3rem;
    color:#22c55e;
}

footer{
    padding:40px;
    text-align:center;
    background:#020617;
    color:#94a3b8;
}
</style>
</head>

<body>

<header>
    <h1>📚 Maduka University Students Note Portal</h1>

    <p>
        A modern web-based platform designed to help students of
        Maduka University access, share, and manage academic notes
        efficiently. The portal promotes collaborative learning
        through a centralized repository for lecture notes,
        assignments and study materials.
    </p>

    <button class="btn" onclick="scrollToFeatures()">
        Explore Features
    </button>
</header>

<section id="features">
    <h2 class="section-title">🚀 Features</h2>

    <div class="grid">

        <div class="card">
            <h3>📖 Browse Notes</h3>
            <p>Download lecture notes instantly.</p>
        </div>

        <div class="card">
            <h3>📤 Upload Materials</h3>
            <p>Share resources with fellow students.</p>
        </div>

        <div class="card">
            <h3>🔍 Smart Search</h3>
            <p>Find notes by title or course code.</p>
        </div>

        <div class="card">
            <h3>👨‍🎓 Student Friendly</h3>
            <p>Simple and intuitive interface.</p>
        </div>

        <div class="card">
            <h3>📱 Responsive</h3>
            <p>Works on all devices.</p>
        </div>

        <div class="card">
            <h3>🔐 Secure Login</h3>
            <p>Protected student accounts.</p>
        </div>

        <div class="card">
            <h3>📂 Organized Notes</h3>
            <p>Faculty and department categories.</p>
        </div>

    </div>
</section>

<section>
    <h2 class="section-title">🛠 Technologies Used</h2>

    <div class="grid">
        <div class="tech">HTML5</div>
        <div class="tech">CSS3</div>
        <div class="tech">JavaScript ES6</div>
        <div class="tech">Firebase</div>
        <div class="tech">Firestore</div>
        <div class="tech">Authentication</div>
        <div class="tech">Cloud Storage</div>
    </div>
</section>

<section>
    <h2 class="section-title">📸 Screenshots</h2>

    <div class="grid">
        <div class="screenshot">Homepage Screenshot</div>
        <div class="screenshot">Dashboard Screenshot</div>
    </div>
</section>

<section>
    <h2 class="section-title">📂 Project Structure</h2>

    <div class="code-box">
maduka-notes-portal/<br>
├── index.html<br>
├── login.html<br>
├── dashboard.html<br>
├── css/<br>
│ └── style.css<br>
├── js/<br>
│ └── app.js<br>
├── images/<br>
└── README.md
    </div>
</section>

<section>
    <h2 class="section-title">⚙ Installation</h2>

    <div class="code-box">
git clone https://github.com/yourusername/maduka-notes-portal.git
<br><br>
cd maduka-notes-portal
<br><br>
npx serve
    </div>
</section>

<section>
    <h2 class="section-title">🎯 Purpose</h2>

    <p style="text-align:center;max-width:900px;margin:auto;color:#cbd5e1;">
        The Maduka University Students Note Portal was developed
        to solve the challenge of limited access to academic
        resources by providing students with a simple and efficient
        platform for sharing and obtaining study materials.
    </p>
</section>

<section>
    <h2 class="section-title">🌟 Future Improvements</h2>

    <ul class="timeline">
        <li>🤖 AI-powered note recommendations</li>
        <li>🌙 Dark mode support</li>
        <li>⭐ Note ratings and reviews</li>
        <li>👨‍🏫 Lecturer uploads</li>
        <li>💬 Department discussion forums</li>
        <li>📄 PDF preview functionality</li>
    </ul>
</section>

<section>
    <h2 class="section-title">📊 Portal Statistics</h2>

    <div class="stats">

        <div class="stat">
            <h2 id="notes">0</h2>
            <p>Notes Uploaded</p>
        </div>

        <div class="stat">
            <h2 id="students">0</h2>
            <p>Students</p>
        </div>

        <div class="stat">
            <h2 id="downloads">0</h2>
            <p>Downloads</p>
        </div>

    </div>
</section>

<section>
    <h2 class="section-title">🤝 Contributing</h2>

    <ol>
        <li>Fork the repository</li>
        <li>Create a feature branch</li>
        <li>Commit your changes</li>
        <li>Open a Pull Request</li>
    </ol>
</section>

<section>
    <h2 class="section-title">👨‍💻 Developer</h2>

    <p style="text-align:center;font-size:1.3rem;">
        Developed by <strong>HACKZZZ</strong>
    </p>
</section>

<footer>
    © 2026 Maduka University Students Note Portal <br>
    Built for students to learn, collaborate and succeed.
</footer>

<script>

function scrollToFeatures(){
    document.getElementById("features")
    .scrollIntoView({behavior:"smooth"});
}

function animate(id,target){

    let count=0;

    let speed=Math.ceil(target/100);

    let interval=setInterval(()=>{

        count+=speed;

        if(count>=target){
            count=target;
            clearInterval(interval);
        }

        document.getElementById(id).innerText=count;

    },20);

}

animate("notes",500);
animate("students",1500);
animate("downloads",12000);

</script>

</body>
</html>
