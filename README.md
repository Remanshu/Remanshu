<h1 align="center">Hi 👋, I'm Remanshu</h1>
<h3 align="center">✨ I craft stories from data while exploring the world of AI. From Metallurgy at IIT Patna to Machine Learning, my journey is about turning raw information into meaningful insights.</h3>

<h3 align="left">Connect with me:</h3>
<p align="left">
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> <a href="https://www.tensorflow.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/> </a> </p>
<!--
File: github-profile-animation.html
Type: Single-file HTML with an animated SVG suitable for converting to an .svg for use in your GitHub README.
Usage:
 1. Open this file in a browser to preview the animation.
 2. To use in your GitHub README, extract the <svg>...</svg> content, save it as profile-anim.svg in your repository (e.g., /assets/profile-anim.svg), and reference it in your README.md like:

    ![Profile Animation](./assets/profile-anim.svg)

 Notes:
 - GitHub supports embedding SVGs from the same repo via raw links or relative paths.
 - If GitHub strips scripts/styles from SVGs for security, the CSS animations used here are inline within the SVG and should work when saved as an .svg file.
 - If anything behaves oddly, let me know and I can produce an SVG-only file optimized for README embedding.
-->

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>GitHub Profile Animation — Preview</title>
  <style>
    html,body{height:100%;margin:0;background:#0f1724;display:flex;align-items:center;justify-content:center;font-family:Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial}
    .frame{width:900px;max-width:95%;border-radius:12px;padding:18px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));box-shadow:0 6px 30px rgba(2,6,23,0.6);}
    .note{color:#9aa4bf;font-size:13px;margin-top:10px;text-align:center}
    .center{display:flex;align-items:center;justify-content:center}
    a{color:#7dd3fc}
  </style>
</head>
<body>
  <div class="frame">
    <!-- Interactive preview area; the SVG inside is what you should extract for README usage -->
    <div class="center">
      <!-- Begin SVG animation -->
      <svg id="profile-anim" viewBox="0 0 900 240" width="900" height="240" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Animated GitHub profile banner">
        <defs>
          <linearGradient id="g1" x1="0" x2="1" y1="0" y2="0">
            <stop offset="0%" stop-color="#06b6d4"/>
            <stop offset="40%" stop-color="#7c3aed"/>
            <stop offset="100%" stop-color="#ef4444"/>
          </linearGradient>

          <filter id="fBlur" x="-40%" y="-40%" width="180%" height="180%">
            <feGaussianBlur stdDeviation="8" result="b" />
            <feBlend in="SourceGraphic" in2="b" mode="screen" />
          </filter>

          <filter id="shadow" x="-50%" y="-50%" width="200%" height="200%">
            <feDropShadow dx="0" dy="6" stdDeviation="12" flood-color="#000" flood-opacity="0.45" />
          </filter>

          <mask id="fadeMask">
            <linearGradient id="maskgrad" x1="0" x2="0" y1="0" y2="1">
              <stop offset="0%" stop-color="#fff" stop-opacity="1"/>
              <stop offset="100%" stop-color="#fff" stop-opacity="0.15"/>
            </linearGradient>
            <rect x="0" y="0" width="900" height="240" fill="url(#maskgrad)" />
          </mask>

          <g id="particle">
            <circle r="6" fill="#fff" opacity="0.9" />
            <circle r="3" fill="#fff" opacity="0.25" transform="translate(6, -6)" />
          </g>
        </defs>

        <!-- Background subtle wave -->
        <g mask="url(#fadeMask)">
          <path id="wave" d="M0 160 C 150 90 350 220 540 140 C 700 80 900 180 900 180 L900 240 L0 240 Z" fill="url(#g1)" opacity="0.14">
            <animate attributeName="d" dur="8s" repeatCount="indefinite"
              values="M0 160 C 150 90 350 220 540 140 C 700 80 900 180 900 180 L900 240 L0 240 Z;
                      M0 150 C 140 80 320 230 540 150 C 720 70 900 160 900 160 L900 240 L0 240 Z;
                      M0 160 C 150 90 350 220 540 140 C 700 80 900 180 900 180 L900 240 L0 240 Z"/>
          </path>

          <!-- floating particles -->
          <g transform="translate(60,40)" opacity="0.95">
            <use href="#particle">
              <animateTransform attributeName="transform" type="translate" dur="12s" repeatCount="indefinite" values="0 0; 80 -30; 0 0"/>
              <animate attributeName="opacity" values="0.95;0.2;0.95" dur="6s" repeatCount="indefinite"/>
            </use>
          </g>

          <g transform="translate(260,20)" opacity="0.85">
            <use href="#particle">
              <animateTransform attributeName="transform" type="translate" dur="10s" repeatCount="indefinite" values="0 0; -60 20; 0 0"/>
              <animate attributeName="opacity" values="0.85;0.15;0.85" dur="5s" repeatCount="indefinite"/>
            </use>
          </g>

          <g transform="translate(520,60)" opacity="0.88">
            <use href="#particle">
              <animateTransform attributeName="transform" type="translate" dur="14s" repeatCount="indefinite" values="0 0; 40 40; 0 0"/>
              <animate attributeName="opacity" values="0.88;0.2;0.88" dur="7s" repeatCount="indefinite"/>
            </use>
          </g>

          <g transform="translate(820,20)" opacity="0.9">
            <use href="#particle">
              <animateTransform attributeName="transform" type="translate" dur="11s" repeatCount="indefinite" values="0 0; -50 -20; 0 0"/>
              <animate attributeName="opacity" values="0.9;0.2;0.9" dur="5.5s" repeatCount="indefinite"/>
            </use>
          </g>
        </g>

        <!-- Profile card bubble -->
        <g transform="translate(24,28)">
          <rect x="0" y="0" rx="14" ry="14" width="360" height="184" fill="#071029" stroke="rgba(255,255,255,0.03)"/>

          <!-- avatar circle -->
          <g transform="translate(28,28)">
            <circle cx="44" cy="44" r="44" fill="#0b1220" stroke="url(#g1)" stroke-width="2" filter="url(#shadow)" />
            <!-- stylized avatar initials -->
            <text x="44" y="52" text-anchor="middle" font-size="34" font-weight="700" font-family="Inter, Arial" fill="white">RS</text>
          </g>

          <!-- name & subtitle -->
          <g transform="translate(112,44)">
            <text x="0" y="14" font-size="20" font-weight="700" fill="#e6eef8">Remanshu Sharma</text>
            <text x="0" y="42" font-size="12" fill="#9fb0d6">Data Science • AI • IIT Patna</text>

            <!-- typing subtitle animation -->
            <g transform="translate(0,70)">
              <text id="typing" x="0" y="0" font-size="12.5" font-family="Inter, Arial" fill="#bfe9ff"></text>
              <rect id="cursor" x="0" y="-10" width="2" height="16" fill="#bfe9ff">
                <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
              </rect>
            </g>

            <!-- small skill chips -->
            <g transform="translate(0,104)">
              <rect x="0" y="0" rx="8" ry="8" width="86" height="24" fill="#052036" stroke="rgba(190,233,255,0.06)" />
              <text x="12" y="16" font-size="11" fill="#8ed3f7">Python</text>

              <rect x="96" y="0" rx="8" ry="8" width="82" height="24" fill="#052036" stroke="rgba(190,233,255,0.06)" />
              <text x="108" y="16" font-size="11" fill="#caa7ff">Machine Learning</text>

              <rect x="188" y="0" rx="8" ry="8" width="78" height="24" fill="#052036" stroke="rgba(190,233,255,0.06)" />
              <text x="200" y="16" font-size="11" fill="#9fe9a8">Data Viz</text>
            </g>
          </g>
        </g>

        <!-- animated code-like panel to the right -->
        <g transform="translate(400,22)">
          <rect x="0" y="0" rx="12" ry="12" width="460" height="196" fill="#021026" stroke="rgba(255,255,255,0.03)"/>

          <!-- header dots -->
          <g transform="translate(12,12)">
            <circle cx="8" cy="8" r="6" fill="#ff726f"/>
            <circle cx="28" cy="8" r="6" fill="#ffd76b"/>
            <circle cx="48" cy="8" r="6" fill="#8af27e"/>
          </g>

          <!-- animated lines -->
          <g transform="translate(18,40)" fill-opacity="0.9">
            <rect x="0" y="0" rx="6" ry="6" width="360" height="10" fill="#0b2240">
              <animate attributeName="width" dur="3.6s" values="0;340;0" repeatCount="indefinite"/>
            </rect>
            <rect x="0" y="22" rx="6" ry="6" width="260" height="10" fill="#0b2238">
              <animate attributeName="width" dur="4.2s" values="0;240;0" repeatCount="indefinite"/>
            </rect>
            <rect x="0" y="44" rx="6" ry="6" width="180" height="10" fill="#0b2232">
              <animate attributeName="width" dur="2.8s" values="0;160;0" repeatCount="indefinite"/>
            </rect>
            <rect x="0" y="66" rx="6" ry="6" width="220" height="10" fill="#0b2238">
              <animate attributeName="width" dur="5s" values="0;200;0" repeatCount="indefinite"/>
            </rect>
          </g>

          <!-- small graph -->
          <g transform="translate(300,120)">
            <polyline points="0,36 12,20 24,28 36,12 48,18 60,8 72,18 84,12 96,20" fill="none" stroke="url(#g1)" stroke-width="3" stroke-linecap="round" stroke-linejoin="round">
              <animate attributeName="stroke-dasharray" dur="4s" values="0,200;200,0" repeatCount="indefinite"/>
            </polyline>
          </g>
        </g>

        <!-- footer small tagline -->
        <g transform="translate(24,220)">
          <text x="0" y="14" font-size="11" fill="#95b2d6">Crafting clean models • Visual stories • Open-source experiments</text>
        </g>

        <!-- invisible text used by JS typing script inside HTML preview only -->
        <foreignObject x="0" y="0" width="1" height="1">
          <div xmlns="http://www.w3.org/1999/xhtml" style="display:none" id="typing-phrases">Data-driven decisions;Explainable AI;End-to-end projects;IIT Patna</div>
        </foreignObject>

      </svg>
      <!-- End SVG animation -->
    </div>

    <div class="note">Preview in browser. To embed in README, save the above SVG as <code>profile-anim.svg</code> inside your repo and reference it with a relative path.</div>
  </div>

  <script>
    // Typing effect only active in the HTML preview (JS removed in pure SVG file to be README-safe).
    (function(){
      try{
        const phrases = document.getElementById('typing-phrases').textContent.split(';');
        const textEl = document.querySelector('#profile-anim #typing');
        const cursor = document.querySelector('#profile-anim #cursor');
        if(!textEl) return;
        let pi = 0, ci = 0, typing=true;
        function step(){
          const phrase = phrases[pi%phrases.length].trim();
          if(typing){
            textEl.textContent = phrase.slice(0, ci+1);
            cursor.setAttribute('x', String(8* (ci+1)) );
            ci++;
            if(ci>=phrase.length){typing=false;setTimeout(step,1200);return}
            setTimeout(step,80);
          } else {
            textEl.textContent = phrase.slice(0, ci-1);
            cursor.setAttribute('x', String(8* (ci-1)) );
            ci--;
            if(ci<=0){typing=true;pi++;setTimeout(step,250);return}
            setTimeout(step,40);
          }
        }
        step();
      }catch(e){/* silent */}
    })();
  </script>
</body>
</html>
