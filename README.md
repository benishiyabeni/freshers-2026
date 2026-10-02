<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>For Vasavi ❤️</title>

<style>
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Georgia, 'Times New Roman', serif;
    background: #fff8f8;
    color: #351b1b;
    overflow-x: hidden;
}

.screen {
    min-height: 100vh;
    display: none;
    align-items: center;
    justify-content: center;
    padding: 30px 20px;
    text-align: center;
    animation: fadeIn 0.8s ease;
}

.screen.active {
    display: flex;
}

.container {
    width: 100%;
    max-width: 850px;
    margin: auto;
}

h1 {
    font-size: clamp(38px, 8vw, 72px);
    margin-bottom: 20px;
    color: #8b1e2d;
}

h2 {
    font-size: clamp(28px, 6vw, 48px);
    margin-bottom: 25px;
    color: #8b1e2d;
}

p {
    font-size: 18px;
    line-height: 1.8;
}

.subtitle {
    font-size: 20px;
    line-height: 1.8;
    margin: 20px auto 35px;
    max-width: 650px;
}

button {
    border: none;
    background: #8b1e2d;
    color: white;
    padding: 15px 30px;
    border-radius: 30px;
    font-size: 16px;
    cursor: pointer;
    font-family: inherit;
    transition: 0.3s;
    margin-top: 25px;
}

button:hover {
    background: #64131f;
    transform: translateY(-3px);
}

.small {
    font-size: 15px;
    margin-top: 15px;
    opacity: 0.7;
}

/* OPENING */

.opening {
    background: linear-gradient(135deg, #fff5f5, #ffe7e9);
}

.heart {
    font-size: 60px;
    margin-bottom: 15px;
    animation: heartbeat 1.5s infinite;
}

/* DARES */

.dare-number {
    color: #b23a48;
    letter-spacing: 3px;
    font-size: 15px;
    margin-bottom: 15px;
    font-weight: bold;
}

.dare-box {
    background: white;
    padding: 45px 30px;
    border-radius: 25px;
    box-shadow: 0 15px 40px rgba(90, 30, 30, 0.12);
    max-width: 650px;
    margin: auto;
}

.dare-text {
    font-size: 26px;
    line-height: 1.6;
}

.progress {
    margin-top: 30px;
    font-size: 14px;
    color: #8b1e2d;
}

/* PASSCODE */

.passcode-box {
    background: white;
    padding: 45px 30px;
    border-radius: 25px;
    box-shadow: 0 15px 40px rgba(90, 30, 30, 0.12);
    max-width: 550px;
    margin: auto;
}

input {
    width: 100%;
    max-width: 300px;
    padding: 15px;
    border: 1px solid #d8a5aa;
    border-radius: 10px;
    text-align: center;
    font-size: 20px;
    letter-spacing: 4px;
    margin-top: 20px;
    outline: none;
}

input:focus {
    border-color: #8b1e2d;
}

#error {
    color: #b23a48;
    margin-top: 15px;
    display: none;
}

/* ROSES */

.rose-section {
    background: #fff4f5;
}

.rose-photo {
    width: 100%;
    max-width: 600px;
    height: 420px;
    object-fit: cover;
    border-radius: 25px;
    margin: 20px auto;
    display: block;
    box-shadow: 0 20px 45px rgba(70, 20, 30, 0.2);
}

.photo-note {
    font-size: 14px;
    color: #777;
    margin-top: 10px;
}

/* PROFILE */

.profile {
    background: #fffafa;
}

.profile-card {
    background: white;
    padding: 40px;
    border-radius: 25px;
    box-shadow: 0 15px 45px rgba(70, 20, 30, 0.1);
    text-align: left;
}

.profile-name {
    text-align: center;
    color: #8b1e2d;
    font-size: 38px;
    margin-bottom: 25px;
}

.profile-card p {
    font-size: 18px;
    line-height: 1.9;
}

/* MEMORY */

.memory {
    background: #fff1f2;
}

.memory-photo {
    width: 100%;
    max-width: 650px;
    height: 430px;
    object-fit: cover;
    border-radius: 20px;
    box-shadow: 0 15px 40px rgba(70, 20, 30, 0.18);
    margin: 20px auto;
    display: block;
}

.caption {
    font-style: italic;
    font-size: 20px;
}

/* SENIORS */

