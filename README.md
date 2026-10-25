# Mgbday2
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#fff0f5">
<title>For Masaba 💗</title>
<style>
:root{--pink:#ff6f9f;--rose:#d93f72;--soft:#fff0f5;--ink:#5b2438;--cream:#fffaf8}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{margin:0;font-family:Georgia,'Times New Roman',serif;color:var(--ink);background:linear-gradient(180deg,#fff4f8,#fffaf8 50%,#ffe9f0);overflow-x:hidden}
button{font:inherit;cursor:pointer}
.hero{min-height:100svh;display:flex;align-items:center;justify-content:center;text-align:center;padding:28px 18px;position:relative;isolation:isolate;overflow:hidden;background:radial-gradient(circle at 50% 20%,#fff 0,#fff1f6 40%,#ffdce8 100%)}
.hero:before,.hero:after{content:"";position:absolute;width:250px;height:250px;border-radius:50%;background:#ffb9d0;filter:blur(70px);opacity:.55;z-index:-1;animation:glow 7s ease-in-out infinite alternate}
.hero:before{top:-80px;left:-60px}.hero:after{right:-70px;bottom:-80px;background:#ffc5d6;animation-delay:2s}
@keyframes glow{to{transform:scale(1.3);opacity:.8}}
.hero-content{max-width:760px;position:relative}
.eyebrow{letter-spacing:.22em;text-transform:uppercase;font:600 .72rem Arial,sans-serif;color:#b84b71}
h1{font-size:clamp(3.4rem,12vw,7.5rem);line-height:.98;margin:18px 0;color:#c6386b;font-weight:500;text-shadow:0 8px 28px #f9b8ce80}
.subtitle{font-size:clamp(1.15rem,3.5vw,1.55rem);line-height:1.65;max-width:600px;margin:20px auto}
.primary,.secondary{border:0;border-radius:999px;padding:15px 25px;margin:8px;box-shadow:0 8px 22px #d93f7225;transition:transform .2s,box-shadow .2s}
.primary{background:linear-gradient(135deg,#ed5b8d,#c92d65);color:white}.secondary{background:#fff;color:#b42f61;border:1px solid #f4b2c9}
.primary:hover,.secondary:hover{transform:translateY(-3px);box-shadow:0 12px 28px #d93f7235}
.scroll-note{font: .75rem Arial,sans-serif;letter-spacing:.12em;margin-top:34px;color:#a85b76}
section{padding:78px 18px;max-width:1000px;margin:auto}
.section-label{text-transform:uppercase;letter-spacing:.2em;font:600 .7rem Arial,sans-serif;color:#c45179;text-align:center}
h2{text-align:center;font-weight:500;font-size:clamp(2rem,6vw,3.3rem);margin:12px 0 22px;color:#b82e60}
.lead{text-align:center;max-width:690px;margin:0 auto 30px;line-height:1.8;font-size:1.08rem}
.card{background:#ffffffc9;border:1px solid #f7c8d8;border-radius:24px;padding:24px;box-shadow:0 14px 45px #bd4a7210}
.timeline{display:grid;gap:16px;max-width:760px;margin:30px auto}
.memory{display:grid;grid-template-columns:105px 1fr;gap:16px;align-items:start;background:#fffafc;border:1px solid #f8d0dd;border-radius:18px;padding:18px}
.year{font-size:1.35rem;color:#d34175}.memory p{margin:6px 0 0;line-height:1.65}
.gallery{display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin-top:25px}
.photo{min-height:190px;border:2px dashed #e9a5bc;border-radius:18px;background:linear-gradient(145deg,#fff,#ffe5ef);display:flex;align-items:center;justify-content:center;text-align:center;padding:12px;overflow:hidden;position:relative;color:#a54a6c;font: .9rem Arial,sans-serif}
.photo img{width:100%;height:100%;object-fit:cover;position:absolute;inset:0}
.photo span{position:relative;background:#fffaf0c9;border-radius:12px;padding:8px}
.upload-help{text-align:center;font: .86rem Arial,sans-serif;line-height:1.7;color:#92536a;margin-top:16px}
.letter{max-width:760px;margin:auto;font-size:1.12rem;line-height:1.95;white-space:pre-line}
.signature{font-style:italic;color:#c6386b;font-size:1.3rem;margin-top:24px}
.gift-wrap{text-align:center;max-width:700px;margin:auto}
.gift{font-size:6rem;border:0;background:transparent;filter:drop-shadow(0 10px 10px #db699044);animation:bob 2.2s ease-in-out infinite}
@keyframes bob{50%{transform:translateY(-10px) rotate(2deg)}}
.hidden{display:none!important}
.reveal{margin:22px auto 0;max-width:620px;animation:appear .8s ease both}
@keyframes appear{from{opacity:0;transform:translateY(15px)}to{opacity:1;transform:translateY(0)}}
.cake{font-size:5rem;margin:12px}
.final-card{max-width:760px;margin:auto;text-align:center;padding:34px 24px;background:linear-gradient(145deg,#fff,#ffe6ef);border:1px solid #f3b6cb;border-radius:28px}
.final-line{font-size:clamp(1.35rem,4vw,2rem);line-height:1.55;margin:20px 0}
footer{text-align:center;padding:30px 18px 45px;color:#a85b76;font-size:.9rem}
.heart{position:fixed;bottom:-30px;z-index:5;pointer-events:none;animation:floatUp linear forwards;opacity:.8}
@keyframes floatUp{to{transform:translateY(-110vh) rotate(35deg);opacity:0}}
.sparkle{position:absolute;pointer-events:none;color:#e76c98;animation:twinkle 2s infinite alternate}
@keyframes twinkle{to{opacity:.25;transform:scale(.7)}}
.music-note{font: .82rem Arial,sans-serif;color:#99506a;margin-top:12px}
@media(max-width:620px){.gallery{grid-template-columns:1fr 1fr}.photo{min-height:145px}.memory{grid-template-columns:78px 1fr;padding:14px}.hero{min-height:92svh}section{padding:58px 16px}}
@media(prefers-reduced-motion:reduce){*,*:before,*:after{animation-duration:.01ms!important;scroll-behavior:auto!important}}
</style>
</head>
<body>
<header class="hero" id="top">
  <span class="sparkle" style="top:18%;left:15%;font-size:2rem">✧</span>
  <span class="sparkle" style="top:25%;right:13%;font-size:1.5rem;animation-delay:.8s">✦</span>
  <div class="hero-content">
    <div class="eyebrow">A little world made just for you</div>
    <h1>Happy Birthday,<br>Masaba <span aria-label="heart">♡</span></h1>
    <p class="subtitle">To my favourite person — may your day feel as soft, beautiful, and magical as the happiness you bring into my life.</p>
    <button class="primary" onclick="document.getElementById('story').scrollIntoView({behavior:'smooth'})">Open your surprise 💌</button>
    <div class="music-note">A little birthday melody is waiting below ♫</div>
    <div class="scroll-note">MADE WITH LOVE · JUST FOR YOU</div>
  </div>
</header>

<section id="story">
  <div class="section-label">Our little universe</div>
  <h2>Somehow, it was always you</h2>
  <p class="lead">Some people become part of your story so naturally that, one day, you realise they have become one of your favourite chapters.</p>
  <div class="timeline">
    <article class="memory"><div class="year">2018 ♡</div><div><strong>The beginning</strong><p>The year our paths crossed — a small beginning to a story that means so much to me now.</p></div></article>
    <article class="memory"><div class="year">2020 ✨</div><div><strong>Knowing you, little by little</strong><p>The year I started getting to know you better, and every new little thing made you more special to me.</p></div></article>
    <article class="memory"><div class="year">28.10.2021 🤝</div><div><strong>A hand I'll always remember</strong><p>The first time I held your hand. One little moment, held close in my heart for a very long time.</p></div></article>
    <article class="memory"><div class="year">Forever 🌷</div><div><strong>My favourite ongoing chapter</strong><p>Still learning you, still growing with you, and still hoping for a lifetime of ordinary days that feel extraordinary because we're together.</p></div></article>
  </div>
</section>

<section id="photos">
  <div class="section-label">Little pieces of forever</div>
  <h2>Our memories, our magic</h2>
  <p class="lead">This space is for the smiles, silly moments, celebrations, and photographs that only we can fully understand.</p>
  <div class="gallery">
    <label class="photo"><input type="file" accept="image/*" hidden onchange="loadPhoto(this,0)"><span>＋ Add our favourite photo</span><img id="photo0" class="hidden" alt="Our favourite memory"></label>
    <label class="photo"><input type="file" accept="image/*" hidden onchange="loadPhoto(this,1)"><span>＋ Add a happy memory</span><img id="photo1" class="hidden" alt="A happy memory"></label>
    <label class="photo"><input type="file" accept="image/*" hidden onchange="loadPhoto(this,2)"><span>＋ Add a photo that feels like home</span><img id="photo2" class="hidden" alt="A memory that feels like home"></label>
  </div>
  <p class="upload-help">Personalise before sharing: tap each frame to choose a photo. For the published website, add your chosen photos to the website folder and replace these frames with the image files, or send me the photos and I can help prepare that version.</p>
</section>

<section id="letter">
  <div class="section-label">From my heart to yours</div>
  <h2>A letter for Masaba</h2>
  <div class="card letter">Happy Birthday, my favourite person. 💗

I hope today reminds you of how loved, precious, and wonderfully you are. I wish I could wrap every good thing in the world into one gift and place it in your hands.

Thank you for being you. Thank you for the little moments, the laughter, the comfort, and the way your presence can make an ordinary day feel special. Every year, I find new reasons to be grateful that our paths crossed.

I hope this new chapter brings you peace when life feels heavy, courage when things feel uncertain, laughter that makes your cheeks hurt, and dreams that come true one by one. I hope you always see in yourself the beautiful person I get to see.

And as life keeps changing, I hope we keep learning, growing, and collecting memories together — one birthday, one silly moment, one ordinary day at a time.

Today is your day, Masaba. Make a wish, smile that beautiful smile, and remember that someone is cheering for your happiness with all his heart.

<div class="signature">Happy Birthday, my love. Always. ♡</div></div>
</section>

<section id="gift">
  <div class="section-label">One last little surprise</div>
  <h2>There's a gift for you 🎁</h2>
  <div class="gift-wrap card">
    <p class="lead">Close your eyes for a second, make a birthday wish, and then tap the gift.</p>
    <button class="gift" aria-label="Open birthday gift" onclick="openGift()">🎁</button>
    <div><button class="primary" onclick="openGift()">Open your gift</button></div>
    <div id="giftReveal" class="reveal hidden">
      <div class="cake">🎂</div>
      <h2 style="font-size:2rem">Make a wish, Masaba!</h2>
      <p class="lead">I hope every candle brings you a little more joy, every new day brings you a reason to smile, and every dream you carry finds its way to you.</p>
      <button class="secondary" onclick="blowCandles()">Blow out the candles ✨</button>
      <p id="candleMessage" class="hidden">Wish sent to the universe. May it be kind to you. 💫</p>
    </div>
  </div>
</section>

<section id="forever">
  <div class="final-card">
    <div class="section-label">And if you remember just one thing…</div>
    <div class="final-line">You are my home. ❤️<br>My favourite place is wherever you are.<br>And if I could choose again, I would still choose you.</div>
    <p class="lead">Happy Birthday, Masaba. Here's to your dreams, your happiness, and all the beautiful chapters still waiting for us.</p>
    <button class="primary" onclick="makeHearts(40)">One more hug, from me to you ♡</button>
  </div>
</section>

<section style="padding-top:10px">
  <div class="gift-wrap">
    <button class="secondary" id="musicButton" onclick="toggleMusic()">♫ Play a little melody</button>
    <p class="music-note">Music starts only when you press play. This page creates a gentle little tune in your browser; no external audio file needed.</p>
  </div>
</section>
<footer>Made with all my heart, for Masaba · 2 November ♡</footer>

<script>
function makeHearts(count=12){
  const chars=['♡','♥','ღ','✿'];
  for(let i=0;i<count;i++){
    const el=document.createElement('span');el.className='heart';el.textContent=chars[Math.floor(Math.random()*chars.length)];
    el.style.left=Math.random()*100+'vw';el.style.fontSize=(14+Math.random()*25)+'px';el.style.color=['#ec5d91','#d93f72','#ff9fbd'][Math.floor(Math.random()*3)];
    el.style.animationDuration=(4+Math.random()*5)+'s';document.body.appendChild(el);setTimeout(()=>el.remove(),9500);
  }
}
setInterval(()=>makeHearts(2),1800);
function openGift(){document.getElementById('giftReveal').classList.remove('hidden');makeHearts(24);document.getElementById('giftReveal').scrollIntoView({behavior:'smooth',block:'center'});}
function blowCandles(){document.getElementById('candleMessage').classList.remove('hidden');makeHearts(30);}
function loadPhoto(input,index){const file=input.files&&input.files[0];if(!file)return;const img=document.getElementById('photo'+index);img.src=URL.createObjectURL(file);img.classList.remove('hidden');input.parentElement.querySelector('span').classList.add('hidden');}
let audioCtx=null, musicTimer=null, musicOn=false, noteIndex=0;
const notes=[523.25,659.25,783.99,659.25,587.33,698.46,880,698.46,523.25,659.25,783.99,1046.5];
function toggleMusic(){
 const btn=document.getElementById('musicButton');
 if(musicOn){clearInterval(musicTimer);musicOn=false;btn.textContent='♫ Play a little melody';if(audioCtx)audioCtx.suspend();return;}
 const AC=window.AudioContext||window.webkitAudioContext;
 if(!AC){btn.textContent='Music is not supported in this browser';return;}
 audioCtx=audioCtx||new AC();audioCtx.resume();musicOn=true;btn.textContent='Ⅱ Pause the melody';
 const playNote=()=>{if(!musicOn)return;const osc=audioCtx.createOscillator(),gain=audioCtx.createGain();osc.type='sine';osc.frequency.value=notes[noteIndex%notes.length];gain.gain.setValueAtTime(.0001,audioCtx.currentTime);gain.gain.exponentialRampToValueAtTime(.06,audioCtx.currentTime+.03);gain.gain.exponentialRampToValueAtTime(.0001,audioCtx.currentTime+.42);osc.connect(gain);gain.connect(audioCtx.destination);osc.start();osc.stop(audioCtx.currentTime+.45);noteIndex++;};
 playNote();musicTimer=setInterval(playNote,480);
}
</script>
</body>
</html>
