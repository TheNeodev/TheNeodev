<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>NeoDev</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <!-- Tailwind CSS CDN for utility-first styling -->
  <script src="https://cdn.tailwindcss.com"></script> <!-- :contentReference[oaicite:3]{index=3} -->
  <!-- Optional: configure Tailwind (custom colors, fonts) -->
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            primary: '#FF0000',
            secondary: '#FFA500',
          },
        }
      }
    }
  </script>
  <style>
    /* Fallback for non-JS or to override individual elements */
    .gradient-header {
      background: linear-gradient(90deg, #FF0000, #FFA500);
    }
  </style>
</head>
<body class="bg-gray-100 text-gray-800">

  <!-- Header Section -->
  <header class="gradient-header py-12 text-center text-white">
    <img
      class="w-32 h-32 rounded-full mx-auto border-4 border-white"
      src="https://avatars.githubusercontent.com/u/1314204512814235689?v=4"
      alt="NeoDev Avatar"
    />
    <h1 class="text-5xl font-bold mt-4">NeoDev</h1>
    <p class="mt-2 text-lg">Python • Gradio • Google Colab</p>
  </header>

  <!-- Main Content Container -->
  <main class="max-w-3xl mx-auto mt-10 space-y-8 p-4">

    <!-- Visitor & Project Badges -->
    <section class="bg-white rounded-lg shadow p-6">
      <div class="flex flex-wrap justify-center gap-4">
        <img
          src="https://komarev.com/ghpvc/?username=TheNeodev&label=Visitor&color=FF0000&style=flat"
          alt="Visitor Count Badge"
        /> <!-- GitHub‑profile visitor counter badge -->
        <img
          src="https://img.shields.io/badge/Advanced--RVC--Inference-blue?style=for-the-badge&logo=github"
          alt="Advanced‑RVC‑Inference Repo"
        /> <!-- :contentReference[oaicite:4]{index=4} -->
        <img
          src="https://img.shields.io/badge/NeoRVC-blue?style=for-the-badge&logo=github"
          alt="NeoRVC Repo"
        /> <!-- :contentReference[oaicite:5]{index=5} -->
      </div>
      <ul class="mt-6 space-y-2 text-gray-700">
        <li>🔭 I’m currently working on <a href="https://github.com/ArkanDash/Advanced-RVC-Inference" class="text-blue-600 hover:underline">Advanced-RVC-Inference</a> and <a href="https://github.com/TheNeodev/NeoRVC" class="text-blue-600 hover:underline">NeoRVC</a>.</li>
        <li>🌱 I’m currently learning RVC and Colab notebooks.</li>
        <li>👯 I’m looking to collaborate on open source projects.</li>
        <li>💬 Ask me about Python, Gradio.</li>
        <li>📫 Reach me at <a href="mailto:neoforevershog@gmail.com" class="text-blue-600 hover:underline">neoforevershog@gmail.com</a> or on <a href="https://discord.com/users/1314204512814235689" class="text-blue-600 hover:underline">Discord</a>.</li>
        <li>⚡ Fun fact: I love Sonic the Hedgehog and YTP.</li>
      </ul>
    </section>

    <!-- Skills Section -->
    <section class="bg-white rounded-lg shadow p-6">
      <h2 class="text-2xl font-semibold mb-4">💻 Skills</h2>
      <div class="flex flex-wrap gap-4">
        <!-- Example static badge for Python -->
        <img
          src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"
          alt="Python Badge"
        /> <!-- :contentReference[oaicite:6]{index=6} -->
        <!-- Add more badges similarly -->
      </div>
    </section>

    <!-- Tools Section -->
    <section class="bg-white rounded-lg shadow p-6">
      <h2 class="text-2xl font-semibold mb-4">🛠 Tools</h2>
      <div class="flex flex-wrap gap-4">
        <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" /> <!-- :contentReference[oaicite:7]{index=7} -->
        <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /> <!-- :contentReference[oaicite:8]{index=8} -->
        <img src="https://img.shields.io/badge/Gradio-db9618?style=for-the-badge&logo=gradio&logoColor=white" alt="Gradio" /> <!-- :contentReference[oaicite:9]{index=9} -->
        <img src="https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=blue" alt="Colab" /> <!-- :contentReference[oaicite:10]{index=10} -->
        <img src="https://img.shields.io/badge/Hugging_Face-FF9900?style=for-the-badge&logo=huggingface&logoColor=white" alt="Hugging Face" /> <!-- :contentReference[oaicite:11]{index=11} -->
      </div>
    </section>

    <!-- GitHub Stats Cards -->
    <section class="bg-white rounded-lg shadow p-6 text-center">
      <h2 class="text-2xl font-semibold mb-4">📊 GitHub Stats</h2>
      <img
        src="https://github-readme-stats.vercel.app/api?username=TheNeoDev&show_icons=true&count_private=true&include_all_commits=false&custom_title=NeoDev's%20GitHub%20Stats&title_color=FFD700&text_color=DAA520&icon_color=FFA500&bg_color=FFFFFF"
        alt="NeoDev's GitHub Stats"
      /> <!-- :contentReference[oaicite:12]{index=12} -->
      <img
        class="mt-4"
        src="https://github-readme-streak-stats.herokuapp.com/?user=TheNeoDev&currStreakNum=FFFF00&sideNums=FFFF00&currStreakLabel=FFFFFF&sideLabels=FFFFFF&background=00000000&border=FFFFFF"
        alt="NeoDev's GitHub Streak"
      /> <!-- :contentReference[oaicite:13]{index=13} -->
    </section>

  </main>

  <!-- Optional: JavaScript for interactivity -->
  <script>
    // e.g., theme switcher, animations
  </script>
</body>
</html>
