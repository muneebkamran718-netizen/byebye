 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For Khadijah ♡</title>

<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,500;0,600;1,400;1,500&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet">

<style>
* { box-sizing: border-box; }

:root {
  --cream: #fff9e9;
  --yellow: #f3d875;
  --brown: #65533b;
}

body {
  margin: 0;
  background: var(--cream);
  color: var(--brown);
  font-family: 'DM Sans', sans-serif;
}

.screen {
  display: none;
  min-height: 100svh;
  padding: 45px 24px;
  align-items: center;
  justify-content: center;
  position: relative;
  overflow: hidden;
}

.screen.active {
  display: flex;
  animation: appear .8s ease both;
}

@keyframes appear {
  from { opacity: 0; transform: translateY(12px); }
  to { opacity: 1; transform: translateY(0); }
}

.screen::before {
  content: "";
  position: absolute;
  inset: 12px;
  border: 1px solid #d9c28b80;
  pointer-events: none;
}

.corner {
  position: absolute;
  font-size: 12px;
  letter-spacing: 2px;
  top: 35px;
  left: 35px;
}

.heart {
  position: absolute;
  right: 35px;
  top: 30px;
  font-size: 22px;
  color: #b99b56;
}

.content {
  width: min(100%, 470px);
  text-align: center;
  z-index: 1;
}

.eyebrow {
  font-size: 10px;
  letter-spacing: 4px;
  text-transform: uppercase;
  opacity: .7;
}

h1, h2 {
  font-family: 'Cormorant Garamond', serif;
  font-weight: 400;
}

h1 {
  font-size: clamp(45px, 10vw, 68px);
  line-height: .98;
  margin: 22px 0;
}

h2 {
  font-size: clamp(35px, 8vw, 48px);
  margin: 15px 0;
}

.subtitle {
  font-family: 'Cormorant Garamond', serif;
  font-style: italic;
  font-size: 20px;
}

.flower-button {
  border: none;
  background: transparent;
  cursor: pointer;
  display: block;
  margin: 28px auto 10px;
  padding: 0;
  transition: transform .4s ease;
}

.flower-button:hover {
  transform: scale(1.08) rotate(-5deg);
}

