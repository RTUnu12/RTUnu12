![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=260&section=header&text=RTUnu12&fontSize=80&animation=fadeIn)

## 한계를 넘어 성장하는 백엔드 개발자, 류태웅

Spring Boot 기반 웹 서비스 개발 경험을 바탕으로, 실무에서 FastAPI 기반 API 개발, AWS CDK 인프라 운영, Kubeflow 파이프라인 개발까지 업무 영역을 확장

- 서비스 요구사항을 API와 데이터 구조로 구체화하고, 프론트엔드·ML 개발자와 협업해 실제 사용자 기능으로 연결
- GPU 실행 환경 분리, 데이터 수집 리소스 과다 사용, 수동 배포 반복 등 운영 과정에서 드러난 문제를 구조적으로 개선
- 백엔드 코드에 머무르지 않고 인프라, CI/CD, 파이프라인까지 필요한 영역을 직접 파악하고 해결 범위를 확장

`#FastAPI` `#SpringBoot` `#Kubeflow` `#Kubernetes` `#AWS_CDK` `#CI_CD` `#DataPipeline`

## Experience Highlights

- **프론트엔드·ML 요구사항을 API 계약으로 구체화한 MVP 개발**<br>
  FastAPI와 PostgreSQL 기반으로 구독 상태 확인, 예측 결과 조회, 관리자 구독 할당/회수 등 핵심 API 구현

- **Kubeflow DAG 외부 온프레미스 GPU 작업 실행 순서 보장**<br>
  온프레미스 GPU 작업을 Kubeflow Component로 추상화하고, DB를 중개 계층으로 활용해 작업 요청·상태·결과·로그를 교환하는 구조 구축

- **외부 데이터 수집 구조 최적화**<br>
  Playwright 기반 수집을 HTTP/API 기반 구조로 전환해 주요 컴포넌트의 Kubernetes 요청 자원 CPU **84.3%**, 메모리 **87.5%** 절감

- **AWS CDK 기반 클라우드 인프라 운영 및 변경 관리**<br>
  기존 CDK 기반 AWS 인프라를 인수인계받아 Stack 의존관계와 실제 리소스 상태를 확인하고, CDK 코드 수정·`cdk import`·`cdk diff` 기반으로 변경 관리

- **Kubeflow 컴포넌트/파이프라인 CI/CD 구축**<br>
  GitLab CI/CD에서 배포 대상 이미지를 선택하면 이미지 빌드, Registry 업로드, 컴포넌트 정의 갱신, 파이프라인 컴파일·업로드까지 이어지는 배포 흐름 자동화

- **DB·인프라 변경 이력 추적 체계 구성**<br>
  Alembic revision 변경 이력과 CloudTrail 관리 이벤트를 추적해 장애 발생 시 DB/인프라 변경 여부를 원인 분석 근거로 활용 가능한 구조 구성

- **AI 입력 데이터 이상 감지·알림 및 임시 보정 체계 구축**<br>
  외부 기준값 이상 수신 시 임시 보정 후 Slack 알림을 전송하는 별도 Python 스크립트로 운영 대응 흐름 구성

## Tech Stack

### Backend

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot">
</p>

### Database / Cache

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white" alt="Redis">
</p>

### Pipeline / Infra / DevOps

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS">
  <img src="https://img.shields.io/badge/AWS%20CDK-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS CDK">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes">
  <img src="https://img.shields.io/badge/Kubeflow-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubeflow">
  <img src="https://img.shields.io/badge/GitLab%20CI%2FCD-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white" alt="GitLab CI/CD">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="NGINX">
</p>

## Experience

### Tilda — BE Engineer

`2025.09 - 2026.08`

- AI 기반 예측/최적화 서비스의 백엔드 API, Kubeflow 파이프라인, AWS CDK 인프라 개발·유지보수
- 프론트엔드·ML 개발자와 API 계약, 응답 구조, 모델 Input/Output 연동 방식 조율
- 온프레미스 GPU 작업 실행 순서 보장, 외부 데이터 수집 구조 최적화, Kubeflow CI/CD 자동화
- CDK 기반 인프라 변경 관리, CloudTrail/Alembic 변경 이력 추적, 운영 리스크 대응

### DND — Developer & Designer

- **운영진** `2025.03 - Present`
- **12기** `2024.12.26 - 2025.02.21`
- **11기** `2024.06.28 - 2024.08.31`

## Certification

- AWS Certified Solutions Architect - Associate
- 정보처리기사

## GitHub & Algorithm

<p>
  <a href="https://github.com/RTUnu12">
    <img src="https://github-readme-stats.vercel.app/api?username=RTUnu12&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats">
  </a>
</p>

[![Solved.ac Profile](https://mazassumnida.wtf/api/v2/generate_badge?boj=RTUnu12)](https://solved.ac/RTUnu12/)

## Blog

[![Velog](https://velog-readme-stats.vercel.app/api/badge?name=rtunu12)](https://velog.io/@rtunu12)
