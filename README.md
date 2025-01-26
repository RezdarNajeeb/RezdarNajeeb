<!-- Rainbow Border Animation -->
<div align="center">
  <img src="https://i.imgur.com/ZKL7DwU.gif" width="100%"/>
</div>

###

<!-- Floating Profile Card -->
<div align="center" style="position: relative">
  <div style="position: relative; display: inline-block">
    <img src="https://i.giphy.com/media/juuaNj1zx0c5QR4C0q/giphy.webp" width="220" style="border-radius: 50%; border: 3px solid #6ee7b7; box-shadow: 0 0 35px rgba(110,231,183,0.4); animation: float 4s ease-in-out infinite"/>
    <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border-radius: 50%; background: radial-gradient(circle, rgba(110,231,183,0.2) 0%, rgba(255,255,255,0) 70%); pointer-events: none"></div>
  </div>

  <!-- Animated Title -->
  <h1 style="
    background: linear-gradient(45deg, #6ee7b7, #3b82f6);
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
    font-family: 'Segoe UI', sans-serif;
    font-weight: 800;
    letter-spacing: -1.5px;
    margin: 20px 0;
    animation: gradientShift 5s infinite alternate;
  ">
    Rezdar Najeeb
  </h1>
  
  <!-- Animated Subtitle -->
  <div style="
    background: linear-gradient(90deg, #3b82f6, #6ee7b7);
    padding: 2px;
    border-radius: 8px;
    display: inline-block;
    margin: 10px 0;
    animation: borderGlow 2s infinite alternate
  ">
    <div style="
      background: #0f172a;
      padding: 12px 25px;
      border-radius: 6px;
      font-size: 1.1em;
      color: #ffffff;
      font-weight: 500
    ">
      🚀 Laravel Architect • Backend Virtuoso • Digital Solutionist
    </div>
  </div>
</div>

<!-- Floating Tech Grid -->
<div align="center" style="margin: 40px 0">
  <div style="
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(80px, 1fr));
    gap: 15px;
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    background: rgba(59, 130, 246, 0.05);
    border-radius: 16px;
    border: 1px solid rgba(59, 130, 246, 0.1);
    backdrop-filter: blur(4px)
  ">
    <div style="
      padding: 15px;
      background: rgba(17, 24, 39, 0.8);
      border-radius: 12px;
      transition: all 0.3s ease;
      cursor: pointer;
      position: relative
    ">
      <img src="https://www.vectorlogo.zone/logos/laravel/laravel-ar21.svg" style="height: 40px; filter: drop-shadow(0 0 8px rgba(255,45,32,0.3))"/>
      <div class="tech-hover" style="
        position: absolute;
        top: -10px;
        left: -10px;
        right: -10px;
        bottom: -10px;
        border: 2px solid #3b82f6;
        border-radius: 16px;
        opacity: 0;
        transition: all 0.3s ease
      "></div>
    </div>
    <!-- Repeat similar blocks for PHP, Python, JavaScript, etc. -->
  </div>
</div>

<!-- Dynamic Snake Animation -->
<div align="center" style="margin: 40px 0">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/rezdarnajeeb/rezdarnajeeb/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/rezdarnajeeb/rezdarnajeeb/output/github-contribution-grid-snake.svg">
    <img alt="Contribution Snake" src="https://raw.githubusercontent.com/rezdarnajeeb/rezdarnajeeb/output/github-contribution-grid-snake.svg" style="max-width: 100%"/>
  </picture>
</div>

<!-- Social Links with Hover Effects -->
<div align="center" style="
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
  gap: 15px;
  max-width: 600px;
  margin: 0 auto;
  padding: 20px
">
  <a href="https://linkedin.com/in/yourprofile" target="_blank" style="
    background: linear-gradient(45deg, #0A66C2, #00A0DC);
    padding: 12px 25px;
    border-radius: 8px;
    color: white;
    text-decoration: none;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 8px;
    transition: all 0.3s ease;
    position: relative;
    overflow: hidden
  ">
    <span style="z-index: 1">LinkedIn</span>
    <div style="
      position: absolute;
      background: rgba(255,255,255,0.1);
      width: 50px;
      height: 100%;
      left: -30%;
      top: 0;
      transform: skewX(-15deg);
      transition: left 0.3s ease
    "></div>
  </a>
  
  <!-- Repeat similar blocks for other social links -->
</div>

<!-- Animated Footer -->
<div align="center" style="margin-top: 40px; padding: 20px 0; border-top: 1px solid rgba(59,130,246,0.2)">
  <div style="
    display: inline-block;
    padding: 8px 20px;
    background: rgba(59,130,246,0.1);
    border-radius: 50px;
    color: #6ee7b7;
    font-size: 0.9em;
    animation: pulse 2s infinite
  ">
    🚀 Building the Future, One Line at a Time
  </div>
</div>

<style>
  @keyframes float {
    0% { transform: translateY(0px); }
    50% { transform: translateY(-12px); }
    100% { transform: translateY(0px); }
  }
  
  @keyframes gradientShift {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }
  
  @keyframes borderGlow {
    0% { box-shadow: 0 0 10px rgba(59,130,246,0.2); }
    100% { box-shadow: 0 0 20px rgba(59,130,246,0.4); }
  }
  
  .tech-hover:hover {
    opacity: 1;
    transform: translateY(-5px);
  }
  
  a:hover .hover-effect {
    left: 120%;
  }
  
  @keyframes pulse {
    0% { transform: scale(1); opacity: 1; }
    50% { transform: scale(1.05); opacity: 0.8; }
    100% { transform: scale(1); opacity: 1; }
  }
</style>
