<div align="center">

<!-- Animated Header with Gradient Text -->
<h1 style="
  font-size: 3.5rem;
  background: linear-gradient(45deg, #00ff88, #00a3ff);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  animation: gradient 5s ease infinite;
  margin-bottom: 2rem;
">
  𝙃𝙞𝙢𝙖𝙣𝙨𝙝𝙪 𝙏𝙞𝙬𝙖𝙧𝙞
</h1>

<!-- Floating Social Icons -->
<div class="social-container" style="
  display: flex;
  gap: 1.5rem;
  justify-content: center;
  margin-bottom: 3rem;
">
  <a href="https://linkedin.com/in/himanshu-tiwari" target="_blank" style="transition: transform 0.3s ease;">
    <img src="https://img.icons8.com/3d-fluency/94/linkedin.png" width="50" style="filter: drop-shadow(0 0 8px #00a3ffaa); transition: all 0.3s ease;" onmouseover="this.style.transform='translateY(-5px) scale(1.2)'" onmouseout="this.style.transform='none'">
  </a>
  <!-- Add other social icons similarly -->
</div>

</div>

<!-- Animated Divider -->
<div style="
  height: 2px;
  background: linear-gradient(90deg, transparent, #00ff88, transparent);
  margin: 2rem 0;
  position: relative;
  overflow: hidden;
">
  <div style="
    content: '';
    position: absolute;
    width: 50%;
    height: 100%;
    background: linear-gradient(90deg, transparent, #00a3ff, transparent);
    animation: shine 3s infinite;
  "></div>
</div>

<!-- 3D Flip Card Container -->
<div style="
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin: 2rem 0;
">

<!-- DevOps Card -->
<div style="
  background: rgba(255, 255, 255, 0.05);
  border-radius: 15px;
  padding: 1.5rem;
  transition: all 0.3s ease;
  transform-style: preserve-3d;
  position: relative;
  cursor: pointer;
  border: 1px solid #00ff8833;
" onmouseover="this.style.transform='perspective(1000px) rotateX(10deg) rotateY(10deg) scale(1.05)'" 
 onmouseout="this.style.transform='none'">
  <h3 style="color: #00ff88; margin-bottom: 1rem;">🛠 DevOps Expertise</h3>
  <ul style="list-style: none; padding: 0;">
    <li style="padding: 0.5rem 0; border-bottom: 1px solid #ffffff1a;">
      <span style="color: #00a3ff;">►</span> CI/CD Pipelines
    </li>
    <!-- Add other list items -->
  </ul>
</div>

<!-- Add other cards similarly -->

</div>

<!-- Animated Skills Matrix -->
<h2 style="color: #00a3ff; margin: 2rem 0 1rem;">🌟 Skills Matrix</h2>
<div style="
  background: rgba(255, 255, 255, 0.03);
  border-radius: 10px;
  padding: 1.5rem;
  margin-bottom: 2rem;
">

<div style="
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1rem;
">
  <div>
    <div style="display: flex; justify-content: space-between; margin-bottom: 0.5rem;">
      <span>AWS</span>
      <span>90%</span>
    </div>
    <div style="
      height: 8px;
      background: #ffffff15;
      border-radius: 4px;
      overflow: hidden;
    ">
      <div style="
        width: 90%;
        height: 100%;
        background: linear-gradient(90deg, #00ff88, #00a3ff);
        border-radius: 4px;
        animation: progress 1.5s ease-out;
      "></div>
    </div>
  </div>
  <!-- Add other skill bars -->
</div>

</div>

<!-- Glowing GitHub Stats -->
<div style="
  position: relative;
  padding: 2rem;
  border-radius: 15px;
  background: rgba(0, 163, 255, 0.05);
  margin: 2rem 0;
  overflow: hidden;
">
  <div style="
    position: absolute;
    width: 200%;
    height: 200%;
    background: conic-gradient(from 0deg, transparent, #00ff88, transparent);
    animation: rotate 4s linear infinite;
    top: -50%;
    left: -50%;
  "></div>
  <div style="
    position: relative;
    z-index: 1;
    background: #0d1117;
    border-radius: 10px;
    padding: 1rem;
  ">
    <img src="https://github-readme-stats.vercel.app/api?username=himanshutiwari5&show_icons=true&theme=radical" alt="Stats" style="width: 100%;">
  </div>
</div>

<!-- CSS Animations -->
<style>
@keyframes gradient {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}

@keyframes shine {
  0% { left: -50%; }
  100% { left: 150%; }
}

@keyframes progress {
  from { width: 0; }
}

@keyframes rotate {
  from { transform: rotate(0deg); }
  to { transform: rotate(360deg); }
}
</style>
