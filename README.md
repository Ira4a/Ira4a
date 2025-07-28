<!-- Подключаем пиксельный шрифт -->
<link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">

<style>
  .pixel-block {
    background-color: #0d0d0d;
    color: #00f0ff;
    font-family: 'Press Start 2P', monospace;
    padding: 20px;
  }

  .glow {
    text-shadow: 0 0 8px #00f0ff;
  }

  .terminal-line::after {
    content: '|';
    animation: blink 1s steps(2, start) infinite;
    text-shadow: 0 0 10px #00f0ff;
  }

  @keyframes blink {
    0% { opacity: 1; }
    50% { opacity: 0; }
    100% { opacity: 1; }
  }

  .npc-img {
    width: 48px;
    vertical-align: middle;
    margin-right: 10px;
    image-rendering: pixelated;
  }
</style>

<div class="pixel-block">

  <h1 align="right" class="glow terminal-line">
    <img src="https://i.ibb.co/NnpNzCX/pixel-npc.gif" alt="Pixel Avatar" class="npc-img" />
    Hi, I'm Irada! 👾
  </h1>

  <hr style="border: 1px dashed #00f0ff;">

  <table align="center" style="padding: 10px;">
    <tr>
      <td>
        <img src="https://github-readme-stats.vercel.app/api?username=Ira4a&show_icons=true&theme=dark&icon_color=00f0ff&text_color=00f0ff&title_color=00f0ff" width="400" />
      </td>
      <td>
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ira4a&layout=compact&theme=dark&text_color=00f0ff&title_color=00f0ff" width="400" />
      </td>
    </tr>
  </table>

  <hr style="border: 1px dashed #00f0ff;">

  <p align="center" style="font-size: 10px;" class="glow">📁 FEATURED PROJECTS</p>

  <table align="center">
    <tr>
      <td align="center" width="50%">
        <a href="https://github.com/Ira4a/Planning-calendar">
          <img src="https://github-readme-stats.vercel.app/api/pin/?username=Ira4a&repo=Planning-calendar&theme=dark&title_color=00f0ff&text_color=00f0ff&icon_color=00f0ff" alt="Planning Calendar" />
        </a>
        <br />
        <strong style="color:#00f0ff;">⭐ RECOMMENDED</strong>
      </td>
      <td align="center" width="50%">
        <a href="https://github.com/Ira4a/runner-game">
          <img src="https://github-readme-stats.vercel.app/api/pin/?username=Ira4a&repo=runner-game&theme=dark&title_color=00f0ff&text_color=00f0ff&icon_color=00f0ff" alt="Runner Game" />
        </a>
        <br />
        <strong style="color:#00f0ff;">🆕 LAST PROJECT</strong>
      </td>
    </tr>
  </table>

  <hr style="border: 1px dashed #00f0ff;">

  <p align="center">
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=Ira4a&theme=github-compact&hide_border=true&area=true&color=00f0ff&line=00f0ff&point=00f0ff&bg_color=0d0d0d00" />
  </p>

</div>
