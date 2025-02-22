<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>김범규 Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    /* Reset & 기본 스타일 */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Poppins', sans-serif;
      background: #f4f7f6;
      color: #333;
      line-height: 1.6;
      padding: 20px;
    }
    .container {
      max-width: 1000px;
      margin: 0 auto;
    }
    h3 {
      margin-bottom: 20px;
      text-align: center;
      font-weight: 600;
      color: #444;
    }
    .center {
      text-align: center;
    }
    .section {
      margin-bottom: 40px;
      padding: 20px;
      background: #fff;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    }
    .badges {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 10px;
    }
    .badge {
      margin: 5px;
    }
    /* Projects Cards */
    .project-card {
      background: #fafafa;
      border-radius: 8px;
      padding: 15px;
      box-shadow: 0 1px 4px rgba(0,0,0,0.1);
      margin-bottom: 20px;
      max-width: 500px;
      width: 100%;
    }
    .project-card a {
      text-decoration: none;
    }
    .project-card input {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      border: 1px solid #ddd;
      border-radius: 4px;
      outline: none;
      transition: border-color 0.3s ease;
    }
    .project-card input:focus {
      border-color: #007ACC;
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Header -->
    <div class="center" style="margin-bottom: 40px;">
      <img src="https://capsule-render.vercel.app/api?type=waving&&color=timeGradient&height=300&section=header&text=김범규&fontSize=90" alt="김범규" style="max-width: 100%; height: auto;">
    </div>

    <!-- Tech Stack -->
    <div class="section">
      <h3>✨ Tech Stack ✨</h3>
      <div class="badges center">
        <img class="badge" src="https://img.shields.io/badge/C-007396?style=for-the-badge&logo=C&logoColor=white" alt="C">
        <img class="badge" src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++">
        <img class="badge" src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#">
        <img class="badge" src="https://img.shields.io/badge/Unity3D-F3F3F3?style=for-the-badge&logo=unity&logoColor=black" alt="Unity3D">
        <img class="badge" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
      </div>
    </div>

    <!-- Studying -->
    <div class="section">
      <h3>📚 Studying 📚</h3>
      <div class="badges center">
        <img class="badge" src="https://img.shields.io/badge/UnrealEngine-23282C?style=for-the-badge&logo=unrealengine&logoColor=white" alt="Unreal Engine">
        <img class="badge" src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
      </div>
    </div>

    <!-- Tools -->
    <div class="section">
      <h3>🛠 Tools 🛠</h3>
      <div class="badges center">
        <img class="badge" src="https://img.shields.io/badge/GitHub-F05033?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
        <img class="badge" src="https://img.shields.io/badge/Unity-181717?style=for-the-badge&logo=unity&logoColor=white" alt="Unity">
        <img class="badge" src="https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VSCode">
      </div>
    </div>

    <!-- Contact -->
    <div class="section">
      <h3>📫 Contact 📫</h3>
      <div class="center">
        <a href="https://cafe.naver.com/bluetree00" target="_blank">
          <img class="badge" src="https://img.shields.io/badge/Velog-1EBC8F?style=for-the-badge&logo=velog&logoColor=white" alt="Velog">
        </a>
      </div>
    </div>

    <!-- Projects undertaken -->
    <div class="section">
      <h3>📫 Projects undertaken 📫</h3>
      <div class="center">
        <!-- ARPG 프로젝트 -->
        <div class="project-card">
          <a href="https://github.com/bluetree00/ARPG" target="_blank">
            <img src="https://img.shields.io/badge/ARPG-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="ARPG">
          </a>
          <input type="text" placeholder="ARPG 코멘트를 남겨주세요">
        </div>
        <!-- Project_A 프로젝트 -->
        <div class="project-card">
          <a href="https://github.com/bluetree00/Project_A" target="_blank">
            <img src="https://img.shields.io/badge/Project_A-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="Project_A">
          </a>
          <input type="text" placeholder="Project_A 코멘트를 남겨주세요">
        </div>
        <!-- StellaWave 프로젝트 -->
        <div class="project-card">
          <a href="https://github.com/bluetree00/StellaWave" target="_blank">
            <img src="https://img.shields.io/badge/StellaWave-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="StellaWave">
          </a>
          <input type="text" placeholder="StellaWave 코멘트를 남겨주세요">
        </div>
        <!-- AI 프로젝트 -->
        <div class="project-card">
          <a href="https://github.com/loremtho/SHA_Project" target="_blank">
            <img src="https://img.shields.io/badge/AI%20프로젝트-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="AI 프로젝트">
          </a>
          <input type="text" placeholder="AI 프로젝트 코멘트를 남겨주세요">
        </div>
      </div>
    </div>
  </div>
</body>
</html>
