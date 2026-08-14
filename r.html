<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>املا آموز | یادگیری املا و نوشتن انگلیسی</title>
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --sky1: #7ec8ff;
    --sky2: #4fa3f7;
    --yellow: #ffd93d;
    --orange: #ff9f1c;
    --pink: #ff7eb3;
    --green: #6ac96a;
    --purple: #b388ff;
    --ink: #2d3e50;
    --white: #ffffff;
  }

  html, body { height: 100%; }

  body {
    font-family: "Vazirmatn", "Segoe UI", "Comic Sans MS", "Comic Sans", Tahoma, sans-serif;
    background: linear-gradient(160deg, var(--sky1) 0%, var(--sky2) 100%);
    color: var(--ink);
    overflow-x: hidden;
    -webkit-tap-highlight-color: transparent;
    touch-action: manipulation;
  }

  /* ---------- floating decorations ---------- */
  .floaties {
    position: fixed;
    inset: 0;
    pointer-events: none;
    z-index: 0;
    overflow: hidden;
  }
  .floaty {
    position: absolute;
    font-size: 34px;
    opacity: .25;
    animation: drift linear infinite;
  }
  @keyframes drift {
    from { transform: translateY(105vh) rotate(0deg); }
    to   { transform: translateY(-15vh) rotate(40deg); }
  }

  .app {
    position: relative;
    z-index: 1;
    max-width: 640px;
    margin: 0 auto;
    padding: 14px 14px calc(40px + env(safe-area-inset-bottom));
    min-height: 100vh;
    min-height: 100dvh;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  /* ---------- top bar ---------- */
  .topbar {
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 14px;
  }
  .brand {
    background: rgba(255,255,255,.9);
    border-radius: 999px;
    padding: 8px 20px;
    font-size: 22px;
    font-weight: 800;
    color: var(--ink);
    box-shadow: 0 4px 12px rgba(0,0,0,.15);
    display: flex;
    align-items: center;
    gap: 8px;
  }
  .brand .owl { font-size: 28px; }
  .home-btn {
    background: rgba(255,255,255,.9);
    border: none;
    border-radius: 999px;
    padding: 10px 16px;
    font-size: 20px;
    cursor: pointer;
    box-shadow: 0 4px 12px rgba(0,0,0,.15);
    transition: transform .15s;
  }
  .home-btn:hover { transform: scale(1.1); }

  /* ---------- screens ---------- */
  .screen { display: none; width: 100%; flex-direction: column; align-items: center; }
  .screen.active { display: flex; animation: popIn .35s ease; }
  @keyframes popIn {
    from { opacity: 0; transform: scale(.94); }
    to   { opacity: 1; transform: scale(1); }
  }

  .big-title {
    font-size: 42px;
    font-weight: 900;
    color: #fff;
    text-shadow: 0 3px 0 rgba(0,0,0,.18);
    text-align: center;
    margin: 10px 0 6px;
  }
  .subtitle {
    font-size: 18px;
    color: rgba(255,255,255,.95);
    text-align: center;
    margin-bottom: 20px;
  }

  .card {
    background: rgba(255,255,255,.94);
    border-radius: 28px;
    padding: 22px;
    box-shadow: 0 10px 30px rgba(0,0,0,.18);
    width: 100%;
  }

  /* ---------- overall progress card ---------- */
  .progress-card { margin-bottom: 14px; padding: 16px 18px; }
  .overall-row { display: flex; justify-content: space-between; align-items: center; font-size: 17px; font-weight: 800; margin-bottom: 8px; }
  .overall-row b { font-size: 24px; color: var(--green); }
  .progress-wrap { background: rgba(255,255,255,.85); border-radius: 999px; height: 18px; overflow: hidden; box-shadow: inset 0 2px 4px rgba(0,0,0,.12); }
  .progress-wrap.big { height: 20px; }
  .progress-bar { height: 100%; background: linear-gradient(90deg, var(--green), #7fd97f); border-radius: 999px; width: 0%; transition: width .4s ease; }
  .details-btn {
    margin-top: 10px; width: 100%;
    border: none; border-radius: 999px; padding: 10px;
    font-size: 15px; font-weight: 700; font-family: inherit; cursor: pointer;
    background: var(--sky2); color: #fff; box-shadow: 0 4px 0 #2f7fd1;
    transition: transform .12s;
  }
  .details-btn:hover { transform: scale(1.02); }

  /* ---------- level grid ---------- */
  .level-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 14px;
  }
  .level-btn {
    border: none;
    border-radius: 22px;
    padding: 16px 12px;
    cursor: pointer;
    font-family: inherit;
    color: #fff;
    box-shadow: 0 6px 0 rgba(0,0,0,.18);
    transition: transform .12s, box-shadow .12s;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 3px;
  }
  .level-btn:hover { transform: translateY(-3px) scale(1.03); }
  .level-btn:active { transform: translateY(2px); box-shadow: 0 2px 0 rgba(0,0,0,.18); }
  .level-btn .lvl-num { font-size: 38px; font-weight: 900; line-height: 1; }
  .level-btn .lvl-label { font-size: 15px; font-weight: 700; }
  .lvl-bar { display: block; width: 100%; height: 9px; background: rgba(255,255,255,.45); border-radius: 99px; overflow: hidden; margin-top: 3px; }
  .lvl-bar i { display: block; height: 100%; background: #fff; border-radius: 99px; transition: width .4s ease; }
  .lvl-meta { display: flex; align-items: center; gap: 7px; margin-top: 2px; font-size: 14px; }
  .lvl-meta b { font-weight: 900; }
  .lvl-stars { font-size: 14px; letter-spacing: 2px; }
  .lvl-review-badge { font-size: 12px; background: #fff; color: #d64545; border-radius: 99px; padding: 1px 8px; font-weight: 800; }
  .c3  { background: var(--yellow); }
  .c4  { background: var(--orange); }
  .c5  { background: var(--pink); }
  .c6  { background: var(--green); }
  .c7  { background: var(--purple); }
  .level-btn.done { outline: 4px solid #fff; }

  .hint-text {
    margin-top: 14px;
    font-size: 15px;
    color: #fff;
    text-align: center;
    background: rgba(0,0,0,.18);
    border-radius: 14px;
    padding: 10px 14px;
  }

  /* ---------- game header ---------- */
  .game-head {
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 8px;
    margin-bottom: 8px;
  }
  .game-head .progress-wrap { flex: 1; margin: 0 10px; }
  .game-count { color: #fff; font-weight: 800; font-size: 17px; white-space: nowrap; }

  .mode-toggle {
    display: flex;
    gap: 8px;
    overflow-x: auto;
    -webkit-overflow-scrolling: touch;
    max-width: 100%;
    padding-bottom: 4px;
    margin-bottom: 10px;
  }
  .mode-btn {
    white-space: nowrap;
    flex: 0 0 auto;
    border: none;
    border-radius: 999px;
    padding: 9px 14px;
    font-size: 14px;
    font-weight: 700;
    font-family: inherit;
    cursor: pointer;
    background: rgba(255,255,255,.7);
    color: var(--ink);
    transition: transform .12s;
  }
  .mode-btn.active {
    background: var(--orange);
    color: #fff;
    box-shadow: 0 4px 10px rgba(0,0,0,.2);
  }
  .mode-btn:hover { transform: scale(1.05); }

  /* ---------- word card ---------- */
  .word-card { text-align: center; }
  .emoji-box {
    font-size: 110px;
    line-height: 1.2;
    background: linear-gradient(135deg, #fff7d6, #ffe29a);
    border-radius: 30px;
    padding: 14px 10px;
    margin-bottom: 12px;
    box-shadow: inset 0 -6px 0 rgba(0,0,0,.08);
    position: relative;
    user-select: none;
    cursor: pointer;
  }
  .emoji-box .shadow {
    position: absolute;
    bottom: 12px;
    left: 50%;
    transform: translateX(-50%);
    width: 60%;
    height: 14px;
    background: rgba(0,0,0,.15);
    border-radius: 50%;
    filter: blur(3px);
  }
  .tap-hint {
    font-size: 14px;
    color: #8a6d1d;
    background: #fff3c4;
    border-radius: 999px;
    padding: 6px 14px;
    display: inline-block;
    margin-bottom: 10px;
  }
  .speak-btn {
    border: none;
    border-radius: 999px;
    padding: 10px 20px;
    font-size: 18px;
    font-weight: 700;
    font-family: inherit;
    cursor: pointer;
    background: var(--sky2);
    color: #fff;
    box-shadow: 0 5px 0 #2f7fd1;
    transition: transform .12s;
    animation: pulse 2.2s ease-in-out infinite;
  }
  .speak-btn:hover { transform: scale(1.06); }
  .speak-btn:active { transform: translateY(3px); box-shadow: 0 2px 0 #2f7fd1; }
  @keyframes pulse {
    0%, 100% { transform: scale(1); }
    50% { transform: scale(1.06); }
  }

  .dict-msg {
    display: none;
    font-size: 22px;
    font-weight: 800;
    color: #8a6d1d;
    background: #fff3c4;
    border-radius: 14px;
    padding: 10px 18px;
    margin: 12px 0 6px;
  }

  /* ---------- cover (look / write) ---------- */
  .cover-look {
    display: none;
    flex-direction: column;
    align-items: center;
    gap: 10px;
    margin: 16px 0 6px;
  }
  .cover-word {
    direction: ltr;
    font-size: 64px;
    font-weight: 900;
    letter-spacing: 10px;
    color: var(--sky2);
    background: #eef4ff;
    border-radius: 20px;
    padding: 8px 22px;
    animation: popIn .35s ease;
  }
  .cover-count { font-size: 16px; color: #8a6d1d; background: #fff3c4; border-radius: 99px; padding: 6px 14px; }
  .ready-btn {
    border: none; border-radius: 999px; padding: 12px 24px;
    font-size: 18px; font-weight: 800; font-family: inherit; cursor: pointer;
    background: var(--green); color: #fff; box-shadow: 0 5px 0 #3f9c3f;
    transition: transform .12s;
  }
  .ready-btn:hover { transform: scale(1.06); }
  .ready-btn:active { transform: translateY(3px); box-shadow: 0 2px 0 #3f9c3f; }

  /* ---------- slots (tiles mode) ---------- */
  .slots {
    display: flex;
    justify-content: center;
    gap: 10px;
    direction: ltr;
    margin: 18px 0 8px;
    min-height: 84px;
    flex-wrap: wrap;
  }
  .slot {
    width: 66px;
    height: 78px;
    border-radius: 16px;
    background: #eef4ff;
    border: 3px dashed #b7c9e8;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 40px;
    font-weight: 900;
    color: var(--ink);
    cursor: pointer;
    transition: transform .12s, border-color .12s, background .12s;
    user-select: none;
  }
  .slot.filled {
    background: #fff;
    border: 3px solid var(--sky2);
    animation: tilePop .25s ease;
  }
  .slot .letter { animation: tilePop .25s ease; display: inline-block; }
  @keyframes tilePop {
    0% { transform: scale(.3); }
    70% { transform: scale(1.25); }
    100% { transform: scale(1); }
  }
  .slot:hover { border-color: var(--orange); }

  .tiles {
    display: flex;
    justify-content: center;
    gap: 10px;
    direction: ltr;
    margin-top: 8px;
    flex-wrap: wrap;
    min-height: 80px;
  }
  .tile {
    width: 66px;
    height: 78px;
    border: none;
    border-radius: 16px;
    font-size: 40px;
    font-weight: 900;
    font-family: inherit;
    color: #fff;
    cursor: pointer;
    box-shadow: 0 6px 0 rgba(0,0,0,.2);
    transition: transform .12s, box-shadow .12s;
    user-select: none;
    text-shadow: 0 2px 0 rgba(0,0,0,.18);
  }
  .tile:hover { transform: translateY(-4px) scale(1.06); }
  .tile:active { transform: translateY(2px); box-shadow: 0 2px 0 rgba(0,0,0,.2); }

  /* ---------- typing ---------- */
  .type-area { display: none; flex-direction: column; align-items: center; gap: 12px; width: 100%; margin: 18px 0 8px; }
  .type-input {
    width: 100%;
    max-width: 380px;
    text-align: center;
    direction: ltr;
    font-size: 42px;
    font-weight: 900;
    font-family: inherit;
    letter-spacing: 8px;
    border: 4px solid var(--sky2);
    border-radius: 20px;
    padding: 12px;
    color: var(--ink);
    background: #fff;
    outline: none;
    text-transform: lowercase;
  }
  .type-input:focus { border-color: var(--orange); }
  .check-btn {
    border: none;
    border-radius: 999px;
    padding: 14px 34px;
    font-size: 22px;
    font-weight: 800;
    font-family: inherit;
    cursor: pointer;
    background: var(--green);
    color: #fff;
    box-shadow: 0 5px 0 #3f9c3f;
    transition: transform .12s;
  }
  .check-btn:hover { transform: scale(1.06); }
  .check-btn:active { transform: translateY(3px); box-shadow: 0 2px 0 #3f9c3f; }
  .keyboard-hint {
    font-size: 14px;
    color: #666;
    background: #f3f6fb;
    border-radius: 12px;
    padding: 8px 14px;
  }

  /* ---------- finger tracing ---------- */
  .trace-area { display: none; flex-direction: column; align-items: center; gap: 12px; width: 100%; margin: 18px 0 8px; }
  .trace-letters { display: flex; gap: 8px; direction: ltr; justify-content: center; flex-wrap: wrap; }
  .trace-letter {
    width: 74px;
    height: 88px;
    border-radius: 16px;
    border: 4px dashed #b7c9e8;
    background: #eef4ff;
    color: #c7d3e8;
    font-size: 56px;
    font-weight: 900;
    display: flex;
    align-items: center;
    justify-content: center;
    user-select: none;
    -webkit-user-select: none;
    touch-action: none;
  }
  .trace-letter.current {
    border: 4px solid var(--orange);
    color: #f0b95e;
    animation: bounce .9s ease-in-out infinite;
  }
  .trace-letter.done {
    border: 4px solid var(--green);
    background: #e6f6e6;
    color: var(--green);
  }
  @keyframes bounce {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-5px); }
  }

  /* ---------- feedback ---------- */
  .feedback {
    font-size: 26px;
    font-weight: 900;
    min-height: 40px;
    margin: 8px 0 4px;
    text-align: center;
  }
  .feedback.good { color: #2e9e3f; }
  .feedback.bad { color: #d64545; }
  .shake { animation: shake .5s ease; }
  @keyframes shake {
    0%,100% { transform: translateX(0); }
    20% { transform: translateX(-10px); }
    40% { transform: translateX(10px); }
    60% { transform: translateX(-8px); }
    80% { transform: translateX(8px); }
  }
  .tricky {
    direction: ltr;
    font-size: 36px;
    font-weight: 900;
    letter-spacing: 5px;
    color: var(--ink);
    margin: 4px 0;
    text-align: center;
    display: none;
  }
  .tricky .hl {
    color: #fff;
    background: #ff6b6b;
    border-radius: 8px;
    padding: 0 6px;
  }
  .tip-box {
    display: none;
    margin-top: 6px;
    font-size: 15px;
    color: #2e9e3f;
    background: #e8f7e8;
    border-radius: 12px;
    padding: 8px 12px;
    text-align: center;
  }

  .hint-btn {
    border: none;
    border-radius: 999px;
    padding: 10px 18px;
    font-size: 17px;
    font-weight: 700;
    font-family: inherit;
    cursor: pointer;
    background: var(--purple);
    color: #fff;
    box-shadow: 0 5px 0 #7a56c9;
    transition: transform .12s;
    margin-top: 10px;
  }
  .hint-btn:hover { transform: scale(1.06); }
  .hint-btn:active { transform: translateY(3px); box-shadow: 0 2px 0 #7a56c9; }

  .word-show {
    direction: ltr;
    font-size: 52px;
    font-weight: 900;
    letter-spacing: 6px;
    color: var(--green);
    animation: popIn .4s ease;
  }

  /* ---------- confetti ---------- */
  .confetti-piece {
    position: fixed;
    top: -40px;
    font-size: 26px;
    z-index: 50;
    pointer-events: none;
    animation: fall linear forwards;
  }
  @keyframes fall {
    to { transform: translateY(110vh) rotate(720deg); opacity: .9; }
  }

  /* ---------- celebration ---------- */
  .stars-big { font-size: 70px; letter-spacing: 10px; margin: 10px 0; text-align: center; }
  .celeb-emoji { font-size: 110px; text-align: center; margin-bottom: 8px; }
  .celeb-title { font-size: 32px; font-weight: 900; text-align: center; color: var(--ink); }
  .celeb-sub { font-size: 18px; color: #555; text-align: center; margin: 6px 0 16px; line-height: 1.7; }

  .btn-row { display: flex; gap: 12px; justify-content: center; flex-wrap: wrap; }
  .big-btn {
    border: none;
    border-radius: 999px;
    padding: 15px 28px;
    font-size: 20px;
    font-weight: 800;
    font-family: inherit;
    cursor: pointer;
    color: #fff;
    box-shadow: 0 6px 0 rgba(0,0,0,.2);
    transition: transform .12s;
  }
  .big-btn:hover { transform: scale(1.07); }
  .big-btn:active { transform: translateY(3px); box-shadow: 0 2px 0 rgba(0,0,0,.2); }
  .btn-orange { background: var(--orange); box-shadow: 0 6px 0 #cc7c10; }
  .btn-green  { background: var(--green);  box-shadow: 0 6px 0 #3f9c3f; }
  .btn-sky    { background: var(--sky2);   box-shadow: 0 6px 0 #2f7fd1; }

  /* ---------- progress screen ---------- */
  .prog-level-row { display: flex; flex-direction: column; gap: 5px; padding: 12px 0; border-bottom: 1px dashed #dde6f5; }
  .prog-level-row:last-child { border-bottom: none; }
  .prog-top { display: flex; justify-content: space-between; align-items: center; font-weight: 800; }
  .prog-top small { color: #888; font-weight: 600; }
  .prog-pct { color: var(--green); font-weight: 900; }
  .review-chips { display: flex; flex-wrap: wrap; gap: 6px; margin-top: 4px; }
  .review-chip {
    direction: ltr;
    background: #ffe3e3;
    color: #d64545;
    font-weight: 800;
    font-size: 13px;
    border-radius: 99px;
    padding: 3px 10px;
  }
  .no-review { font-size: 13px; color: #2e9e3f; }
  .reset-row { margin-top: 16px; display: flex; justify-content: center; gap: 10px; flex-wrap: wrap; }
  .reset-btn {
    border: none; border-radius: 999px; padding: 10px 18px;
    font-size: 15px; font-weight: 700; font-family: inherit; cursor: pointer;
    background: #ff6b6b; color: #fff; box-shadow: 0 4px 0 #d64545;
  }

  .footer-note {
    margin-top: 20px;
    font-size: 13px;
    color: rgba(255,255,255,.9);
    text-align: center;
  }

  @media (max-width: 460px) {
    .slot, .tile { width: 54px; height: 64px; font-size: 32px; }
    .big-title { font-size: 34px; }
    .emoji-box { font-size: 90px; }
    .trace-letter { width: 62px; height: 74px; font-size: 46px; }
  }
  @media (max-width: 380px) {
    .slot, .tile { width: 46px; height: 56px; font-size: 27px; border-radius: 12px; }
    .slots, .tiles { gap: 6px; }
    .emoji-box { font-size: 74px; }
    .big-title { font-size: 28px; }
    .mode-btn { font-size: 12px; padding: 7px 10px; }
    .tap-hint { font-size: 12px; }
    .trace-letter { width: 52px; height: 64px; font-size: 40px; }
  }
</style>
</head>
<body>

<div class="floaties" id="floaties"></div>

<div class="app">
  <!-- ================= TOP BAR ================= -->
  <div class="topbar">
    <div class="brand"><span class="owl">🦉</span> املا آموز</div>
    <button class="home-btn" onclick="goHome()" title="خانه">🏠</button>
  </div>

  <!-- ================= HOME / LEVEL SELECT ================= -->
  <section id="screen-home" class="screen active">
    <h1 class="big-title">املا بساز! ✏️</h1>
    <p class="subtitle">یه سطح رو انتخاب کن و کلمه‌ها رو درست بنویس</p>

    <div class="card progress-card">
      <div class="overall-row">
        <span>📊 پیشرفت کل</span>
        <b id="overallPct">۰٪</b>
      </div>
      <div class="progress-wrap big"><div class="progress-bar" id="overallBar"></div></div>
      <button class="details-btn" onclick="showProgress()">🔁 جزئیات و کلمه‌های مرور</button>
    </div>

    <div class="card">
      <div class="level-grid" id="levelGrid"></div>
    </div>

    <div class="hint-text">
      🎯 مثل معلم‌های زبان: اول ببین، بعد بپوشون و از حفظ بنویس (👀 ببین/بنویس)<br>
      یا با گوش بشنو و بنویس (👂 بشنو/بنویس) یا با انگشت روی حرف‌ها بکش (✍️)<br>
      کلمه‌هایی که اشتباه بنویسی، دفعه‌ی بعد اول مرور می‌شن 💪
    </div>
  </section>

  <!-- ================= GAME ================= -->
  <section id="screen-game" class="screen">
    <div class="game-head">
      <div class="progress-wrap"><div class="progress-bar" id="progressBar"></div></div>
      <span class="game-count" id="wordCount"></span>
    </div>

    <div class="mode-toggle" id="modeToggle">
      <button class="mode-btn" data-mode="tiles" onclick="setMode('tiles')">🔤 حروف</button>
      <button class="mode-btn" data-mode="type" onclick="setMode('type')">⌨️ نوشتن</button>
      <button class="mode-btn" data-mode="cover" onclick="setMode('cover')">👀 ببین/بنویس</button>
      <button class="mode-btn" data-mode="dict" onclick="setMode('dict')">👂 بشنو/بنویس</button>
      <button class="mode-btn" data-mode="trace" onclick="setMode('trace')">✍️ انگشتی</button>
    </div>

    <div class="card word-card">
      <div class="emoji-box" id="emojiBox" onclick="speakWord()" title="برای شنیدن، روی عکس بزن"><span id="emoji">🐱</span><div class="shadow"></div></div>
      <div class="tap-hint" id="tapHint">👆 برای شنیدن کلمه، روی عکس یا دکمه 🔊 بزن</div>
      <button class="speak-btn" onclick="speakWord()">🔊 گوش کن</button>

      <div class="dict-msg" id="dictMsg">🤫 عکس پنهانه! با دکمه 🔊 گوش کن و بنویس</div>

      <!-- cover: look phase -->
      <div class="cover-look" id="coverLook">
        <div class="cover-word" id="coverWord">cat</div>
        <div class="cover-count" id="coverCount"></div>
        <button class="ready-btn" onclick="startCoverWrite()">✍️ آماده‌ام، بنویس!</button>
      </div>

      <!-- tiles mode -->
      <div class="slots" id="slots" dir="ltr"></div>
      <div class="tiles" id="tiles" dir="ltr"></div>

      <!-- typing / cover-write / dict -->
      <div class="type-area" id="typeArea">
        <input class="type-input" id="typeInput" dir="ltr" autocomplete="off" autocapitalize="off" spellcheck="false" placeholder="____">
        <button class="check-btn" onclick="evaluateTyped()">بررسی ✅</button>
        <div class="keyboard-hint" id="keyboardHint">⌨️ کلمه رو تایپ کن و دکمه «بررسی» رو بزن (یا Enter)</div>
      </div>

      <!-- finger tracing -->
      <div class="trace-area" id="traceArea">
        <div class="trace-letters" id="traceLetters" dir="ltr"></div>
        <div class="keyboard-hint">🖐️ با انگشت یا موس روی حرف درشت بکش تا رنگی بشه!</div>
      </div>

      <div class="feedback" id="feedback"></div>
      <div class="tricky" id="tricky"></div>
      <div class="tip-box" id="tipBox"></div>
      <button class="hint-btn" id="hintBtn" onclick="useHint()">💡 یه کمکی بده</button>
    </div>
  </section>

  <!-- ================= LEVEL COMPLETE ================= -->
  <section id="screen-done" class="screen">
    <div class="card" style="text-align:center;">
      <div class="celeb-emoji" id="doneEmoji">🏆</div>
      <div class="stars-big" id="doneStars"></div>
      <div class="celeb-title" id="doneTitle">آفرین! 🎉</div>
      <div class="celeb-sub" id="doneSub"></div>
      <div class="btn-row">
        <button class="big-btn btn-orange" onclick="restartLevel()">🔄 دوباره بازی کن</button>
        <button class="big-btn btn-green" id="nextLevelBtn" onclick="goNextLevel()">سطح بعدی ➡️</button>
        <button class="big-btn btn-sky" onclick="goHome()">🏠 سطح‌ها</button>
      </div>
    </div>
  </section>

  <!-- ================= PROGRESS ================= -->
  <section id="screen-progress" class="screen">
    <h1 class="big-title">پیشرفت من 📊</h1>
    <p class="subtitle">هر کلمه‌ای که اول‌بار درست بنویسی، مسلط می‌شه. اشتباهی‌ها می‌مونن تا دوباره تمرین کنی!</p>
    <div class="card">
      <div class="overall-row">
        <span>کل پیشرفت</span>
        <b id="progOverallPct">۰٪</b>
      </div>
      <div class="progress-wrap big"><div class="progress-bar" id="progOverallBar"></div></div>
      <div id="progLevels"></div>
      <div class="reset-row">
        <button class="big-btn btn-sky" onclick="goHome()">🏠 برگرد</button>
        <button class="reset-btn" onclick="resetAllProgress()">🗑️ پاک کردن پیشرفت</button>
      </div>
    </div>
  </section>

  <div class="footer-note">ساخته‌شده برای بچه‌های دوست‌داشتنی 💛</div>
</div>

<script>
"use strict";

/* =====================================================
   واژه‌نامه: از کلمه‌های ۳ حرفی تا کلمه‌های بلند
   ===================================================== */
const LEVELS = {
  3: [
    { w: "cat", e: "🐱" }, { w: "dog", e: "🐶" }, { w: "sun", e: "☀️" },
    { w: "hat", e: "👒" }, { w: "pig", e: "🐷" }, { w: "bus", e: "🚌" },
    { w: "cup", e: "☕" }, { w: "pen", e: "🖊️" }, { w: "fox", e: "🦊" },
    { w: "bee", e: "🐝" }, { w: "egg", e: "🥚" }, { w: "map", e: "🗺️" },
    { w: "key", e: "🔑" }, { w: "box", e: "📦" }, { w: "owl", e: "🦉" },
    { w: "ant", e: "🐜" }, { w: "cow", e: "🐮" }, { w: "hen", e: "🐔" },
    { w: "jet", e: "✈️" }, { w: "bed", e: "🛏️" }, { w: "bat", e: "🦇" },
    { w: "car", e: "🚗" }, { w: "toy", e: "🧸" }, { w: "ice", e: "🧊" },
    { w: "tea", e: "🍵" }, { w: "pie", e: "🥧" }, { w: "web", e: "🕸️" },
    { w: "net", e: "🥅" }, { w: "bag", e: "🎒" }, { w: "cap", e: "🧢" },
    { w: "arm", e: "💪" }, { w: "ear", e: "👂" }, { w: "leg", e: "🦵" },
    { w: "toe", e: "🦶" }, { w: "sky", e: "🌤️" }, { w: "run", e: "🏃" },
    { w: "fun", e: "🎢" }, { w: "kid", e: "🧒" }, { w: "ape", e: "🦧" },
    { w: "fly", e: "🪰" }, { w: "jar", e: "🫙" }, { w: "pan", e: "🍳" },
    { w: "can", e: "🥫" }, { w: "pin", e: "📌" }, { w: "eye", e: "👁️" },
    { w: "bow", e: "🎀" }, { w: "dot", e: "⚪" }, { w: "ham", e: "🍖" },
    { w: "hut", e: "⛺" }, { w: "lip", e: "👄" }, { w: "man", e: "👨" },
    { w: "sea", e: "🌊" }, { w: "tub", e: "🛁" }, { w: "axe", e: "🪓" },
    { w: "one", e: "1️⃣" }, { w: "two", e: "2️⃣" }, { w: "six", e: "6️⃣" },
    { w: "ten", e: "🔟" }, { w: "red", e: "🔴" }
  ],
  4: [
    { w: "fish", e: "🐟" }, { w: "bird", e: "🐦" }, { w: "star", e: "⭐" },
    { w: "moon", e: "🌙" }, { w: "book", e: "📖" }, { w: "tree", e: "🌳" },
    { w: "rain", e: "🌧️" }, { w: "cake", e: "🍰" }, { w: "milk", e: "🥛" },
    { w: "duck", e: "🦆" }, { w: "frog", e: "🐸" }, { w: "lion", e: "🦁" },
    { w: "hand", e: "✋" }, { w: "nose", e: "👃" }, { w: "kite", e: "🪁" },
    { w: "bell", e: "🔔" }, { w: "ball", e: "⚽" }, { w: "door", e: "🚪" },
    { w: "wolf", e: "🐺" }, { w: "pear", e: "🍐" }, { w: "seed", e: "🌱" },
    { w: "lamp", e: "💡" }, { w: "boat", e: "⛵" }, { w: "ship", e: "🚢" },
    { w: "king", e: "👑" }, { w: "ring", e: "💍" }, { w: "fire", e: "🔥" },
    { w: "snow", e: "❄️" }, { w: "leaf", e: "🍂" }, { w: "corn", e: "🌽" },
    { w: "bear", e: "🐻" }, { w: "deer", e: "🦌" }, { w: "goat", e: "🐐" },
    { w: "crab", e: "🦀" }, { w: "seal", e: "🦭" }, { w: "foot", e: "🦶" },
    { w: "face", e: "🙂" }, { w: "lamb", e: "🐑" }, { w: "pony", e: "🐎" },
    { w: "rock", e: "🪨" }, { w: "sand", e: "🏖️" }, { w: "wave", e: "🌊" },
    { w: "sing", e: "🎤" }, { w: "song", e: "🎵" }, { w: "drum", e: "🥁" },
    { w: "gold", e: "🥇" }, { w: "coin", e: "🪙" }, { w: "gift", e: "🎁" },
    { w: "mask", e: "🎭" }, { w: "soap", e: "🧼" }, { w: "soup", e: "🍜" },
    { w: "plum", e: "🍑" }, { w: "kiwi", e: "🥝" }, { w: "rice", e: "🍚" },
    { w: "taco", e: "🌮" }, { w: "baby", e: "👶" }, { w: "city", e: "🏙️" },
    { w: "dice", e: "🎲" }, { w: "five", e: "5️⃣" }, { w: "four", e: "4️⃣" },
    { w: "girl", e: "👧" }, { w: "home", e: "🏠" }, { w: "lock", e: "🔒" },
    { w: "nine", e: "9️⃣" }, { w: "time", e: "⏰" }, { w: "week", e: "📅" },
    { w: "wind", e: "🍃" }, { w: "play", e: "▶️" }, { w: "walk", e: "🚶" }
  ],
  5: [
    { w: "apple", e: "🍎" }, { w: "grape", e: "🍇" }, { w: "happy", e: "😊" },
    { w: "smile", e: "😄" }, { w: "house", e: "🏠" }, { w: "cloud", e: "☁️" },
    { w: "sheep", e: "🐑" }, { w: "horse", e: "🐴" }, { w: "mouse", e: "🐭" },
    { w: "chair", e: "🪑" }, { w: "clock", e: "🕐" }, { w: "robot", e: "🤖" },
    { w: "tiger", e: "🐯" }, { w: "candy", e: "🍬" }, { w: "lemon", e: "🍋" },
    { w: "water", e: "💧" }, { w: "panda", e: "🐼" }, { w: "pizza", e: "🍕" },
    { w: "bread", e: "🍞" }, { w: "sweet", e: "🍭" }, { w: "ghost", e: "👻" },
    { w: "snake", e: "🐍" }, { w: "train", e: "🚂" }, { w: "plane", e: "✈️" },
    { w: "watch", e: "⌚" }, { w: "phone", e: "📱" }, { w: "music", e: "🎵" },
    { w: "radio", e: "📻" }, { w: "paint", e: "🎨" }, { w: "brush", e: "🖌️" },
    { w: "paper", e: "📄" }, { w: "spoon", e: "🥄" }, { w: "plate", e: "🍽️" },
    { w: "juice", e: "🧃" }, { w: "honey", e: "🍯" }, { w: "melon", e: "🍈" },
    { w: "mango", e: "🥭" }, { w: "onion", e: "🧅" }, { w: "berry", e: "🫐" },
    { w: "donut", e: "🍩" }, { w: "fries", e: "🍟" }, { w: "salad", e: "🥗" },
    { w: "tomato", e: "🍅" }, { w: "beach", e: "🏖️" }, { w: "plant", e: "🪴" },
    { w: "ocean", e: "🌊" }, { w: "zebra", e: "🦓" }, { w: "shark", e: "🦈" },
    { w: "whale", e: "🐳" }, { w: "eagle", e: "🦅" }, { w: "crown", e: "👑" },
    { w: "laugh", e: "😂" }, { w: "hotdog", e: "🌭" }, { w: "eight", e: "8️⃣" },
    { w: "three", e: "3️⃣" }, { w: "seven", e: "7️⃣" }, { w: "hello", e: "👋" },
    { w: "teeth", e: "🦷" }, { w: "clown", e: "🤡" }, { w: "scarf", e: "🧣" },
    { w: "boots", e: "👢" }, { w: "shirt", e: "👕" }, { w: "jeans", e: "👖" },
    { w: "dress", e: "👗" }, { w: "glove", e: "🧤" }, { w: "socks", e: "🧦" },
    { w: "lunch", e: "🍱" }, { w: "tower", e: "🗼" }
  ],
  6: [
    { w: "banana", e: "🍌" }, { w: "orange", e: "🍊" }, { w: "school", e: "🏫" },
    { w: "window", e: "🪟" }, { w: "flower", e: "🌸" }, { w: "pencil", e: "✏️" },
    { w: "garden", e: "🏡" }, { w: "monkey", e: "🐵" }, { w: "rabbit", e: "🐰" },
    { w: "cherry", e: "🍒" }, { w: "turkey", e: "🦃" }, { w: "cookie", e: "🍪" },
    { w: "circle", e: "⭕" }, { w: "rocket", e: "🚀" }, { w: "planet", e: "🪐" },
    { w: "guitar", e: "🎸" }, { w: "pumpkin", e: "🎃" }, { w: "turtle", e: "🐢" },
    { w: "cheese", e: "🧀" }, { w: "butter", e: "🧈" }, { w: "burger", e: "🍔" },
    { w: "potato", e: "🥔" }, { w: "carrot", e: "🥕" }, { w: "pepper", e: "🌶️" },
    { w: "garlic", e: "🧄" }, { w: "coconut", e: "🥥" }, { w: "almond", e: "🌰" },
    { w: "coffee", e: "☕" }, { w: "bridge", e: "🌉" }, { w: "castle", e: "🏰" },
    { w: "forest", e: "🌲" }, { w: "island", e: "🏝️" }, { w: "camera", e: "📷" },
    { w: "pillow", e: "🛌" }, { w: "mirror", e: "🪞" }, { w: "basket", e: "🧺" },
    { w: "yellow", e: "💛" }, { w: "purple", e: "💜" }, { w: "parrot", e: "🦜" },
    { w: "spider", e: "🕷️" }, { w: "beetle", e: "🪲" }, { w: "insect", e: "🐛" },
    { w: "kitten", e: "🐱" }, { w: "autumn", e: "🍂" }, { w: "bubble", e: "🫧" },
    { w: "candle", e: "🕯️" }, { w: "hammer", e: "🔨" }, { w: "jacket", e: "🧥" },
    { w: "ladder", e: "🪜" }, { w: "number", e: "🔢" }, { w: "pickle", e: "🥒" },
    { w: "puzzle", e: "🧩" }, { w: "summer", e: "☀️" }, { w: "sunset", e: "🌇" },
    { w: "winter", e: "❄️" }, { w: "dragon", e: "🐉" }, { w: "police", e: "🚓" },
    { w: "wizard", e: "🧙" }
  ],
  7: [
    { w: "elephant", e: "🐘" }, { w: "butterfly", e: "🦋" }, { w: "umbrella", e: "☂️" },
    { w: "kangaroo", e: "🦘" }, { w: "octopus", e: "🐙" }, { w: "rainbow", e: "🌈" },
    { w: "dinosaur", e: "🦖" }, { w: "pineapple", e: "🍍" }, { w: "giraffe", e: "🦒" },
    { w: "watermelon", e: "🍉" }, { w: "helicopter", e: "🚁" }, { w: "caterpillar", e: "🐛" },
    { w: "strawberry", e: "🍓" }, { w: "blueberry", e: "🫐" }, { w: "crocodile", e: "🐊" },
    { w: "flamingo", e: "🦩" }, { w: "peacock", e: "🦚" }, { w: "squirrel", e: "🐿️" },
    { w: "hamster", e: "🐹" }, { w: "dolphin", e: "🐬" }, { w: "penguin", e: "🐧" },
    { w: "snowman", e: "⛄" }, { w: "volcano", e: "🌋" }, { w: "balloon", e: "🎈" },
    { w: "cupcake", e: "🧁" }, { w: "popcorn", e: "🍿" }, { w: "chocolate", e: "🍫" },
    { w: "icecream", e: "🍦" }, { w: "sandwich", e: "🥪" }, { w: "pancake", e: "🥞" },
    { w: "mountain", e: "⛰️" }, { w: "airplane", e: "✈️" }, { w: "alphabet", e: "🔤" },
    { w: "astronaut", e: "🧑‍🚀" }, { w: "basketball", e: "🏀" }, { w: "bicycle", e: "🚲" },
    { w: "birthday", e: "🎂" }, { w: "calendar", e: "📅" }, { w: "fireworks", e: "🎆" },
    { w: "football", e: "⚽" }, { w: "hospital", e: "🏥" }, { w: "mushroom", e: "🍄" },
    { w: "necklace", e: "📿" }, { w: "princess", e: "👸" }, { w: "skeleton", e: "💀" },
    { w: "sunflower", e: "🌻" }, { w: "telephone", e: "☎️" }, { w: "telescope", e: "🔭" },
    { w: "television", e: "📺" }, { w: "thunder", e: "⛈️" }, { w: "unicorn", e: "🦄" },
    { w: "vampire", e: "🧛" }
  ]
};

const TILE_COLORS = ["#ff7eb3", "#ff9f1c", "#6ac96a", "#4fa3f7", "#b388ff", "#ff6b6b", "#00c2a8"];
const LABELS = { 3: "۳ حرفی", 4: "۴ حرفی", 5: "۵ حرفی", 6: "۶ حرفی", 7: "حرفه‌ای ✨" };
const COLORS = { 3: "c3", 4: "c4", 5: "c5", 6: "c6", 7: "c7" };

const $ = (id) => document.getElementById(id);

/* ===================== persistent store ===================== */
let store = loadStore();
function loadStore() {
  let s;
  try { s = JSON.parse(localStorage.getItem("emla_amoz_store") || "null"); } catch (e) { s = null; }
  if (!s) {
    let old = {};
    try { old = JSON.parse(localStorage.getItem("emla_amoz_progress") || "{}"); } catch (e) { old = {}; }
    s = { stars: old, mastered: {}, review: {} };
    try { localStorage.removeItem("emla_amoz_progress"); } catch (e) { /* ignore */ }
  }
  s.stars = s.stars || {};
  s.mastered = s.mastered || {};
  s.review = s.review || {};
  return s;
}
function persistStore() {
  try { localStorage.setItem("emla_amoz_store", JSON.stringify(store)); } catch (e) { /* full */ }
}
function addToReview(w) {
  const lv = currentLevel;
  store.review[lv] = (store.review[lv] || []).filter(x => x !== w);
  store.review[lv].push(w);
  store.mastered[lv] = (store.mastered[lv] || []).filter(x => x !== w);
  persistStore();
}
function markMastered(w) {
  const lv = currentLevel;
  store.mastered[lv] = (store.mastered[lv] || []).filter(x => x !== w);
  store.mastered[lv].push(w);
  store.review[lv] = (store.review[lv] || []).filter(x => x !== w);
  persistStore();
}
function saveStars(lv, stars) {
  store.stars[lv] = Math.max(store.stars[lv] || 0, stars);
  persistStore();
}

/* ===================== state ===================== */
let currentLevel = 3;
let queue = [];       // کلمه‌های این دور (مرورها اول می‌آن)
let queuePos = 0;
let currentWord = null;
let mode = "tiles";   // tiles | type | cover | dict | trace
let coverStep = "look";   // look | write
let coverTimer = null;
let dictRevealed = false;
let traceIdx = 0;
let traceInk = 0;
let requeued = new Set();
let mistakes = 0;
let hintsUsed = 0;
let celebrating = false;

/* ===================== audio ===================== */
let audioCtx = null;
function beep(freq, dur, type = "sine", vol = 0.15) {
  try {
    audioCtx = audioCtx || new (window.AudioContext || window.webkitAudioContext)();
    const o = audioCtx.createOscillator();
    const g = audioCtx.createGain();
    o.type = type;
    o.frequency.value = freq;
    g.gain.setValueAtTime(vol, audioCtx.currentTime);
    g.gain.exponentialRampToValueAtTime(0.001, audioCtx.currentTime + dur);
    o.connect(g); g.connect(audioCtx.destination);
    o.start(); o.stop(audioCtx.currentTime + dur);
  } catch (err) { /* no audio, no problem */ }
}
function goodSound()  { beep(660, .15); setTimeout(() => beep(880, .2), 120); }
function badSound()   { beep(180, .3, "square", .08); }
function winSound()   { [523,659,784,1047].forEach((f,i) => setTimeout(() => beep(f,.25), i*150)); }

function speakWord() {
  try {
    const u = new SpeechSynthesisUtterance(currentWord.w);
    u.lang = "en-US";
    u.rate = 0.8;
    speechSynthesis.cancel();
    speechSynthesis.speak(u);
  } catch (err) { /* unsupported */ }
}

/* ===================== helpers ===================== */
function shuffle(arr) {
  const a = arr.slice();
  for (let i = a.length - 1; i > 0; i--) {
    const j = Math.floor(Math.random() * (i + 1));
    [a[i], a[j]] = [a[j], a[i]];
  }
  return a;
}

/* نکته‌های املایی — مثل معلم‌ها که الگوهای کلمه رو یاد می‌دن */
function wordTip(w) {
  const tips = [];
  const rep = w.match(/(.)\1/);
  if (rep) tips.push("یادت باشه: حرف «" + rep[1] + "» توی «" + w + "» دوبار اومده!");
  if (w.endsWith("e") && w.length > 3) tips.push("نکته: «e» آخر بی‌صدا (silent e) ولی حتماً نوشته می‌شه!");
  if (w.includes("ck")) tips.push("صدای «ک» آخرش با ck نوشته می‌شه!");
  if (w.includes("sh")) tips.push("«sh» با هم صدای «ش» می‌دن!");
  if (w.includes("ch")) tips.push("«ch» با هم صدای «چ» می‌دن!");
  if (w.includes("th")) tips.push("«th» با هم صدای «ث» می‌دن!");
  if (w.includes("ee")) tips.push("«ee» صدای بلند «ای» می‌ده!");
  if (w.includes("oo")) tips.push("«oo» صدای «او» می‌ده!");
  if (w.includes("ai")) tips.push("«ai» صدای «ای» می‌ده!");
  if (w.includes("ay")) tips.push("«ay» صدای «ای» می‌ده!");
  if (w.includes("qu")) tips.push("«q» همیشه با «u» می‌اد!");
  if (w.includes("ph")) tips.push("«ph» صدای «ف» می‌ده!");
  if (w.includes("kn")) tips.push("توی «" + w + "» حرف «k» بی‌صداست!");
  return tips[0] || "";
}

/* حرف‌هایی که اشتباه نوشته شده رو قرمز می‌کنه (تحلیل خطا) */
function highlightDiff(correct, attempt) {
  return correct.split("").map((ch, i) => {
    return attempt[i] === ch ? ch : "<span class='hl'>" + ch + "</span>";
  }).join("");
}

/* ===================== screens ===================== */
function showScreen(name) {
  document.querySelectorAll(".screen").forEach(s => s.classList.remove("active"));
  $("screen-" + name).classList.add("active");
}

function goHome() {
  buildLevelGrid();
  showScreen("home");
}

function renderOverall() {
  let total = 0, mastered = 0;
  Object.keys(LEVELS).forEach(n => {
    total += LEVELS[n].length;
    mastered += (store.mastered[n] || []).filter(w => LEVELS[n].some(x => x.w === w)).length;
  });
  const pct = total ? Math.round(mastered / total * 100) : 0;
  $("overallPct").textContent = pct + "٪";
  $("overallBar").style.width = pct + "%";
}

function buildLevelGrid() {
  const grid = $("levelGrid");
  grid.innerHTML = "";
  Object.keys(LEVELS).forEach((lv, i) => {
    const n = Number(lv);
    const total = LEVELS[n].length;
    const mastered = (store.mastered[n] || []).filter(w => LEVELS[n].some(x => x.w === w)).length;
    const review = (store.review[n] || []).filter(w => LEVELS[n].some(x => x.w === w));
    const pct = Math.round(mastered / total * 100);
    const stars = store.stars[n] || 0;
    const btn = document.createElement("button");
    btn.className = "level-btn " + COLORS[n] + (pct === 100 ? " done" : "");
    btn.innerHTML =
      '<span class="lvl-num">' + n + '</span>' +
      '<span class="lvl-label">' + LABELS[n] + ' (' + total + ' کلمه)</span>' +
      '<span class="lvl-bar"><i style="width:' + pct + '%"></i></span>' +
      '<span class="lvl-meta"><b>' + pct + '٪</b>' +
        '<span class="lvl-stars">' + "⭐".repeat(stars) + '</span>' +
        (review.length ? '<span class="lvl-review-badge">🔁 ' + review.length + '</span>' : "") +
      '</span>';
    btn.onclick = () => startLevel(n);
    grid.appendChild(btn);
    setTimeout(() => {
      btn.style.opacity = "0";
      btn.style.transform = "translateY(14px)";
      btn.style.transition = "opacity .4s ease, transform .4s ease";
      requestAnimationFrame(() => {
        btn.style.opacity = "1";
        btn.style.transform = "none";
      });
    }, i * 80);
  });
  renderOverall();
}

/* ===================== level flow ===================== */
function startLevel(lv) {
  currentLevel = lv;
  const all = LEVELS[lv];
  const review = (store.review[lv] || []).filter(w => all.some(x => x.w === w));
  const masteredSet = new Set((store.mastered[lv] || []).filter(w => all.some(x => x.w === w)));
  const rest = all.filter(x => !masteredSet.has(x.w) && !review.includes(x.w));
  // کلمه‌های مرور اول میان (مرور فاصله‌دار)
  queue = shuffle(review.map(w => all.find(x => x.w === w))).concat(shuffle(rest));
  if (queue.length === 0) queue = shuffle(all.map(x => ({ ...x })));
  queuePos = 0;
  requeued = new Set();
  clearInterval(coverTimer);
  $("nextLevelBtn").style.display = LEVELS[lv + 1] ? "" : "none";
  document.querySelectorAll(".mode-btn").forEach(b => b.classList.toggle("active", b.dataset.mode === mode));
  showScreen("game");
  nextWord();
}

function nextWord() {
  if (queuePos >= queue.length) return levelComplete();
  currentWord = queue[queuePos];
  queuePos++;
  $("emoji").textContent = currentWord.e;
  $("progressBar").style.width = (queuePos / queue.length * 100) + "%";
  $("wordCount").textContent = queuePos + " / " + queue.length;
  setupCurrentWord();
}

function setupCurrentWord() {
  mistakes = 0;
  hintsUsed = 0;
  dictRevealed = false;
  clearInterval(coverTimer);
  $("feedback").textContent = "";
  $("feedback").className = "feedback";
  $("tricky").innerHTML = "";
  $("tricky").style.display = "none";
  $("tipBox").textContent = "";
  $("tipBox").style.display = "none";
  $("hintBtn").style.display = (mode === "tiles" || mode === "type") ? "" : "none";
  $("typeInput").value = "";
  if (mode === "tiles") setupTiles();
  if (mode === "cover") startCoverLook();
  if (mode === "dict") setupDict();
  if (mode === "trace") setupTrace();
  renderMode();
}

function levelComplete() {
  let stars = 3;
  if (hintsUsed > 0) stars = Math.min(stars, 2);
  if (mistakes > 0)  stars = Math.min(stars, 2);
  if (hintsUsed > 0 && mistakes > 0) stars = 1;
  saveStars(currentLevel, stars);
  winSound();
  confetti();
  $("progressBar").style.width = "100%";
  $("doneEmoji").textContent = stars === 3 ? "🏆" : stars === 2 ? "🎖️" : "💪";
  $("doneTitle").textContent = stars === 3 ? "عالی بود! تو قهرمانی! 🏆" : "آفرین! دوباره تمرین کن تا ۳ ستاره بگیری 💪";
  $("doneStars").textContent = "⭐".repeat(stars) + "☆".repeat(3 - stars);
  const all = LEVELS[currentLevel];
  const masteredN = (store.mastered[currentLevel] || []).filter(w => all.some(x => x.w === w)).length;
  const reviewN = (store.review[currentLevel] || []).filter(w => all.some(x => x.w === w)).length;
  $("doneSub").innerHTML = LABELS[currentLevel] + " رو مرور کردی — " + masteredN + " کلمه از " + all.length + " رو مسلط شدی!" +
    (reviewN ? "<br>🔁 " + reviewN + " کلمه مونده تا دفعه‌ی بعد اول مرور بشن" : "");
  showScreen("done");
}

function restartLevel() { startLevel(currentLevel); }
function goNextLevel()  { startLevel(currentLevel + 1); }

/* ===================== tiles mode ===================== */
function setupTiles() {
  const letters = currentWord.w.split("");
  slotsFilled = new Array(letters.length).fill(null);
  lettersLeft = shuffle(letters.slice());
  renderTiles();
}

let slotsFilled = [];
let lettersLeft = [];

function renderTiles() {
  const slotsEl = $("slots");
  const tilesEl = $("tiles");
  slotsEl.innerHTML = "";
  tilesEl.innerHTML = "";
  slotsFilled.forEach((ch, i) => {
    const s = document.createElement("div");
    s.className = "slot" + (ch ? " filled" : "");
    s.onclick = () => unplace(i);
    if (ch) { const sp = document.createElement("span"); sp.className = "letter"; sp.textContent = ch; s.appendChild(sp); }
    slotsEl.appendChild(s);
  });
  lettersLeft.forEach((ch, i) => {
    if (ch === null) return;   // حرفی که قبلاً جای‌گذاری شده
    const t = document.createElement("button");
    t.className = "tile";
    t.textContent = ch;
    t.style.background = TILE_COLORS[i % TILE_COLORS.length];
    t.onclick = () => place(i);
    tilesEl.appendChild(t);
  });
}

function place(tileIdx) {
  const empty = slotsFilled.indexOf(null);
  if (empty === -1) return;
  slotsFilled[empty] = lettersLeft[tileIdx];
  lettersLeft[tileIdx] = null;
  beep(500, .08, "triangle", .08);
  renderTiles();
  if (!slotsFilled.includes(null)) checkAnswer();
}

function unplace(slotIdx) {
  const ch = slotsFilled[slotIdx];
  if (!ch) return;
  slotsFilled[slotIdx] = null;
  lettersLeft[lettersLeft.indexOf(null)] = ch;
  beep(400, .06, "triangle", .06);
  renderTiles();
}

function useHint() {
  hintsUsed++;
  if (mode === "type") {
    const ch = currentWord.w[0];
    $("typeInput").value = ch;
    $("typeInput").focus();
    beep(700, .12, "sine", .1);
    return;
  }
  if (slotsFilled.includes(null)) {
    const firstEmpty = slotsFilled.indexOf(null);
    const idx = lettersLeft.indexOf(currentWord.w[firstEmpty]);
    if (idx !== -1) {
      slotsFilled[firstEmpty] = lettersLeft[idx];
      lettersLeft[idx] = null;
      beep(700, .12, "sine", .1);
      renderTiles();
      if (!slotsFilled.includes(null)) checkAnswer();
    }
  }
}

function checkAnswer() {
  const word = slotsFilled.join("");
  if (word === currentWord.w) {
    goodSound();
    celebrate(true);
  } else {
    badSound();
    mistakes++;
    addToReview(currentWord.w);
    requeueWord();
    const slotsEl = $("slots");
    slotsEl.classList.remove("shake");
    void slotsEl.offsetWidth;
    slotsEl.classList.add("shake");
    const fb = $("feedback");
    fb.className = "feedback bad";
    fb.textContent = "🙈 اوه نه! به حرف قرمز دقت کن:";
    $("tricky").innerHTML = highlightDiff(currentWord.w, word);
    $("tricky").style.display = "block";
    setTimeout(() => {
      slotsFilled = new Array(currentWord.w.length).fill(null);
      lettersLeft = shuffle(currentWord.w.split(""));
      renderTiles();
    }, 900);
  }
}

/* ===================== typing / cover / dict ===================== */
function evaluateTyped() {
  const val = $("typeInput").value.trim().toLowerCase();
  if (!val) return;
  if (val === currentWord.w) {
    goodSound();
    if (mode === "dict") dictRevealed = true;
    celebrate(true);
  } else {
    badSound();
    mistakes++;
    addToReview(currentWord.w);
    requeueWord();
    const inp = $("typeInput");
    inp.classList.remove("shake");
    void inp.offsetWidth;
    inp.classList.add("shake");
    const fb = $("feedback");
    fb.className = "feedback bad";
    $("tricky").innerHTML = highlightDiff(currentWord.w, val);
    $("tricky").style.display = "block";
    if (mode === "dict") {
      dictRevealed = true;
      fb.textContent = "🙈 اوه نه! به این حرف‌ها دقت کن:";
      $("emojiBox").style.display = "block";
      speakWord();
    } else if (mode === "cover") {
      fb.textContent = "🙈 نزدیک بود! دوباره خوب نگاه کن:";
      speakWord();
      setTimeout(startCoverLook, 1000);
    } else {
      fb.textContent = "🙈 اوه نه! دوباره تلاش کن";
    }
    inp.value = "";
    if (mode !== "cover") inp.focus();
  }
}

function setMode(m) {
  mode = m;
  document.querySelectorAll(".mode-btn").forEach(b => b.classList.toggle("active", b.dataset.mode === m));
  if (currentWord) setupCurrentWord();
}

/* ----- cover: ببین، بپوشون، بنویس، چک کن ----- */
function startCoverLook() {
  coverStep = "look";
  clearInterval(coverTimer);
  $("coverWord").textContent = currentWord.w;
  let t = 6;
  $("coverCount").textContent = "بعد " + t + " ثانیه پنهان می‌شه...";
  coverTimer = setInterval(() => {
    t--;
    if (t <= 0) { clearInterval(coverTimer); startCoverWrite(); }
    else $("coverCount").textContent = "بعد " + t + " ثانیه پنهان می‌شه...";
  }, 1000);
  renderMode();
}

function startCoverWrite() {
  coverStep = "write";
  clearInterval(coverTimer);
  $("feedback").textContent = "✍️ حالا از حفظ بنویس!";
  $("feedback").className = "feedback good";
  renderMode();
  $("typeInput").value = "";
  $("typeInput").focus();
}

/* ----- dict: بشنو و بنویس ----- */
function setupDict() {
  dictRevealed = false;
  renderMode();
  $("feedback").textContent = "";
  $("feedback").className = "feedback";
}

/* ===================== trace: ردیابی با انگشت ===================== */
function setupTrace() {
  traceIdx = 0;
  traceInk = 0;
  const box = $("traceLetters");
  box.innerHTML = "";
  currentWord.w.split("").forEach((ch, i) => {
    const d = document.createElement("div");
    d.className = "trace-letter" + (i === 0 ? " current" : "");
    d.textContent = ch;
    d.setAttribute("data-i", i);
    box.appendChild(d);
  });
  const letters = [...box.children];
  letters.forEach((el, i) => {
    let pressed = false, lastX = 0, lastY = 0;
    el.addEventListener("pointerdown", (e) => {
      e.preventDefault();
      pressed = true;
      lastX = e.clientX; lastY = e.clientY;
      try { el.setPointerCapture(e.pointerId); } catch (err) { /* ok */ }
    });
    el.addEventListener("pointerup", () => { pressed = false; });
    el.addEventListener("pointercancel", () => { pressed = false; });
    el.addEventListener("pointermove", (e) => {
      if (!pressed || i !== traceIdx) return;
      const dx = Math.abs(e.clientX - lastX);
      const dy = Math.abs(e.clientY - lastY);
      lastX = e.clientX; lastY = e.clientY;
      traceInk += Math.min(30, dx + dy);
      if (traceInk > 220) {
        el.classList.remove("current");
        el.classList.add("done");
        beep(600, .1, "triangle", .1);
        traceIdx++;
        traceInk = 0;
        if (traceIdx >= currentWord.w.length) {
          traceDone();
        } else {
          letters[traceIdx].classList.add("current");
        }
      }
    });
  });
}

function traceDone() {
  goodSound();
  speakWord();
  celebrate(false);
}

/* ===================== render by mode ===================== */
function renderMode() {
  const isTiles = mode === "tiles";
  const isType = mode === "type";
  const isCover = mode === "cover";
  const isDict = mode === "dict";
  const isTrace = mode === "trace";
  $("slots").style.display = isTiles ? "flex" : "none";
  $("tiles").style.display = isTiles ? "flex" : "none";
  $("typeArea").style.display = (isType || isDict || (isCover && coverStep === "write")) ? "flex" : "none";
  $("coverLook").style.display = (isCover && coverStep === "look") ? "flex" : "none";
  $("traceArea").style.display = isTrace ? "flex" : "none";
  $("dictMsg").style.display = isDict ? "block" : "none";
  $("emojiBox").style.display = (isDict && !dictRevealed) ? "none" : "block";
  $("tapHint").textContent =
    isDict ? "👂 با دکمه 🔊 چند بار گوش کن، بعد بنویس!" :
    isCover ? "👀 اول خوب نگاه کن و با دکمه 🔊 بشنو" :
    "👆 برای شنیدن کلمه، روی عکس یا دکمه 🔊 بزن";
  $("keyboardHint").textContent =
    isDict ? "👂 هرچند بار که خواستی گوش کن و بعد از حفظ بنویس" :
    isCover ? "✍️ کلمه‌ای که دیدی رو از حفظ بنویس" :
    "⌨️ کلمه رو تایپ کن و دکمه «بررسی» رو بزن (یا Enter)";
  if (isType || isDict || (isCover && coverStep === "write")) {
    setTimeout(() => $("typeInput").focus(), 60);
  }
}

/* ===================== celebration ===================== */
function celebrate(showWord) {
  if (celebrating) return;
  celebrating = true;
  $("hintBtn").style.display = "none";
  const fb = $("feedback");
  fb.className = "feedback good";
  fb.innerHTML = "آفرین! 🎉 درسته: <span class='word-show'>" + currentWord.w + "</span>";
  if (mistakes === 0 && hintsUsed === 0) markMastered(currentWord.w);
  const tip = wordTip(currentWord.w);
  if (tip) {
    $("tipBox").textContent = "🔎 " + tip;
    $("tipBox").style.display = "block";
  } else {
    $("tipBox").style.display = "none";
  }
  confetti();
  if (showWord) speakWord();
  setTimeout(() => {
    celebrating = false;
    nextWord();
  }, 1900);
}

function confetti() {
  const emojis = ["⭐", "🎉", "🎈", "🌟", "💛", "✨", "🍬", "🎊"];
  for (let i = 0; i < 28; i++) {
    const p = document.createElement("div");
    p.className = "confetti-piece";
    p.textContent = emojis[Math.floor(Math.random() * emojis.length)];
    p.style.left = Math.random() * 100 + "vw";
    p.style.fontSize = (18 + Math.random() * 26) + "px";
    p.style.animationDuration = (1.4 + Math.random() * 1.6) + "s";
    p.style.animationDelay = (Math.random() * 0.4) + "s";
    document.body.appendChild(p);
    setTimeout(() => p.remove(), 3500);
  }
}

/* کلمه‌ی اشتباه: یک‌بار دیگه هم تو همین دور تکرار می‌شه */
function requeueWord() {
  if (!requeued.has(currentWord.w)) {
    requeued.add(currentWord.w);
    queue.push({ ...currentWord });
  }
}

/* ===================== progress screen ===================== */
function showProgress() {
  let total = 0, mastered = 0;
  const rows = [];
  Object.keys(LEVELS).forEach(n => {
    const totalN = LEVELS[n].length;
    const masteredN = (store.mastered[n] || []).filter(w => LEVELS[n].some(x => x.w === w)).length;
    const reviewN = (store.review[n] || []).filter(w => LEVELS[n].some(x => x.w === w));
    total += totalN;
    mastered += masteredN;
    const pct = Math.round(masteredN / totalN * 100);
    rows.push(
      '<div class="prog-level-row">' +
        '<div class="prog-top"><span>' + LABELS[n] + '</span><small>' + masteredN + ' از ' + totalN + ' کلمه</small></div>' +
        '<div class="progress-wrap"><div class="progress-bar" style="width:' + pct + '%"></div></div>' +
        '<div class="prog-top"><span class="prog-pct">' + pct + '٪</span></div>' +
        '<div class="review-chips">' +
          (reviewN.length
            ? reviewN.map(w => '<span class="review-chip">' + w + '</span>').join("")
            : '<span class="no-review">✅ کلمه‌ای برای مرور نیست</span>') +
        '</div>' +
      '</div>'
    );
  });
  $("progLevels").innerHTML = rows.join("");
  const pct = total ? Math.round(mastered / total * 100) : 0;
  $("progOverallPct").textContent = pct + "٪";
  $("progOverallBar").style.width = pct + "%";
  showScreen("progress");
}

function resetAllProgress() {
  if (!confirm("همه‌ی پیشرفت‌ها و ستاره‌ها پاک بشه؟")) return;
  try { localStorage.removeItem("emla_amoz_store"); } catch (e) { /* ignore */ }
  store = loadStore();
  goHome();
}

/* ===================== boot ===================== */
(function initFloaties() {
  const emojis = ["☁️", "⭐", "🎈", "🌈", "🦋", "☀️", "✨"];
  const wrap = $("floaties");
  for (let i = 0; i < 8; i++) {
    const f = document.createElement("div");
    f.className = "floaty";
    f.textContent = emojis[i % emojis.length];
    f.style.left = Math.random() * 100 + "vw";
    f.style.animationDuration = (14 + Math.random() * 16) + "s";
    f.style.animationDelay = (Math.random() * 12) + "s";
    wrap.appendChild(f);
  }
})();

$("typeInput").addEventListener("keydown", (e) => {
  if (e.key === "Enter") { e.preventDefault(); evaluateTyped(); }
});
$("typeInput").addEventListener("input", () => {
  $("typeInput").value = $("typeInput").value.toLowerCase();
});

buildLevelGrid();
</script>
</body>
</html>
