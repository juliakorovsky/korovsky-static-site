---
title: "Обо мне"
layout: "page"
---

<div id="about-real">
<p>Добро пожаловать! Это Коровски, конкретно отбитая личность. Саркастичная, честная, тупая, как скотина, местами умная. Раньше раздражала редактора научно-популярного журнала, теперь бешу ML-инженеров (TTS) и нейросети. И периодически — тренеров по плаванию и скейтбордингу. В свободное время печатает буковки на экране.</p>

<p>Welcome! This is Korovsky, a genuinely unhinged person. Sarcastic, honest, stupid as fuck, smart around the edges. Previously annoyed an editor of a popular science magazine, now annoys ML engineers (TTS) and neural networks. And occasionally — swimming and skateboarding coaches. Also puts letters on screens in her free time.</p>
</div>

<div id="about-hr" style="display:none">
<p>Высокомотивированный ML-специалист с подтверждённым опытом достижения результатов. Увлечена применением передовых технологий для создания инновационных решений и межфункционального взаимодействия. Командный игрок с развитыми коммуникативными навыками и проактивным мышлением. Ориентирована на результат.</p>

<p>Highly motivated and results-driven ML professional with a proven track record of delivering impactful solutions. Passionate about leveraging cutting-edge technologies to drive innovation and cross-functional synergy. A dedicated team player with exceptional communication skills and a growth mindset. Committed to excellence.</p>
</div>

<button id="hr-btn" onclick="toggleHR()" style="margin-top:1rem;cursor:pointer">Я HR / I'm HR</button>

<script>
function toggleHR() {
  const real = document.getElementById('about-real');
  const hr = document.getElementById('about-hr');
  const btn = document.getElementById('hr-btn');
  const isHR = hr.style.display === 'none';
  real.style.display = isHR ? 'none' : '';
  hr.style.display = isHR ? '' : 'none';
  btn.textContent = isHR ? 'Я не HR / I\'m not HR' : 'Я HR / I\'m HR';
}
</script>
