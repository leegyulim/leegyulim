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
</p>





<h1 align="center">👋 Hi, I’m Younghyun – Building Meaningful Intelligence with Data</h1>
<p align="center">
  대화형 AI, 자연어처리, 데이터 기반 서비스에 몰입하고 있는<br>
  개발자 Younghyun의 포트폴리오입니다.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AIVLE SCHOOL-KT-red?style=flat-square" />
  <img src="https://img.shields.io/badge/GPT-Driven-blue?style=flat-square&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Data Engineering-Python%20%7C%20GCP%20%7C%20SQL-yellowgreen?style=flat-square" />
</p>

---

## 🔍 About Me

> **실전 중심의 문제 해결**을 지향합니다.  
> AI를 활용한 의미 있는 사용자 경험을 만들기 위해, 작은 개선에도 끊임없이 실험합니다.

- 🧠 GPT 기반 Q&A 챗봇 개발 및 도메인 적용 (LangChain, ChromaDB)
- 🗂️ 대용량 PDF/STT 데이터 처리 자동화 및 요약 서비스 설계
- 🌐 Spring Boot, React 기반 AI 플랫폼 풀스택 개발 경험
- ☁️ AWS & GCP 멀티 클라우드 배포 및 JVM 최적화 경험
- 🔄 지속 가능한 데이터 흐름을 설계하는 것이 목표입니다

---

## 📁 Featured Projects

| Project | Description | Tech Stack |
|--------|-------------|------------|
| [AI Lecture Summarizer](https://github.com/) | STT + GPT 기반 강의 자동 요약 서비스 | Flask, GPT API, LangChain, GCP |
| [Voice Assistant Platform](https://github.com/) | 음성 인식 기반 AI 챗봇 플랫폼 | FastAPI, OpenAI, ChromaDB |
| [Multi-Cloud Deployment](https://github.com/) | GCP + AWS 통합 배포 및 리소스 최적화 | Docker, VM, S3, RDS |

> 각 프로젝트에는 실제 기술 선택 이유, 장애 해결 경험, 협업 방식까지 상세히 기술되어 있습니다.

---

## 🔎 Skills

### 💻 Languages & Frameworks  
![Python](https://img.shields.io/badge/Python-3776AB.svg?style=flat&logo=python&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F.svg?style=flat&logo=springboot&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB.svg?style=flat&logo=react&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-003B57?style=flat&logo=postgresql&logoColor=white)

### ☁️ DevOps & Tools  
![Docker](https://img.shields.io/badge/Docker-2496ED.svg?style=flat&logo=docker&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E.svg?style=flat&logo=amazonaws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

---

## 📊 Activity Highlights

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=yourgithubid&show_icons=true&theme=tokyonight&count_private=true" width="400"/>
  <img src="http://mazassumnida.wtf/api/v2/generate_badge?boj=yourbojhandle" width="250"/>
</p>

---

## 💡 What I Value

- **정제된 기술**보다 **실제 문제 해결**에 더 집중합니다.
- 현업 맥락에서 유용한 도구와 흐름을 빠르게 익히고 개선합니다.
- 협업 과정에서의 **기술 문서화**, **테스트 자동화**, **성과 측정**을 중요하게 생각합니다.

---

## 📬 Reach Me

[![Gmail](https://img.shields.io/badge/youremail@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:youremail@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourname)
[![Blog](https://img.shields.io/badge/Dev%20Blog-Velog-brightgreen?style=flat-square)](https://velog.io/@yourid)
