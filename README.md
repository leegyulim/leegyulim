<!-- 
Hi, I'm [Your Name]! 
-->

<!-- 1. HEADER -->
<div align="center">
  <img src="[![search pstatic](https://github.com/user-attachments/assets/15cfbad5-73cf-471b-b704-b1e6c65b63ab)]" width="800"/>
  <h1> 안녕하세요! 👋, 개발자 이규림입니다. </h1>
</div>

<!-- 3. SKILLS -->
## 🛠️ My Tech Stack & Tools

> 제가 프로젝트에서 사용해 본 기술들입니다.

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
<br/>
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![Shell Script](https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
<br/>
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

<br/>

<!-- 4. FEATURED PROJECTS -->
## ✨ Featured Projects

> 제가 진행했던 주요 프로젝트들입니다. 자세한 내용은 각 저장소의 README를 참고해주세요.

<table>
  <tr>
    <td width="33%">
      <h3 align="center">LSTM 기반 시계열 데이터를 활용한 평균 온도 예측 모델</h3>
      <div align="center">
        <a href="https://github.com/leegyulim/Temperature-Prediction-LSTM.git" target="_blank">
          <img src="https://github.com/user-attachments/assets/4c06104b-d5d8-413e-af1c-5f3fc5c324b9" alt="Project Banner" width="400"/>
        </a>
        <p>
          <a href="https://github.com/leegyulim/Temperature-Prediction-LSTM.git" target="_blank">
            <b> 🚀 GitHub Repository </b>
          </a>
        </p>
      </div>
      <details>
        <summary> 📖 프로젝트 상세 설명 보기 </summary>
        <ul>
          <li>과거 20년치 기상 데이터를 분석하여 미래의 평균 온도를 예측하는 딥러닝 모델을 개발했습니다.</li>
          <li><b>주요 구현 내용:</b></li>
          <ul>
            <li><b>데이터 전처리:</b> 20년 분량의 시계열 데이터에서 불필요한 변수를 제거하고 결측치를 처리하여 모델 학습용 데이터셋을 구축</li>
            <li><b>모델링:</b> 시간에 따른 데이터 패턴과 장기 의존성 학습에 유리한 RNN 기반의 <b>LSTM 모델</b>을 설계 및 구현</li>
            <li><b>모델 최적화:</b> <b>TensorFlow/Keras</b>를 활용하고, 활성화 함수(Hyperbolic Tangent)와 옵티마이저(Adam)를 선정하여 모델 성능 최적화</li>
            <li><b>성능 검증:</b> 구축된 모델의 예측값과 실제 온도를 비교하여 <b>평균제곱오차(MSE)</b>를 계산하고, 목표 정확도를 달성했음을 정량적으로 검증</li>
          </ul>
        </ul>
      </details>
    </td>
    <td width="33%">
      <h3 align="center">PHP/MariaDB 게시판 CI/CD 파이프라인 구축</h3>
      <div align="center">
        <a href="https://github.com/leegyulim/my-php-board-project" target="_blank">
          <img src="https://github.com/user-attachments/assets/641bceed-ab77-434a-81b3-4ddd59230376" alt="Project Banner" width="400">
        </a>
        <p>
          <a href="https://github.com/leegyulim/my-php-board-project" target="_blank">
            <b> 🚀 GitHub Repository </b>
          </a>
        </p>
      </div>
      <details>
        <summary> 📖 프로젝트 상세 설명 보기 </summary>
        <ul>
          <li>PHP/MariaDB로 구성된 다중 컨테이너 웹 애플리케이션을 AWS EC2에 자동으로 배포하는 End-to-End 파이프라인을 구축했습니다.</li>
          <li><b>주요 구현 내용:</b></li>
          <ul>
            <li><b>Docker Compose:</b> Web/DB 서버 환경을 코드로 정의하고 관리</li>
            <li><b>GitHub Actions:</b> `git push` 시 자동으로 이미지를 빌드하고 EC2에 배포 (CI/CD)</li>
            <li><b>Terraform:</b> EC2, 보안 그룹 등 모든 AWS 인프라를 코드로 관리 (IaC)</li>
            <li><b>트러블슈팅:</b> 클라우드 네트워크, 권한, 경로 등 배포 과정에서 발생하는 다양한 문제를 해결</li>
          </ul>
        </ul>
      </details>
    </td>
    <td width="33%">
      <h3 align="center">단축 URL 서비스 CI/CD 파이프라인 구축</h3>
       <div align="center">
        <a href="https://github.com/leegyulim/my-short-url-app" target="_blank">
          <img src="https://github.com/user-attachments/assets/69319da2-7a22-4046-b635-dba44e871e00" alt="Project Banner" width="400">
        </a>
        <p>
          <a href="https://github.com/leegyulim/my-short-url-app" target="_blank">
            <b> 🚀 GitHub Repository </b>
          </a>
        </p>
      </div>
      <details>
        <summary> 📖 프로젝트 상세 설명 보기 </summary>
        <ul>
          <li>Python/Flask로 개발한 간단한 웹 애플리케이션을 AWS EC2에 자동으로 배포하는 파이프라인을 구축했습니다.</li>
          <li><b>주요 구현 내용:</b></li>
          <ul>
            <li><b>Docker:</b> `Dockerfile`을 이용한 애플리케이션 컨테이너화</li>
            <li><b>GitHub Actions:</b> Docker Hub 이미지 자동 푸시 및 EC2 원격 배포</li>
            <li><b>Terraform:</b> 단일 EC2 인스턴스 및 관련 인프라 코드화</li>
          </ul>
        </ul>
      </details>
    </td>
  </tr>
</table>

<br/>

<!-- 5. GITHUB STATS -->
## 📈 My GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=leegyulim&show_icons=true&theme=radical&rank_icon=github" alt="leegyulim's GitHub stats"/>
  <br/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=leegyulim&layout=compact&theme=radical" alt="leegyulim's top languages" />
</div>

<br/>

<!-- 6. CONTACT -->
## 📫 How to Reach Me

<p align="center">
  <a href="mailto:tbehfdl1@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="www.linkedin.com/in/규림-이-50a710387"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
</p>