.flower {
  width: 190px;
  max-width: 55vw;
  filter: drop-shadow(0 12px 10px #8b6a2720);
  animation: sway 4s ease-in-out infinite;
}

@keyframes sway {
  0%,100% { transform: rotate(-3deg); }
  50% { transform: rotate(3deg); }
}

.hint {
  font-size: 10px;
  letter-spacing: 3px;
  text-transform: uppercase;
  margin-top: 20px;
  opacity: .7;
}

.message {
  font-family: 'Cormorant Garamond', serif;
  font-size: 21px;
  line-height: 1.75;
  white-space: pre-wrap;
  text-align: left;
  margin: 25px auto;
  max-width: 390px;
  min-height: 80px;
  outline-color: #d9c28b;
}

.message:empty::before {
  content: attr(data-placeholder);
  color: #aa987e;
  font-style: italic;
}

.next {
  border: 1px solid #b9a26c;
  background: transparent;
  color: var(--brown);
  padding: 13px 25px;
  letter-spacing: 1px;
  font-size: 11px;
  cursor: pointer;
  margin-top: 15px;
}

.next:hover { background: #f4e7bf; }

.divider {
  width: 55px;
  height: 1px;
  background: #c6ac70;
  margin: 22px auto;
}

.letter {
  text-align: left;
  background: #fffdf5;
  padding: 24px;
  border: 1px solid #e8d9b7;
  box-shadow: 0 15px 45px #8b6a270c;
}

.letter .message { margin: 0; }

.song {
  margin-top: 25px;
  background: #f7edcf;
  border: 1px solid #ead9a7;
  padding: 20px;
  text-align: left;
}

.song-title {
  font-family: 'Cormorant Garamond', serif;
  font-size: 24px;
}

.song-subtitle {
  font-size: 11px;
  opacity: .7;
  margin: 5px 0 15px;
  overflow-wrap: anywhere;
}

audio {
  width: 100%;
  height: 38px;
}

.back {
  display: inline-block;
  margin-top: 25px;
  border: none;
  background: none;
  color: var(--brown);
  cursor: pointer;
  font-size: 12px;
}

.petal {
  position: absolute;
  color: #d9b85e;
  opacity: .6;
  pointer-events: none;
}

.p1 { top: 20%; left: 9%; font-size: 20px; }
.p2 { bottom: 19%; right: 10%; font-size: 24px; }
.p3 { top: 35%; right: 8%; font-size: 13px; }
.p4 { bottom: 30%; left: 10%; font-size: 15px; }

@media(max-height: 700px) {
  .flower { width: 140px; }
  h1 { margin: 12px 0; }
  .flower-button { margin-top: 15px; }
}
</style>
</head>

<body>

<!-- SUNFLOWER ILLUSTRATION -->
<svg width="0" height="0" style="position:absolute">
<defs>
  <g id="sunflower">
    <path d="M100 105 Q104 160 96 220"
      stroke="#6d8751" stroke-width="5" fill="none"
      stroke-linecap="round"/>
    <path d="M99 165 Q58 130 48 163 Q69 183 99 165"
      fill="#819968"/>
    <path d="M98 187 Q130 149 147 177 Q126 198 98 187"
      fill="#91a36d"/>
    <g fill="#f4d46d" stroke="#dfb54b" stroke-width="1.5">
      <ellipse cx="100" cy="47" rx="17" ry="34"/>
      <ellipse cx="100" cy="47" rx="17" ry="34" transform="rotate(30 100 100)"/>
      <ellipse cx="100" cy="47" rx="17" ry="34" transform="rotate(60 100 100)"/>
      <ellipse cx="100" cy="47" rx="17" ry="34" transform="rotate(90 100 100)"/>
      <ellipse cx="100" cy="47" rx="17" ry="34" transform="rotate(120 100 100)"/>
      <ellipse cx="100" cy="47" rx="17" ry="34" transform="rotate(150 100 100)"/>
      <ellipse cx="100" cy="47" rx="17" ry="34" transform="rotate(180 100 100)"/>
      <ellipse cx="100" cy="47" rx="17" ry="34" transform="rotate(210 100 100)"/>
      <ellipse cx="100" cy="47" rx="17" ry="34" transform="rotate(240 100 100)"/>
      <ellipse cx="100" cy="47" rx="17" ry="34" transform="rotate(270 100 100)"/>
      <ellipse cx="100" cy="47" rx="17" ry="34" transform="rotate(300 100 100)"/>
      <ellipse cx="100" cy="47" rx="17" ry="34" transform="rotate(330 100 100)"/>
    </g>
    <circle cx="100" cy="100" r="29" fill="#684323"/>
    <circle cx="100" cy="100" r="23" fill="#80552d"/>
    <g fill="#d3a34d">
      <circle cx="89" cy="90" r="2"/>
      <circle cx="101" cy="86" r="2"/>
      <circle cx="111" cy="94" r="2"/>
      <circle cx="91" cy="105" r="2"/>
      <circle cx="105" cy="108" r="2"/>
      <circle cx="115" cy="108" r="2"/>
      <circle cx="99" cy="97" r="2"/>
      <circle cx="85" cy="98" r="2"/>
      <circle cx="105" cy="119" r="2"/>
      <circle cx="95" cy="116" r="2"/>
    </g>
  </g>
</defs>
</svg>

<!-- SCREEN 1: CLICK THE FLOWER -->
<section class="screen active" id="screen1">
  <span class="corner">a little something</span>
  <span class="heart">♡</span>
  <span class="petal p1">✳</span>
  <span class="petal p2">✧</span>
  <span class="petal p3">♡</span>
  <span class="petal p4">✳</span>

  <div class="content">
    <p class="eyebrow">made just for you</p>
    <h1>A little<br><i>something.</i></h1>
    <p class="subtitle">For Khadijah ♡</p>

    <button class="flower-button"
      onclick="goTo(2)" aria-label="Open the flower">
      <svg class="flower" viewBox="0 0 200 230">
        <use href="#sunflower"/>
      </svg>
    </button>

    <p class="hint">click the flower to begin ↓</p>
  </div>
</section>

<!-- SCREEN 2: YOUR APOLOGY -->
<section class="screen" id="screen2">
  <span class="corner">for khadijah</span>
  <span class="heart">♡</span>
  <span class="petal p1">✧</span>
  <span class="petal p2">♡</span>

  <div class="content">
    <p class="eyebrow">something i need to say</p>

    <!-- CHANGE THIS HEADING -->
    <h2 contenteditable="true">Your heading here</h2>

    <!-- WRITE YOUR APOLOGY HERE -->
    <div class="message" contenteditable="true"
      data-placeholder="Write your apology here..."
      style="text-align:center"
      id="apology"></div>

    <div class="divider"></div>

    <button class="flower-button" onclick="goTo(3)"
      aria-label="Continue to the next flower">
      <svg class="flower" style="width:105px"
        viewBox="0 0 200 230">
        <use href="#sunflower"/>
      </svg>
    </button>

    <p class="hint">there's a little more ↓</p>
  </div>
</section>

<!-- SCREEN 3: FLOWER, PARAGRAPH & SONG -->
<section class="screen" id="screen3">
  <span class="corner">one more thing</span>
  <span class="heart">♡</span>
  <span class="petal p1">✳</span>
  <span class="petal p2">✧</span>

  <div class="content">
    <p class="eyebrow">a little letter</p>

    <!-- CHANGE THIS TITLE -->
    <h2 contenteditable="true">A little letter for you</h2>

    <button class="flower-button" onclick="revealLetter()"
      aria-label="Open your letter">
      <svg class="flower" style="width:125px"
        viewBox="0 0 200 230">
        <use href="#sunflower"/>
      </svg>
    </button>

    <p class="hint" id="letterHint">click this flower ♡</p>

    <div id="letterContent" hidden>
      <div class="letter">
        <!-- WRITE YOUR PARAGRAPH HERE -->
        <div class="message" contenteditable="true"
          data-placeholder="Write your personal paragraph here..."
          id="paragraph"></div>
      </div>

      <div class="song">
        <div class="song-title">A song for you ♡</div>

        <div class="song-subtitle">
          King — She Don't Give A (Explicit) |
          The Carnival | Prod. by Satyam HCR
        </div>

        <!-- THE MP3 MUST BE UPLOADED TO YOUR REPOSITORY ROOT -->
        <audio controls preload="metadata">
          <source
            src="King%20-%20She%20Don%27t%20Give%20A%20%28Explicit%29%20%EF%BD%9C%20The%20Carnival%20%EF%BD%9C%20Prod.%20by%20Satyam%20HCR%20%EF%BD%9C%20Latest%20Songs%202020.mp3"
            type="audio/mpeg">
          Your browser does not support audio.
        </audio>
      </div>
    </div>

    <button class="back" onclick="goTo(1)">↶ start again</button>
  </div>
</section>

<script>
function goTo(number) {
  document.querySelectorAll('.screen').forEach(screen => {
    screen.classList.remove('active');
  });

  document.getElementById('screen' + number).classList.add('active');
  window.scrollTo({ top: 0, behavior: 'smooth' });
}

function revealLetter() {
  document.getElementById('letterContent').hidden = false;
  document.getElementById('letterHint').textContent = '♡';
}
</script>

</body>
</html>
