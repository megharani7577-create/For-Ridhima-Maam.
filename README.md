# For-Ridhima-Maam.



<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>For Ridhima Ma'am ❤️</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,500;0,600;1,400&family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
    --pink: #f6d5df;
    --rose: #c65d7b;
    --dark: #593743;
    --cream: #fff9f6;
}

body {
    min-height: 100vh;
    background: linear-gradient(135deg, #fff5f5, #fce4ec, #fff0e8);
    color: var(--dark);
    font-family: 'Poppins', sans-serif;
    overflow-x: hidden;
}

.heart {
    position: fixed;
    bottom: -30px;
    pointer-events: none;
    animation: floatUp linear forwards;
    z-index: 0;
    opacity: 0.6;
}

@keyframes floatUp {
    to {
        transform: translateY(-110vh) rotate(25deg);
        opacity: 0;
    }
}

.container {
    position: relative;
    z-index: 1;
    width: min(92%, 720px);
    margin: auto;
    padding: 45px 0;
}

.hero {
    min-height: 85vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
}

.flower {
    font-size: 55px;
    animation: sway 3s ease-in-out infinite;
}

@keyframes sway {
    0%, 100% { transform: rotate(-5deg); }
    50% { transform: rotate(5deg); }
}

.eyebrow {
    margin-top: 20px;
    text-transform: uppercase;
    letter-spacing: 4px;
    font-size: 11px;
    color: var(--rose);
}

h1 {
    font-family: 'Playfair Display', serif;
    font-size: clamp(36px, 8vw, 60px);
    line-height: 1.2;
    margin: 20px 0;
    font-weight: 500;
}

.hero p {
    font-size: 14px;
    line-height: 1.9;
    max-width: 420px;
    color: #87616c;
}

button {
    border: none;
    cursor: pointer;
    font-family: 'Poppins', sans-serif;
    transition: 0.3s;
}

.primary-btn {
    margin-top: 30px;
    padding: 15px 27px;
    border-radius: 40px;
    color: white;
    background: linear-gradient(135deg, #c65d7b, #a94365);
    box-shadow: 0 8px 25px #c65d7b40;
    font-size: 14px;
}

.primary-btn:hover {
    transform: translateY(-3px);
    box-shadow: 0 12px 30px #c65d7b55;
}

.letter {
    display: none;
    background: rgba(255, 255, 255, 0.83);
    border: 1px solid #ffffff;
    border-radius: 25px;
    padding: clamp(22px, 6vw, 45px);
    box-shadow: 0 15px 60px #a65d7118;
    animation: appear 1s ease;
}

@keyframes appear {
    from {
        opacity: 0;
        transform: translateY(25px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

.letter-top {
    text-align: center;
    font-size: 30px;
    margin-bottom: 25px;
}

.letter h2 {
    font-family: 'Playfair Display', serif;
    font-size: 30px;
    font-weight: 500;
    text-align: center;
    margin-bottom: 25px;
}

.letter p {
    font-size: 14px;
    line-height: 2;
    margin-bottom: 19px;
    color: #624550;
}

.highlight {
    color: #b44c6b;
    font-weight: 500;
}

.quote {
    text-align: center;
    padding: 22px 15px;
    margin: 25px 0;
    border-top: 1px solid #f1ccd7;
    border-bottom: 1px solid #f1ccd7;
    font-family: 'Playfair Display', serif;
    font-size: 21px;
    font-style: italic;
    line-height: 1.7;
    color: #b44c6b;
}

.signature {
    text-align: right;
    margin-top: 30px;
    font-family: 'Playfair Display', serif;
    font-size: 21px;
    font-style: italic;
}

.forgiveness {
    display: none;
    text-align: center;
    padding: 35px 20px;
    margin-top: 30px;
    border-radius: 22px;
    background: #fff0f4;
    animation: appear 0.8s ease;
}

.forgiveness h3 {
    font-family: 'Playfair Display', serif;
    font-size: 27px;
    margin-bottom: 15px;
}

.forgiveness p {
    font-size: 14px;
    line-height: 1.9;
}

footer {
    text-align: center;
    padding: 35px 10px 10px;
    font-size: 11px;
    color: #a17c88;
    letter-spacing: 1px;
}

footer span {
    color: #c65d7b;
}

@media (max-width: 480px) {
    .container {
        width: 90%;
    }

    .letter p {
        font-size: 13px;
    }

    .quote {
        font-size: 19px;
    }
}
</style>
</head>

<body>

<div class="container">

    <section class="hero" id="hero">
        <div class="flower">🌷</div>

        <div class="eyebrow">A letter from my heart</div>

        <h1>For Ridhima<br>Ma'am ❤️</h1>

        <p>
            Some people give us opportunities.<br>
            Some give us memories.<br>
            And some teach us lessons that stay with us forever.
        </p>

        <button class="primary-btn" onclick="openLetter()">
            Open My Letter 💌
        </button>

        <p style="margin-top: 22px; font-size: 11px;">
            Made with gratitude, love and a sincere apology.
        </p>
    </section>

    <section class="letter" id="letter">

        <div class="letter-top">💌 🌷 💌</div>

        <h2>Dear Ridhima Ma'am ❤️</h2>

        <p>
            Thank you for giving me the opportunity to stand beside you
            on the stage of <span class="highlight">The Legacy Lounge</span>
            and for giving me one of the most beautiful memories of my
            college life. 🥹❤️
        </p>

        <p>
            I have faced many hurdles and even lost some relationships
            just to be a part of our E-Cell, Queenpreneurs. There were
            moments when things felt difficult, and I questioned a lot
            of things. But today, after standing on that stage, I can
            finally say that everything feels worth it. ✨
        </p>

        <div class="quote">
            "When you believe in yourself, limited resources cannot
            limit your dreams."
        </div>

        <p>
            You have taught me something I will never forget. You didn't
            just give me an opportunity; you gave me a memory, a lesson,
            and an experience that I will carry with me for the rest of
            my life.
        </p>

        <p>
            I also want to sincerely apologise for every doubt I had
            regarding the Illuminate event and for the moments when I
            doubted your leadership. I am truly sorry from the bottom
            of my heart. Please forgive me for my mistakes.
        </p>

        <p>
            Thank you for being patient with me, tolerating my doubts,
            and helping me understand what teamwork, trust, and
            leadership truly mean.
        </p>

        <p>
            Today, after this event, I can proudly say once again that
            <span class="highlight">Ridhima Singh is the person I chose
            as my ideal when I first saw her in college.</span>
            And today, I have even more reasons to look up to you. ❤️
        </p>

        <p>
            Thank you for every lesson, every opportunity, and every
            moment that helped me grow. The knowledge you have given me
            is something I will carry throughout my life, using it to
            light my path whenever I feel lost.
        </p>

        <p>
            I may not always have expressed my thoughts in the right
            way, but my gratitude and respect for you are genuine.
            I am truly grateful to have been a part of Queenpreneurs
            under your leadership.
        </p>

        <p>
            Thank you for making today's moment so special that all
            the struggles leading up to it finally feel meaningful.
            ❤️✨
        </p>

        <div class="signature">
            With respect, gratitude & a sincere apology 🫶🏻
        </div>

        <div style="text-align:center; margin-top:35px;">
            <p style="font-size:14px;">
                There is just one more thing I want to ask you...
            </p>

            <button class="primary-btn" onclick="showForgiveness()">
                Can You Forgive Me, Ma'am? 🥹❤️
            </button>
        </div>

        <div class="forgiveness" id="forgiveness">
            <div style="font-size:42px; margin-bottom:15px;">🫶🏻</div>

            <h3>Thank You, Ma'am ❤️</h3>

            <p>
                Whatever your answer may be, I will always be grateful
                for the lessons you have taught me.<br><br>

                I cannot change the moments when I misunderstood things,
                but I can learn from them and become a better teammate
                and a better person.<br><br>

                You will always have my respect, and the lessons I
                learned from you will continue to light my path. 🌷
            </p>

            <div style="font-size:30px; margin-top:20px;">
                🌷 ❤️ ✨
            </div>
        </div>

    </section>

    <footer>
        MADE WITH A GRATEFUL HEART <span>♥</span><br><br>
        For the woman who taught me more than she knows.
    </footer>

</div>

<script>
function openLetter() {
    document.getElementById("hero").style.display = "none";

    const letter = document.getElementById("letter");
    letter.style.display = "block";

    window.scrollTo({
        top: 0,
        behavior: "smooth"
    });
}

function showForgiveness() {
    const message = document.getElementById("forgiveness");
    message.style.display = "block";

    message.scrollIntoView({
        behavior: "smooth",
        block: "center"
    });

    for (let i = 0; i < 18; i++) {
        setTimeout(createHeart, i * 100);
    }
}

function createHeart() {
    const heart = document.createElement("div");

    heart.className = "heart";

    const symbols = ["❤️", "💗", "💕", "🌷", "✨"];
    heart.textContent = symbols[
        Math.floor(Math.random() * symbols.length)
    ];

    heart.style.left = Math.random() * 100 + "vw";
    heart.style.fontSize = (14 + Math.random() * 20) + "px";
    heart.style.animationDuration = (4 + Math.random() * 5) + "s";

    document.body.appendChild(heart);

    setTimeout(() => heart.remove(), 9500);
}

setInterval(createHeart, 900);
</script>

</body>
</html>
