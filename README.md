<svg viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg">
  <style>
    .title {
      font: bold 40px monospace;
      fill: url(#grad);
    }
    .subtitle {
      font: 20px monospace;
      fill: #fff;
    }
    .wave {
      animation: waveMove 6s linear infinite;
    }
    @keyframes waveMove {
      from { transform: translateX(0); }
      to { transform: translateX(-200); }
    }
    .fade {
      animation: fadeCycle 9s infinite;
    }
    @keyframes fadeCycle {
      0%,33%   { opacity: 1; }
      34%,100% { opacity: 0; }
    }
    .fade2 {
      animation: fadeCycle2 9s infinite;
    }
    @keyframes fadeCycle2 {
      0%,33%   { opacity: 0; }
      34%,66%  { opacity: 1; }
      67%,100% { opacity: 0; }
    }
    .fade3 {
      animation: fadeCycle3 9s infinite;
    }
    @keyframes fadeCycle3 {
      0%,66%   { opacity: 0; }
      67%,100% { opacity: 1; }
    }
  </style>

  <!-- Gradient -->
  <defs>
    <linearGradient id="grad" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#06b6d4"/>
      <stop offset="50%" stop-color="#7c3aed"/>
      <stop offset="100%" stop-color="#ef4444"/>
    </linearGradient>
  </defs>

  <!-- Background Waves -->
  <g fill="#1e293b">
    <path class="wave" d="M0 120 Q 40 100 80 120 T 160 120 T 240 120 T 320 120 T 400 120 T 480 120 T 560 120 T 640 120 T 720 120 T 800 120 V200 H0 Z"/>
    <path class="wave" d="M0 140 Q 40 160 80 140 T 160 140 T 240 140 T 320 140 T 400 140 T 480 140 T 560 140 T 640 140 T 720 140 T 800 140 V200 H0 Z" fill="#334155"/>
  </g>

  <!-- Main Title -->
  <text x="50" y="80" class="title">Remanshu Sharma</text>

  <!-- Cycling Subtitles -->
  <text x="50" y="120" class="subtitle fade">Data Science Enthusiast</text>
  <text x="50" y="120" class="subtitle fade2">Artificial Intelligence Explorer</text>
  <text x="50" y="120" class="subtitle fade3">IIT Patna Learner</text>
</svg>
<h1 align="center">Hi 👋, I'm Remanshu</h1>
<h3 align="center">✨ I craft stories from data while exploring the world of AI. From Metallurgy at IIT Patna to Machine Learning, my journey is about turning raw information into meaningful insights.</h3>

<h3 align="left">Connect with me:</h3>
<p align="left">
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> <a href="https://www.tensorflow.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/> </a> </p>
