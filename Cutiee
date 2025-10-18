<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday Deepu</title>
<style>
  body {
    margin: 0;
    font-family: 'Comic Sans MS', cursive, sans-serif;
    background: linear-gradient(to right, #a0e9ff, #caf0f8);
    text-align: center;
    overflow-x: hidden;
  }
  .page { display: none; padding: 20px; }
  .active { display: block; }

  /* Glowing text */
  .glow-text {
    font-size: 2rem;
    font-weight: bold;
    color: #fff;
    text-shadow:
      0 0 5px #00bfff,
      0 0 10px #00bfff,
      0 0 20px #0077ff,
      0 0 40px #0077ff;
    animation: glowPulse 2s ease-in-out infinite alternate;
  }
  @keyframes glowPulse {
    from {
      text-shadow:
        0 0 5px #00bfff,
        0 0 10px #00bfff,
        0 0 20px #0077ff,
        0 0 40px #0077ff;
      transform: scale(1);
    }
    to {
      text-shadow:
        0 0 10px #00bfff,
        0 0 20px #0077ff,
        0 0 30px #0077ff,
        0 0 50px #0077ff;
      transform: scale(1.05);
    }
  }

  input {
    padding: 10px; font-size: 1rem; text-align: center;
    border: none; border-radius: 5px; margin-top: 10px; outline: none;
  }
  button {
    padding: 10px 20px; font-size: 1rem; margin-top: 10px;
    border: none; border-radius: 5px;
    background-color: #0096c7; color: #fff; cursor: pointer;
  }
  .hint { font-size: 0.9rem; margin: 10px 0; color: #333; }
  #error { margin-top: 10px; font-size: 1rem; }
  .error-flash { color: #ff4444; font-weight: bold; animation: flash 0.5s ease-in-out 3; }
  @keyframes flash { 0%,100%{opacity:1} 50%{opacity:0} }

  .message-box {
    background: rgba(255,255,255,0.8);
    padding: 20px; border-radius: 15px; max-width: 700px; margin: 20px auto;
    box-shadow: 0 0 20px #00bfff; line-height: 1.6;
    animation: glowPulse 2s ease-in-out infinite alternate;
  }

  footer {
    margin-top: 20px;
    color: #003366;
    font-weight: bold;
    text-shadow: 0 0 5px #99ccff;
    line-height: 1.6;
  }

  /* Final glowing line */
  .final-line {
    margin-top: 20px;
    font-size: 1.5rem;
    font-weight: bold;
    color: #ffffff;
    text-shadow:
      0 0 10px #00bfff,
      0 0 20px #0077ff,
      0 0 40px #0077ff,
      0 0 80px #0077ff;
    animation: glowPulse 2s ease-in-out infinite alternate;
  }

  /* Floating balloons */
  .balloon {
    position: absolute; width: 50px; height: 70px;
    background: radial-gradient(circle at 30% 30%, #ffffff, #00bfff);
    border-radius: 50%;
    animation: float 6s ease-in-out infinite;
  }
  @keyframes float {
    0% { transform: translateY(100vh); opacity: 0; }
    50% { opacity: 1; }
    100% { transform: translateY(-120vh); opacity: 0; }
  }
</style>
</head>
<body>

<!-- Lock Screen -->
<div id="lockscreen" class="page active">
  <h1 class="glow-text">Happy Birthday Deepu💙</h1>
  <h2>🔒 Enter the Secret Code</h2>
  <div class="hint">hint ledhu em ledhu easy number eh echinaa try cheskoo madammm</div>
  <input type="password" id="passcode" maxlength="4" placeholder="4-digit code"><br>
  <button onclick="checkCode()">Unlock</button>
  <div id="error"></div>
</div>

<!-- Main Page -->
<div id="mainpage" class="page">
  <h1 style="color:white; font-size:2.5rem; text-shadow:0 0 10px #004aad;">Happy Birthday Deepika 🎉</h1>
  <div class="message-box">
    <p>Dear Deepika,</p>
    <p>On this special day, I just want to say how grateful I am to have you in my life.</p>
    <p>You are more than a friend – you are family, my biggest supporter, and my happiest memory maker.</p>
    <p>Your smile makes everything brighter and your kindness makes every day better.</p>
    <p>Through good times and tough times, you have always been there, and I cherish that more than words can say.</p>
    <p>Thank you for every laugh we’ve shared, every secret we’ve kept, and every crazy adventure we’ve had.</p>
    <p>You deserve all the love, happiness, and success this world has to offer.</p>
    <p>May this year bring you endless joy, new opportunities, and beautiful memories.</p>
    <p>Always stay the amazing person you are – because the world is better with you in it.</p>
    <p>Here’s to more late-night talks, more laughter, and more memories we’ll never forget.</p>
    <p>I’ll always cheer for you, always stand by you, and always wish you the best.</p>
    <p>Because you are not just Deepika – you’re Deepu, my best friend at heart.</p>
    <p>No matter where life takes us, you will always have a special place in my heart.</p>
    <p>So blow out the candles, make a wish, and know that someone is wishing the best for you too.</p>
    <p>You’re irreplaceable, unforgettable, and absolutely amazing.</p>
    <p>Happy Birthday again! Let’s make this day as awesome as you are!</p>
    <p>With love,</p>
    <p>Abhi 💙</p>
  </div>
  <footer>
    ninnu chala sarlu hurt chesaa SORRY for that<br>
    these wishes are from your friend Abhi
  </footer>

  <div class="final-line">once again Happy Birthday Cutie💗</div>
</div>

<!-- Floating balloons -->
<div class="balloon" style="left:10%; animation-delay:0s;"></div>
<div class="balloon" style="left:30%; animation-delay:2s;"></div>
<div class="balloon" style="left:50%; animation-delay:4s;"></div>
<div class="balloon" style="left:70%; animation-delay:1s;"></div>
<div class="balloon" style="left:90%; animation-delay:3s;"></div>

<script>
function checkCode() {
  const input = document.getElementById('passcode').value;
  const errorEl = document.getElementById('error');
  if (input === '2009') {
    document.getElementById('lockscreen').classList.remove('active');
    document.getElementById('mainpage').classList.add('active');
  } else {
    errorEl.textContent = "malli try cheyi medam";
    errorEl.classList.remove('error-flash');
    void errorEl.offsetWidth; // re-trigger animation
    errorEl.classList.add('error-flash');
  }
}
</script>

</body>
</html>
