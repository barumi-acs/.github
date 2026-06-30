<div align="center">

# 플랜잇 PlanIt

### AI 기반 자기계발 목표 및 일정 관리 플랫폼

> **트렌드 분석부터 목표 추천, 일정 관리, 성장 피드백까지**  
> AI와 클라우드 기술을 활용해 사용자의 성장을 돕는 목표 관리 서비스

<img src="https://github.com/user-attachments/assets/91037b05-2a17-4880-9b40-3bda27fadced" width="100%">


</div>

---

## 프로젝트 소개

PlanIt은 AI가 최신 트렌드를 분석하여 사용자에게 필요한 목표를 추천하고,
목표를 실행 가능한 일정(Todo)으로 자동 생성하며,
수행 데이터를 기반으로 성장 리포트를 제공하는 AI 기반 자기계발 플랫폼입니다.

단순한 Todo 관리 서비스를 넘어,
**"무엇을 해야 할지"부터 AI가 함께 고민하는 서비스**를 목표로 개발했습니다.


---

## 주요 기능

### AI 목표 추천

- 글로벌 트렌드 분석
- 사용자 맞춤 목표 추천
- AI 기반 목표 생성
  
### AI 일정 생성

- 목표 기반 일정 자동 생성
- 날짜별 Todo 생성
- 실행 가능한 계획 자동 구성

### 일정 관리

- 캘린더 기반 일정 관리
- 오늘/주간/목표 단위 관리
- 일정 미루기 기능
- 진행률 확인

### AI 성장 리포트

- 수행률 분석
- 미룸 패턴 분석
- 성장 방향 피드백
- AI 종합 리포트 제공

---

# 시스템 아키텍처

<p align="center">

  <img src="https://github.com/user-attachments/assets/17f2da12-6d80-4d78-b6b3-9049549de73d" width="100%">

</p>

### Architecture Highlights

- AWS EKS 기반 Microservices Architecture
- Terraform 기반 Infrastructure as Code
- GitHub Actions + Argo CD GitOps CI/CD
- Prometheus · Grafana · Loki 기반 Observability
- CloudWatch 중앙 로그 관리
- Slack 장애 알림 자동화

---

## 기술 스택

- 프론트엔드: React Native
- 백엔드: Java 21, Spring Boot, Spring Cloud Gateway, Spring Security, JPA, JWT
- AI: Amazon Bedrock, Prompt Chaining
- 데이터베이스: MariaDB, DynamoDB, ElastiCache
- 클라우드: AWS EKS, EC2, ECR, RDS, S3, ALB, IAM, CloudWatch
- DevOps: Docker, Kubernetes, Terraform, GitHub Actions, Argo CD, Helm
- 모니터링: Prometheus, Grafana, Loki, CloudWatch, Slack
- 협업: GitHub, Confluence, Jira

---

## 팀 소개

| 이름 | 담당 |
|------|------|
| 이진영 | PM, User Service, 공통 인프라 |
| 신예지 | AI Report, Chatbot, Monitoring |
| 신준용 | Schedule Service, AWS EKS |
| 박현빈 | Strategy Service, Terraform, GitOps CI/CD |

---

## 서비스 화면

| <img width="161" height="308" alt="image" src="https://github.com/user-attachments/assets/9f8be91a-a01a-4ea9-8078-19af624f022b" /> | <img width="160" height="309" alt="image" src="https://github.com/user-attachments/assets/d634de99-236d-4164-a4ab-c1386d75f33b" /> | <img width="161" height="305" alt="image" src="https://github.com/user-attachments/assets/40224a2e-2b84-4902-afd9-682bd44dd693" /> | <img width="160" height="303" alt="image" src="https://github.com/user-attachments/assets/66757e37-1c60-42da-9c9a-b0789e6d2b18" /> | 
|:---:|:---:|:---:|:---:|
| 대시보드 | 트렌드 기반 할일 생성 프롬프트 | 실제 생성된 할일 | 할일 상세 |

| <img width="164" height="312" alt="image" src="https://github.com/user-attachments/assets/7b7c7b53-12d3-4f93-b5b6-d670778dca60" /> | <img width="158" height="302" alt="image" src="https://github.com/user-attachments/assets/ba1fc5ea-5594-4ad2-8c8f-ef52a70c62f9" /> | <img width="156" height="305" alt="image" src="https://github.com/user-attachments/assets/fcdac7bf-3780-414a-8af6-f2cafc7cb3e2" /> | <img width="158" height="304" alt="image" src="https://github.com/user-attachments/assets/0bb499bd-8818-4ad9-8293-5d00ce725a87" /> |
|:---:|:---:|:---:|:---:|
| AI 피드백 챗봇 | AI 피드백 리포트 | AI 피드백 리포트 (수행 패턴 분석) | 친구 할일 응원 |

---

## 시연 영상
> 아래 이미지를 클릭하시면 시연 영상을 확인하실 수 있습니다.
<p>
  <a href="https://youtube.com/shorts/w8srLyqyzsY?feature=share">
    <img
      src="https://github.com/user-attachments/assets/b39b3ae1-d48d-4036-b3da-805f2454f5c6"
      width="250"
      alt="시연 영상 바로가기"
    />
  </a>
</p>