.seniors {
    background: linear-gradient(135deg, #fff8f8, #ffe9eb);
}

.senior-message {
    max-width: 700px;
    margin: auto;
    font-size: 20px;
    line-height: 2;
}

.quote {
    margin-top: 35px;
    font-style: italic;
    color: #8b1e2d;
}

/* LETTER */

.letter {
    background: #fff5f1;
}

.letter-box {
    background: #fffdf8;
    padding: 50px 35px;
    max-width: 650px;
    margin: auto;
    border-radius: 8px;
    box-shadow: 0 15px 40px rgba(80, 40, 20, 0.15);
    border: 1px solid #ead8ca;
}

.letter-icon {
    font-size: 50px;
    margin-bottom: 20px;
}

.footer {
    margin-top: 35px;
    font-size: 14px;
    opacity: 0.6;
}

/* ANIMATIONS */

@keyframes fadeIn {
    from {
        opacity: 0;
        transform: translateY(15px);
    }

    to {
        opacity: 1;
        transform: translateY(0);
    }
}

@keyframes heartbeat {
    0%, 100% {
        transform: scale(1);
    }

    50% {
        transform: scale(1.15);
    }
}

/* MOBILE */

@media (max-width: 600px) {

    .screen {
        padding: 25px 15px;
    }

    .dare-box,
    .passcode-box,
    .profile-card,
    .letter-box {
        padding: 30px 20px;
    }

    .dare-text {
        font-size: 21px;
    }

    .rose-photo,
    .memory-photo {
        height: 300px;
    }

    .profile-card p {
        font-size: 16px;
    }
}
</style>
</head>


<body>


<!-- ========================= -->
<!-- 1. OPENING -->
<!-- ========================= -->

<section class="screen active opening" id="screen1">

<div class="container">

<div class="heart">❤️</div>

<h1>HEY FRESHER!</h1>

<p class="subtitle">
Welcome to a little surprise prepared by your seniors.
<br><br>

Before you meet us, you have
<strong>3 little challenges</strong>
waiting for you.
<br><br>

Ready, Junior? 👀
</p>

<button onclick="nextScreen()">
START THE CHALLENGE →
</button>

</div>

</section>


<!-- ========================= -->
<!-- 2. DARE 1 -->
<!-- ========================= -->

<section class="screen" id="screen2">

<div class="container">

<div class="dare-box">

<div class="dare-number">
DARE 01
</div>

<h2>💬</h2>

<p class="dare-text">
Tell us about your <strong>favourite senior</strong>
so far in college. 👀
</p>

<button onclick="nextScreen()">
✓ CHALLENGE COMPLETED
</button>

<div class="progress">
1 / 3 completed
</div>

</div>

</div>

</section>


<!-- ========================= -->
<!-- 3. DARE 2 -->
<!-- ========================= -->

<section class="screen" id="screen3">

<div class="container">

<div class="dare-box">

<div class="dare-number">
DARE 02
</div>

<h2>🎶</h2>

<p class="dare-text">
<strong>Sing a song!</strong>
<br><br>
No excuses. We want to hear it. 😈
</p>

<button onclick="nextScreen()">
✓ CHALLENGE COMPLETED
</button>

<div class="progress">
2 / 3 completed
</div>

</div>

</div>

</section>


<!-- ========================= -->
<!-- 4. DARE 3 -->
<!-- ========================= -->

<section class="screen" id="screen4">

<div class="container">

<div class="dare-box">

<div class="dare-number">
DARE 03
</div>

<h2>🤖</h2>

<p class="dare-text">
<strong>Speak like a robot!</strong>
<br><br>
Keep talking like a robot for the next 30 seconds. 😂
</p>

<button onclick="nextScreen()">
✓ CHALLENGE COMPLETED
</button>

<div class="progress">
3 / 3 completed
</div>

</div>

</div>

</section>


<!-- ========================= -->
<!-- 5. PASSCODE -->
<!-- ========================= -->

<section class="screen" id="screen5">

<div class="container">

<div class="passcode-box">

<div class="heart">👀</div>

<h2>WAIT… YOU ACTUALLY DID IT?</h2>

<p>
All three challenges completed!
<br><br>

But there's still one little secret waiting for you…
</p>

<h3 style="margin-top:30px;">
ENTER THE SECRET PASSCODE 🔐
</h3>

<input
type="password"
id="passcode"
placeholder="Enter code"
maxlength="6"
>

<br>

<button onclick="checkPasscode()">
UNLOCK →
</button>

<p id="error">
Wrong passcode. Try again 👀
</p>

</div>

</div>

</section>


<!-- ========================= -->
<!-- 6. ROSES -->
<!-- ========================= -->

<section class="screen rose-section" id="screen6">

<div class="container">

<h2>A LITTLE SOMETHING<br>FROM YOUR SENIORS ❤️</h2>

<!--
IMPORTANT:
Replace "roses.jpg" with your rose photo filename.
Example:
<img src="roses.jpg">
-->

<img
src="roses.jpg"
alt="A bouquet of red roses"
class="rose-photo"
>

<p class="photo-note">
A little something from your seniors.
</p>

<h2 style="margin-top:35px;">
WELCOME, JUNIOR!
</h2>

<p>
With love, laughter and lots of memories. ❤️
</p>

<button onclick="nextScreen()">
CONTINUE →
</button>

</div>

</section>


<!-- ========================= -->
<!-- 7. VASAVI INTRO -->
<!-- ========================= -->

<section class="screen" id="screen7">

<div class="container">

<h1>HEY, VASAVI! 👋</h1>

<p class="subtitle">

We know you're the fresher who has been waiting
to see what your seniors have planned for you...

<br><br>

So, before we tell you about us,
let's talk about <strong>YOU.</strong> ❤️

</p>

<button onclick="nextScreen()">
MEET VASAVI →
</button>

</div>

</section>


<!-- ========================= -->
<!-- 8. VASAVI PROFILE -->
<!-- ========================= -->

<section class="screen profile" id="screen8">

<div class="container">

<div class="profile-card">

<div class="profile-name">
🌸 VASAVI
</div>

<p>

We’ve known you from our first year, ever since you joined
Manipal for your internship. You’ve always had such a nice
and energetic personality, especially in an environment that
can sometimes be a little rude. 😄 The way you speak so nicely
with all your seniors has definitely earned you a special place
here. You’re always so eager to learn and try new things, and
honestly, you’re a little hyperactive too! 😂 Even before IRC,
you were already busy thinking about data collection.

Keep that curiosity, energy and enthusiasm, Vasavi —
we’re really happy to have you around, and we’re looking
forward to all the memories you’re going to make with us. ❤️

</p>

</div>

<button onclick="nextScreen()">
ONE MORE THING →
</button>

</div>

</section>


<!-- ========================= -->
<!-- 9. MEMORY -->
<!-- ========================= -->

<section class="screen memory" id="screen9">

<div class="container">

<h2>A MEMORY OF US 📸</h2>

<!--
Replace "vasavi-memory.jpg"
with the photo you want to use.
-->

<img
src="vasavi-memory.jpg"
alt="A memory with Vasavi"
class="memory-photo"
>

<p class="caption">
“One picture today, a memory we'll keep for a long time.” ❤️
</p>

<button onclick="nextScreen()">
CONTINUE →
</button>

</div>

</section>


<!-- ========================= -->
<!-- 10. FROM SENIORS -->
<!-- ========================= -->

<section class="screen seniors" id="screen10">

<div class="container">

<h2>FROM YOUR SENIORS ❤️</h2>

<p class="senior-message">

We are the people behind your three dares. 😈

<br><br>

You may know our faces already, but now you know that
we are also the people who wanted to give you a little
memory to take with you.

</p>

<p class="quote">

“I think you'll remember this forever. ❤️”

<br><br>

— Your Seniors

</p>

<button onclick="nextScreen()">
ONE LAST THING →
</button>

</div>

</section>


<!-- ========================= -->
<!-- 11. HANDWRITTEN LETTER -->
<!-- ========================= -->

<section class="screen letter" id="screen11">

<div class="container">

<div class="letter-box">

<div class="letter-icon">
💌
</div>

<h2>A LITTLE LETTER FOR YOU</h2>

<p>

You made it till the end…

<br><br>

So here's something you can keep.

<br><br>

<strong>
There's a handwritten letter waiting for you from your seniors.
</strong>

<br><br>

Something written especially for you —
not on a screen, but something you can actually hold onto. ❤️

</p>

<button onclick="finish()">
SEE YOU SOON →
</button>

</div>

<div class="footer">
Made with ❤️ by your seniors
</div>

</div>

</section>


<script>

/* =========================
   SCREEN CONTROL
========================= */

let currentScreen = 1;

function nextScreen() {

    const current = document.getElementById(
        "screen" + currentScreen
    );

    current.classList.remove("active");

    currentScreen++;

    const next = document.getElementById(
        "screen" + currentScreen
    );

    next.classList.add("active");

    window.scrollTo({
        top: 0,
        behavior: "smooth"
    });
}


/* =========================
   PASSCODE
========================= */

function checkPasscode() {

    const enteredCode =
        document.getElementById("passcode").value;

    const error =
        document.getElementById("error");

    if (enteredCode === "031026") {

        error.style.display = "none";

        nextScreen();

    } else {

        error.style.display = "block";

    }
}


/* =========================
   FINAL SCREEN
========================= */

function finish() {

    document.querySelector(".letter-box").innerHTML = `

        <div class="letter-icon">
        ❤️
        </div>

        <h2>SEE YOU SOON, VASAVI!</h2>

        <p>
        And don't forget to collect your letter. 💌
        </p>

        <br>

        <p>
        Until then… keep that energy alive! 😄
        </p>

        <br>

        <strong>
        — Your Seniors ❤️
        </strong>

    `;

}

</script>

</body>
</html>
