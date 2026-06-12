<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Compatibility Check</title>
    <style>
        :root {
            --bg: #070b17;
            --panel: rgba(255, 255, 255, 0.08);
            --line: rgba(255, 255, 255, 0.16);
            --text: #f8fbff;
            --muted: #aeb9d6;
            --cyan: #76e8ff;
            --pink: #ff5ca8;
            --violet: #c9a7ff;
            --green: #8affc1;
            --yellow: #ffd166;
            --shadow: 0 28px 80px rgba(0, 0, 0, 0.45);
        }

        * {
            box-sizing: border-box;
        }

        body {
            min-height: 100vh;
            margin: 0;
            font-family: Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
            color: var(--text);
            background:
                radial-gradient(circle at 14% 16%, rgba(118, 232, 255, 0.28), transparent 28%),
                radial-gradient(circle at 86% 12%, rgba(255, 92, 168, 0.24), transparent 25%),
                linear-gradient(145deg, #070b17 0%, #11172d 55%, #170d24 100%);
            overflow-x: hidden;
        }

        body::before {
            content: "";
            position: fixed;
            inset: 0;
            pointer-events: none;
            background-image:
                linear-gradient(rgba(255, 255, 255, 0.04) 1px, transparent 1px),
                linear-gradient(90deg, rgba(255, 255, 255, 0.04) 1px, transparent 1px);
            background-size: 42px 42px;
            mask-image: linear-gradient(to bottom, #000, transparent 78%);
        }

        main {
            position: relative;
            display: grid;
            min-height: 100vh;
            place-items: center;
            padding: 24px;
        }

        .shell {
            width: min(92vmin, 900px);
            aspect-ratio: 1 / 1;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 18px;
        }

        .hero,
        .terminal {
            min-width: 0;
            border: 1px solid var(--line);
            border-radius: 24px;
            background: var(--panel);
            box-shadow: var(--shadow);
            backdrop-filter: blur(22px);
        }

        .hero {
            position: relative;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            overflow: hidden;
            padding: clamp(20px, 3.6vmin, 36px);
        }

        .hero::after {
            content: "";
            position: absolute;
            width: 320px;
            height: 320px;
            right: -150px;
            bottom: -130px;
            border-radius: 50%;
            background: conic-gradient(from 180deg, var(--pink), var(--cyan), var(--green), var(--pink));
            filter: blur(34px);
            opacity: 0.34;
        }

        .badge {
            position: relative;
            z-index: 1;
            width: fit-content;
            display: inline-flex;
            align-items: center;
            gap: 9px;
            padding: 10px 13px;
            border-radius: 999px;
            border: 1px solid rgba(118, 232, 255, 0.28);
            color: var(--cyan);
            background: rgba(118, 232, 255, 0.09);
            font-size: 0.76rem;
            font-weight: 800;
            letter-spacing: 0.04em;
            text-transform: uppercase;
        }

        .pulse {
            width: 9px;
            height: 9px;
            border-radius: 50%;
            background: var(--green);
            box-shadow: 0 0 0 0 rgba(138, 255, 193, 0.64);
            animation: pulse 1.7s infinite;
        }

        h1 {
            position: relative;
            z-index: 1;
            margin: 28px 0 16px;
            font-size: clamp(2.3rem, 7.3vmin, 4.9rem);
            line-height: 0.96;
            letter-spacing: 0;
        }

        .gradient-text {
            display: block;
            color: transparent;
            background: linear-gradient(90deg, var(--cyan), #ffffff 48%, var(--pink));
            -webkit-background-clip: text;
            background-clip: text;
        }

        .lead {
            position: relative;
            z-index: 1;
            margin: 0;
            max-width: 34rem;
            color: var(--muted);
            font-size: clamp(0.9rem, 1.55vmin, 1rem);
            line-height: 1.58;
        }

        .cta-row {
            position: relative;
            z-index: 1;
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 18px;
        }

        button {
            border: 0;
            border-radius: 15px;
            padding: 12px 16px;
            color: #07101f;
            background: linear-gradient(135deg, var(--cyan), var(--pink));
            font-weight: 900;
            font-size: 0.88rem;
            cursor: pointer;
            box-shadow: 0 16px 34px rgba(255, 92, 168, 0.24);
            transition: transform 180ms ease, box-shadow 180ms ease, opacity 180ms ease;
        }

        button:hover {
            transform: translateY(-2px);
            box-shadow: 0 20px 42px rgba(118, 232, 255, 0.19);
        }

        button:disabled {
            cursor: not-allowed;
            opacity: 0.7;
            transform: none;
        }

        .ghost {
            color: var(--text);
            background: rgba(255, 255, 255, 0.08);
            border: 1px solid rgba(255, 255, 255, 0.18);
            box-shadow: none;
        }

        .terminal {
            display: flex;
            flex-direction: column;
            padding: 16px;
            overflow: hidden;
        }

        .terminal-top {
            display: flex;
            align-items: center;
            justify-content: space-between;
            gap: 12px;
            padding: 7px 5px 15px;
            color: var(--muted);
            font-size: 0.78rem;
        }

        .dots {
            display: flex;
            gap: 7px;
        }

        .dots span {
            width: 10px;
            height: 10px;
            border-radius: 50%;
            background: #ff6b91;
        }

        .dots span:nth-child(2) {
            background: var(--yellow);
        }

        .dots span:nth-child(3) {
            background: var(--green);
        }

        .code-card {
            flex: 1;
            display: flex;
            flex-direction: column;
            min-height: 0;
            padding: 18px;
            border-radius: 18px;
            background: rgba(2, 8, 23, 0.76);
            border: 1px solid rgba(255, 255, 255, 0.1);
            font-family: "Cascadia Code", "Fira Code", Consolas, monospace;
        }

        .lives {
            display: flex;
            align-items: center;
            justify-content: space-between;
            gap: 12px;
            margin-bottom: 12px;
            padding: 10px 12px;
            border-radius: 14px;
            color: var(--muted);
            background: rgba(255, 255, 255, 0.055);
            border: 1px solid rgba(255, 255, 255, 0.1);
            font-size: 0.78rem;
            font-weight: 800;
        }

        .heart-meter {
            display: flex;
            gap: 7px;
        }

        .pixel-heart {
            color: #b56dff;
            font-size: 1rem;
            line-height: 1;
            text-shadow:
                2px 0 0 #5f2fb5,
                0 2px 0 #5f2fb5,
                2px 2px 0 #5f2fb5;
            filter: drop-shadow(0 0 7px rgba(181, 109, 255, 0.42));
        }

        .pixel-heart.empty {
            color: rgba(181, 109, 255, 0.18);
            text-shadow: none;
            filter: none;
        }

        .log {
            flex: 1;
            min-height: 0;
            overflow-y: auto;
            padding-right: 4px;
        }

        .line {
            min-height: 25px;
            color: #dbe7ff;
            white-space: pre-wrap;
            word-break: break-word;
            font-size: clamp(0.78rem, 1.55vmin, 0.94rem);
            line-height: 1.5;
        }

        .line .key {
            color: var(--cyan);
        }

        .line .string {
            color: var(--green);
        }

        .line .warn {
            color: var(--yellow);
        }

        .line .answer {
            color: var(--pink);
            font-weight: 900;
        }

        .console-form {
            display: none;
            gap: 10px;
            margin-top: 14px;
        }

        .console-form.show {
            display: flex;
        }

        .console-form input {
            min-width: 0;
            flex: 1;
            border: 1px solid rgba(118, 232, 255, 0.24);
            border-radius: 14px;
            padding: 13px 14px;
            color: var(--text);
            background: rgba(255, 255, 255, 0.07);
            outline: none;
            font: inherit;
        }

        .console-form input:focus {
            border-color: var(--cyan);
            box-shadow: 0 0 0 4px rgba(118, 232, 255, 0.1);
        }

        .console-form button {
            padding-inline: 15px;
        }

        .retry-btn {
            display: none;
            width: 100%;
            margin-top: 14px;
        }

        .retry-btn.show {
            display: block;
        }

        .reveal {
            display: none;
            margin-top: 18px;
            padding: 22px;
            border-radius: 20px;
            text-align: center;
            background: linear-gradient(135deg, rgba(255, 92, 168, 0.2), rgba(118, 232, 255, 0.14));
            border: 1px solid rgba(255, 255, 255, 0.18);
        }

        .reveal.show {
            display: block;
            animation: pop 420ms ease both;
        }

        .yes {
            margin: 0;
            font-size: clamp(3.2rem, 10vmin, 7rem);
            line-height: 0.9;
            color: transparent;
            background: linear-gradient(90deg, #ffffff, var(--pink), var(--cyan));
            -webkit-background-clip: text;
            background-clip: text;
            font-weight: 950;
        }

        .reveal p {
            margin: 13px auto 0;
            max-width: 390px;
            color: #e4ebff;
            line-height: 1.6;
            font-size: 0.92rem;
        }

        .specific-btn {
            margin-top: 16px;
            padding: 12px 16px;
        }

        .specific-message {
            display: none;
            margin: 16px auto 0;
            max-width: 390px;
            padding: 16px;
            border-radius: 16px;
            color: #fff;
            background: rgba(255, 255, 255, 0.08);
            border: 1px solid rgba(255, 255, 255, 0.16);
            font-family: Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
            font-weight: 800;
            line-height: 1.5;
        }

        .specific-message.show {
            display: block;
            animation: pop 360ms ease both;
        }

        .floating {
            position: fixed;
            inset: 0;
            pointer-events: none;
            overflow: hidden;
        }

        .heart {
            position: absolute;
            color: var(--pink);
            animation: floatUp 4s linear forwards;
            opacity: 0.9;
        }

        @keyframes pulse {
            70% {
                box-shadow: 0 0 0 12px rgba(138, 255, 193, 0);
            }
            100% {
                box-shadow: 0 0 0 0 rgba(138, 255, 193, 0);
            }
        }

        @keyframes pop {
            from {
                opacity: 0;
                transform: translateY(14px) scale(0.96);
            }
            to {
                opacity: 1;
                transform: translateY(0) scale(1);
            }
        }

        @keyframes floatUp {
            from {
                transform: translateY(20px) rotate(0deg);
            }
            to {
                transform: translateY(-105vh) rotate(240deg);
                opacity: 0;
            }
        }

        @media (max-width: 820px) {
            main {
                padding: 14px;
            }

            .shell {
                width: min(100%, 560px);
                aspect-ratio: auto;
                grid-template-columns: 1fr;
            }

            .hero,
            .terminal {
                min-height: 440px;
                border-radius: 22px;
            }

            .cta-row button,
            .console-form button {
                width: 100%;
            }

            .console-form {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <main>
        <section class="shell" aria-label="A romantic IT-themed compatibility check">
            <div class="hero">
                <div>
                    <div class="badge"><span class="pulse"></span>Lindsay Console</div>
                    <h1>
                        Console Test Game.
                        <span class="gradient-text">Can you pass? </span>
                    </h1>
                    <p class="lead">
                        Test Your knowledge on this console
                    </p>
                </div>

                <div class="cta-row">
                    <button id="startBtn" type="button">Start commit test</button>
                </div>
            </div>

            <aside class="terminal" aria-live="polite">
                <div class="terminal-top">
                    <div class="dots" aria-hidden="true"><span></span><span></span><span></span></div>
                    <span>Test Your Knowledge</span>
                </div>

                <div class="code-card">
                    <div class="lives" aria-live="polite">
                        <span>Lives</span>
                        <div class="heart-meter" id="heartMeter" aria-label="5 lives remaining"></div>
                    </div>

                    <div class="log" id="log"></div>

                    <form class="console-form" id="consoleForm" autocomplete="off">
                        <input id="answerInput" type="text" placeholder="type your answer here..." aria-label="Type your answer">
                        <button type="submit">Enter</button>
                    </form>

                    <button class="retry-btn" id="retryBtn" type="button">Try again</button>

                    <div class="reveal" id="reveal">
                        <h2 class="yes">YES</h2>
                        <p>
                            Yes, I would love to be yours. You passed the check, and my answer is finally deployed.
                        </p>
                        <button class="specific-btn" id="specificBtn" type="button">Want more specific?</button>
                        <div class="specific-message" id="specificMessage"></div>
                    </div>
                </div>
            </aside>
        </section>
    </main>

    <div class="floating" id="floating" aria-hidden="true"></div>

    <script>
        const log = document.getElementById("log");
        const reveal = document.getElementById("reveal");
        const startBtn = document.getElementById("startBtn");
        const peekBtn = document.getElementById("peekBtn");
        const consoleForm = document.getElementById("consoleForm");
        const answerInput = document.getElementById("answerInput");
        const specificBtn = document.getElementById("specificBtn");
        const specificMessage = document.getElementById("specificMessage");
        const floating = document.getElementById("floating");
        const heartMeter = document.getElementById("heartMeter");
        const retryBtn = document.getElementById("retryBtn");
        const maxLives = 5;
        let lives = maxLives;

        const quiz = [
            {
                question: "Level 1: What command stages all changed files?",
                reply: "Correct. Files staged successfully.",
                error: "Incorrect. Try the command that adds every changed file.",
                validate: (answer) => normalizeCommand(answer) === "git add ."
            },
            {
                question: "Level 2: What command creates a commit with the message comment?",
                reply: "Correct. Commit created.",
                error: "Incorrect. Include the commit message exactly.",
                validate: (answer) => normalizeCommand(answer) === 'git commit -m "comment"'
            },
            {
                question: "Level 3: What command pushes to origin with the branch inside quotes?",
                reply: "Correct. Branch pushed to origin.",
                error: "Incorrect. Include origin and the quoted branch name.",
                validate: (answer) => normalizeCommand(answer) === 'git push origin "branch"'
            },
            {
                question: "Creator check: What's the Creator fav color?",
                reply: "Correct. Creator profile unlocked.",
                error: "Wrong color. Try again.",
                revives: true,
                validate: (answer) => normalize(answer) === "purple"
            },
            {
                question: "Creator check: What food can instantly make the Creator happy?",
                reply: "Correct. That answer is cached permanently.",
                error: "Nope. Be specific. Full name, please.",
                revives: true,
                validate: (answer) => normalize(answer) === "dubai chewy cookie"
            },
            {
                question: "Creator check: What is one thing you like about the Creator?",
                reply: "Okay, that one made me smile.",
                error: "",
                revives: true,
                validate: (answer) => answer.trim().length > 0
            },
            {
                question: "Final check: are you ready for the resultss?",
                reply: "Request accepted. Preparing final response...",
                error: "I need a clear yes before deploying this.",
                validate: (answer) => normalize(answer) === "yes"
            }
        ];

        let currentQuestion = 0;
        let started = false;

        function addLine(html) {
            const line = document.createElement("div");
            line.className = "line";
            line.innerHTML = html;
            log.appendChild(line);
            log.scrollTop = log.scrollHeight;
        }

        function askQuestion() {
            addLine('<span class="key">system:</span> ' + quiz[currentQuestion].question);
            answerInput.value = "";
            answerInput.focus();
        }

        function startCheck() {
            if (started) {
                answerInput.focus();
                return;
            }

            started = true;
            currentQuestion = 0;
            lives = maxLives;
            renderLives();
            reveal.classList.remove("show");
            log.innerHTML = "";
            startBtn.textContent = "Check running...";
            startBtn.disabled = true;
            consoleForm.classList.add("show");
            retryBtn.classList.remove("show");

            addLine('<span class="key">boot:</span> loading basic commit knowledge test...');
            setTimeout(askQuestion, 700);
        }

        function finishCheck() {
            consoleForm.classList.remove("show");
            addLine('<span class="key">system:</span> validating answers...');
            setTimeout(() => addLine('<span class="string">status:</span> sincerity detected'), 650);
            setTimeout(() => addLine('<span class="string">status:</span> heart permission granted'), 1250);
            setTimeout(() => {
                reveal.classList.add("show");
                startBtn.textContent = "Answer unlocked";
                launchHearts();
            }, 1900);
        }

        consoleForm.addEventListener("submit", (event) => {
            event.preventDefault();

            const value = answerInput.value.trim();
            if (!value) {
                addLine('<span class="warn">console:</span> no blank answers. Try again.');
                answerInput.focus();
                return;
            }

            addLine('<span class="key">you:</span> ' + escapeHtml(value));

            if (!quiz[currentQuestion].validate(value)) {
                addLine('<span class="warn">console:</span> ' + quiz[currentQuestion].error);
                loseLife();
                answerInput.value = "";
                answerInput.focus();
                return;
            }

            addLine('<span class="string">console:</span> ' + quiz[currentQuestion].reply);
            if (quiz[currentQuestion].revives) {
                reviveLife();
            }
            currentQuestion++;

            if (currentQuestion >= quiz.length) {
                finishCheck();
                return;
            }

            if (currentQuestion === 3) {
                const bonusMessage = lives === maxLives
                    ? "Bonus Questions"
                    : "Bonus Questions to revive lives...";

                setTimeout(() => addLine('<span class="warn">system:</span> ' + bonusMessage), 420);
                setTimeout(askQuestion, 1050);
                return;
            }

            setTimeout(askQuestion, 650);
        });

        if (peekBtn) {
            peekBtn.addEventListener("click", () => {
                addLine('<span class="warn">access denied:</span> answer locked behind the questions.');
                if (!started) {
                    startCheck();
                }
            });
        }

        startBtn.addEventListener("click", startCheck);

        specificBtn.addEventListener("click", () => {
            const today = new Date();
            const dateText = today.toLocaleDateString(undefined, {
                weekday: "long",
                year: "numeric",
                month: "long",
                day: "numeric"
            });

            specificMessage.textContent = "YES! You're my boyfriend now, today, " + dateText + ".";
            specificMessage.classList.add("show");
            specificBtn.textContent = "Specific answer deployed";
            specificBtn.disabled = true;
            launchHearts();
        });

        function escapeHtml(value) {
            return value
                .replace(/&/g, "&amp;")
                .replace(/</g, "&lt;")
                .replace(/>/g, "&gt;")
                .replace(/"/g, "&quot;")
                .replace(/'/g, "&#039;");
        }

        function normalize(value) {
            return value.trim().replace(/\s+/g, " ").toLowerCase();
        }

        function normalizeCommand(value) {
            return normalize(value).replace(/[“”]/g, '"');
        }

        function renderLives() {
            heartMeter.innerHTML = "";
            heartMeter.setAttribute("aria-label", lives + " lives remaining");

            for (let i = 0; i < maxLives; i++) {
                const heart = document.createElement("span");
                heart.className = "pixel-heart" + (i >= lives ? " empty" : "");
                heart.textContent = "\u2665";
                heartMeter.appendChild(heart);
            }
        }

        function loseLife() {
            lives = Math.max(0, lives - 1);
            renderLives();
            addLine('<span class="warn">lives:</span> -1 purple heart');

            if (lives === 0) {
                addLine('<span class="warn">system:</span> no hearts left. Game over.');
                endGame();
            }
        }

        function endGame() {
            consoleForm.classList.remove("show");
            retryBtn.classList.add("show");
            startBtn.textContent = "Game over";
            answerInput.value = "";
        }

        function resetGame() {
            started = false;
            currentQuestion = 0;
            lives = maxLives;
            renderLives();
            log.innerHTML = "";
            reveal.classList.remove("show");
            retryBtn.classList.remove("show");
            consoleForm.classList.remove("show");
            startBtn.disabled = false;
            startBtn.textContent = "Start commit test";
            specificMessage.classList.remove("show");
            specificMessage.textContent = "";
            specificBtn.disabled = false;
            specificBtn.textContent = "Want more specific?";
        }

        function reviveLife() {
            if (lives >= maxLives) {
                return;
            }

            lives++;
            renderLives();
            addLine('<span class="string">lives:</span> +1 purple heart revived');
        }

        function launchHearts() {
            for (let i = 0; i < 34; i++) {
                setTimeout(() => {
                    const heart = document.createElement("div");
                    heart.className = "heart";
                    heart.textContent = "♥";
                    heart.style.left = Math.random() * 100 + "vw";
                    heart.style.bottom = "-24px";
                    heart.style.fontSize = 14 + Math.random() * 26 + "px";
                    heart.style.animationDuration = 3.2 + Math.random() * 2.4 + "s";
                    floating.appendChild(heart);
                    setTimeout(() => heart.remove(), 6000);
                }, i * 90);
            }
        }

        retryBtn.addEventListener("click", resetGame);

        renderLives();
    </script>
</body>
</html>
