<h1 align="center">Hi 👋, I'm Yashwant Singh</h1>
<h3 align="center">BTech CSE Student</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=yashrajpurohit7&label=Profile%20views&color=0e75b6&style=flat" alt="views" />
</p>

<p align="center">
  <a href="https://github.com/yashrajpurohit7">
    <img src="https://readme-typing-svg.herokuapp.com?lines=Aspiring+Software+Engineer;Open+Source+Contributor;Competitive+Programmer&center=true&width=500&height=45">
  </a>
</p>
## 🛠️ Skills
<p>
  <img src="https://skillicons.dev/icons?i=html,css,js,react,nodejs,python,git,github,vscode,mysql" />
</p>

---

## 📊 GitHub Stats
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=yashrajpurohit7&show_icons=true&theme=tokyonight" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=yashrajpurohit7&theme=tokyonight" />
</p>
<p align="center">
  <!-- Top Languages Card -->
<a href="https://github.com/yashrajpurohit7">
    <img height="200" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yashrajpurohit7&layout=compact&langs_count=10&theme=radical" />
  </a>
</p>
 
BADGES
<div><a href="https://cloud.layer5.io/user/3880476c-c33d-4463-9436-8988d61bcdfb?tab=badges&badge=first-design" alt="First Design" ><img width="175px" height="252px" src="https://badges.layer5.io/assets/badges/first-design/first-design.png" alt="First Design" /></a></div>

## 🌐 Connect with Me
- 💼 LinkedIn: https://www.linkedin.com/in/yashwant-singh-40856b307
- 🧑‍💻 twitter(x): https://x.com/yash_purohit7
- 📧 Email: yashpurohit866@gmail.com
  <!DOCTYPE html>
<html>
<head>
  <title>Support Me</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      margin: 0;
      background: radial-gradient(circle at top, #0f2027, #05070a);
      overflow: hidden;
      font-family: Arial, sans-serif;
      color: white;
      position: relative;
    }

    /* Button */
    .btn {
      position: absolute;
      top: 45%;
      left: 50%;
      transform: translateX(-50%);
      padding: 16px 32px;
      font-size: 18px;
      border-radius: 14px;
      border: none;
      background: linear-gradient(135deg, #ff512f, #f09819);
      font-weight: bold;
      cursor: pointer;
      z-index: 10;
      box-shadow: 0 10px 30px rgba(0,0,0,0.5);
    }

    /* Character */
    .ironman {
      position: absolute;
      bottom: 60px;
      left: -300px;
      width: 180px;
      transition: 1.6s cubic-bezier(.2,.8,.2,1);
      z-index: 2;
    }

    .ironman.show {
      left: 40px;
    }

    /* Energy ball */
    .repulsor {
      position: absolute;
      width: 18px;
      height: 18px;
      background: radial-gradient(circle, #00f6ff, #005eff);
      border-radius: 50%;
      left: 170px;
      bottom: 120px;
      opacity: 0;
      box-shadow: 0 0 20px #00f6ff;
      z-index: 3;
    }

    .repulsor.fire {
      opacity: 1;
      animation: shoot 0.9s linear forwards;
    }

    @keyframes shoot {
      from { left: 170px; }
      to { left: 50%; }
    }

    /* Flash */
    .flash {
      position: fixed;
      inset: 0;
      background: white;
      opacity: 0;
      pointer-events: none;
      z-index: 5;
    }

    .flash.boom {
      animation: flash 0.3s ease;
    }

    @keyframes flash {
      0% {opacity: 0;}
      50% {opacity: 0.7;}
      100% {opacity: 0;}
    }

    /* QR Card */
    .card {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%) scale(0.7);
      opacity: 0;
      background: rgba(255,255,255,0.08);
      backdrop-filter: blur(16px);
      padding: 30px;
      border-radius: 22px;
      text-align: center;
      box-shadow: 0 0 60px rgba(0,0,0,0.6);
      transition: 0.6s ease;
      z-index: 6;
    }

    .card.show {
      transform: translate(-50%, -50%) scale(1);
      opacity: 1;
    }

    .card img {
      width: 230px;
      border-radius: 16px;
      margin-top: 12px;
      box-shadow: 0 10px 40px rgba(0,0,0,0.5);
    }
  </style>
</head>
<body>

<button class="btn" id="btn">☕ Support My Work</button>

<img class="ironman" id="ironman"
     src="https://i.imgur.com/O7Mst7Y.png" alt="character">

<div class="repulsor" id="repulsor"></div>
<div class="flash" id="flash"></div>

<div class="card" id="card">
  <h2>⚡ QR Unlocked</h2>
  <p>Scan to support my work</p>
  <img src="https://api.qrserver.com/v1/create-qr-code/?size=300x300&data=DummyUPI">
</div>

<script>
  const btn = document.getElementById("btn");
  const iron = document.getElementById("ironman");
  const rep = document.getElementById("repulsor");
  const flash = document.getElementById("flash");
  const card = document.getElementById("card");

  btn.addEventListener("click", () => {
    btn.style.display = "none";

    // Step 1: character enters
    iron.classList.add("show");

    // Step 2: shoot
    setTimeout(() => {
      rep.classList.add("fire");
    }, 1500);

    // Step 3: impact + QR reveal
    setTimeout(() => {
      flash.classList.add("boom");
      card.classList.add("show");
    }, 2400);
  });
</script>

</body>
</html>


---

## 🔥 Leetcode: https://leetcode.com/u/yashwantsingh7
