![header](https://capsule-render.vercel.app/api?type=waving&color=100:ff7f00,100:87ceeb&height=150&section=header)

![venom](https://capsule-render.vercel.app/api?type=venom&height=150&text=JobScanner&fontSize=100&color=100:ff7f00,100:87ceeb&stroke=ffffff)  
![venom](https://capsule-render.vercel.app/api?type=transparent&height=50&text=취업%20준비의%20스마트%20솔루션&fontSize=30&color=87ceeb)


## 🫂 Team

### 팀 이름: `Team2Job`
- `Team` + `To` + `Job` ➜ 취업을 하기 위해 만난 팀
- `Team2` + `JobScanner` ➜ 플레이데이터 DE32기 2조의 JobScanner 서비스

### 팀원 소개 및 역할
| **김도현** | **김동욱** | **이상우** | **이상훈** | **조하영** |
|:------------:|:------------:|:------------:|:------------:|:------------:|
| [@rlaehgus97](https://github.com/rlaehgus97) | [@DONGUK777](https://github.com/DONGUK777) | [@GITSangWoo](https://github.com/GITSangWoo) | [@hun0219](https://github.com/hun0219) | [EstherCho-7](https://github.com/EstherCho-7) |
| • 애플리케이션 관리<br>• 형상 및 배포 관리<br>• Docker, Airflow<br>• 브랜치 전략 수립 | • 팀 분위기 <br>• 백엔드 개발<br>• 데이터 전처리<br>• 기술 사전 정의  | • 기술적 문제 해결 및 방향 설정<br>• 시스템 아키텍처 설계<br>• OCR(이미지 텍스트화)<br>• 백엔드 개발 | • 팀원들의 애로 사항 논의<br>• 애자일 프로세스 적용<br>• Docker, Airflow<br>• 크롤링 코드 통합 | • 프로젝트 일정 관리<br>• 진행 상황 모니터링<br>• 프론트엔드 개발<br>• ERD 작성 |


<br/>

## 📂프로젝트 소개
### 🎯프로젝트 목표
- 여러 채용 공고 사이트의 정보를 크롤링하여 다양한 인사이트(직군별 핵심 키워드 순위, 기술 정보 제공, 직무 소개, 채용 공고 요약)를 제공하여 SW 개발 입문/취업에 실질적인 도움을 주는 것이 목표입니다.

### 🔑주요기능
- **회원가입 및 로그인**
  - 구글/네이버/카카오 계정으로 회원가입 및 로그인이 가능합니다.
    
- **직군별 기술 스택 순위**
  - 이전 `네이버 실시간 검색어`처럼 현재 모집중인 채용 공고 데이터를 바탕으로 직군별 기술 스택 순위를 확인할 수 있습니다.
  - 주요업무, 자격요건, 우대사항의 카테고리로 기술 스택 순위를 확인할 수 있습니다.
 
- **기술별 상세 정보 제공**
  - 기술 스택에 대한 다양한 정보(설명, 공식 문서, 유튜브 동영상 추천, 도서 추천)을 확인할 수 있습니다.
  - 원하는 기술을 북마크에 저장할 수 있습니다.
 
- **직무별 채용 공고 요약**
  - 기존 불필요한 채용 공고 내용에서 핵심적인 내용만을 담은 채용 공고를 제공합니다.
  - 원하는 공고를 북마크에 저장할 수 있습니다.
 
- **마이페이지**
  - 북마크한 기술/공고를 한 눈에 모아 볼 수 있습니다.
 
## 👀Demo
### 시연 Video
### 배포 URL
### 팀 Notion

<br/>

## 🗓️ 전체 프로젝트 일정
> **프로젝트 일정 : 2024년 12월 14일 ~ 2024년 1월 6일(총 24일)**

<br/>

## 🛠️사용된 기술 스택
![최종발표용-011](https://github.com/user-attachments/assets/680e1e39-8c8f-4ddf-8dca-1e5f2e249c16)

<br/>

## 💾사용된 데이터
- **크롤링한 채용 사이트**
  - **Incruit**
  - **Jobkorea**
  - **Jumpit**
  - **RocketPunch**
  - **Saramin**  

<br/>

## ERD


## 목차
 1. [📚프로젝트 개요](#프로젝트-개요)
 2. [📋요구사항 정의서](#요구사항-정의서)
 3. [🏗️시스템 아키텍처](#시스템-아키텍처)
 4. [⌨트러블 슈팅 및 PR](#트러블-슈팅-및-PR)
 5. [🔄KPT 회고](#KPT-회고)
 6. [🔍최종 검토 및 개선](#최종-검토-및-개선)

<br/>

## 📚프로젝트 개요

### JobScanner 취업 준비의 스마트 솔루션

이 프로젝트는 여러 채용 공고 사이트의 정보를 크롤링하여 다양한 인사이트(직군별 핵심 키워드 순위, 기술 정보 제공, 직무 소개, 채용 공고 요약)를 제공하여 SW 개발 입문/취업에 실질적인 도움을 주는 것이 목표입니다.

---

### 프로젝트 시나리오
- 2023년 상반기 IT 업계 채용시장 지원 수는 108만 7천건으로 나타났다.[출처: 원티드랩]
- 약 4,000명의 경력/예비 개발자의 설문조사 결과 구직/이직 과정에서, 어려움을 겪는 부분은 포트폴리오(42%), 코딩테스트(40.8%), 기술면접(33.7%), 이력서 작성(22%)입니다.[출처: (주)그렙]
- **JobScanner**는 개발자로 입문/취업하는 과정에서 위와 같은 어려움을 겪는 사람들에게 다양한 인사이트와 공고 요약을 통해 효과적인 취업 전략 수립과 편리함을 제공 받을 수 있습니다.
  - 최신 기술 스택 변화가 반영된 직군별 기술 키워드 순위: 여러 채용 사이트의 채용공고 데이터를 바탕으로 **기업에서 요구하는 기술 스택 순위**를 한 눈에 확인 할 수 있습니다.
  - 채용공고의 핵심 내용만을 담은 공고 요약: `회사`, `공고 제목`, `주요업무`, `자격요건`, `우대사항`, `요구 기술 스택 목록`, `마감일`에 대한 정보를 제공합니다.   

<br/>

### 📋요구사항 정의서
---

<br/>

### 📅개발 일정
---


<br/>

### ⚙주요 기능
---
#### 1. Kubernetes 상의 Prometheus 및 Grafana 배포
   - Kubernetes 클러스터에 Prometheus와 Grafana를 배포하여 웹 서버의 CPU 사용량을 수집하고 대시보드에서 실시간으로 확인합니다.

#### 2. Docker 웹 서버 배포 및 부하 테스트
   - Docker Compose로 웹 서버를 실행하고, 부하 테스트를 통해 CPU 사용량 변화를 관찰합니다.

#### 3. 자동 및 수동 스케일링
   - **자동 스케일링**: CPU 사용량이 설정된 임계치를 넘으면 서버가 자동으로 스케일 업됩니다.
   - **수동 스케일링**: 관리자 페이지에서 필요에 따라 수동으로 서버 스케일 업/다운을 조정할 수 있습니다.

<br/>

### 🏗️시스템 아키텍처
---
![image](https://github.com/user-attachments/assets/5d35abed-b4a5-4c5f-aee8-60cdabac13ae)

<br/>

### 🌐환경 구성
---
#### Team_repository clone
```bash
$ git clone git@github.com:DE32FinalTeam2/FourthProject.git
```

### Airflow 실행
```bash
$ cd airflow

$ docker compose up -d
```


### java 웹 실행
```bash
# minikube 실행

$ minikube start

$ kubectl apply -f java-deployment.yaml

$ minikube service java-service --url
```

#### Spark/Exporter/Prometheus/Grafana 실행
```bash
# 해당 docker-compose.yaml이 있는 디렉토리로 이동

# FourthProject 기준

$ cd moni

$ docker compose up -d
```

#### 그 이후 진행사항
```bash 
# FourthProject 기준

$ pip install .

$ streamlit run src/fourthproject/main.py

# streamlit web 접속 (http://localhost:8501)

# manual scale In/Out
```

### 번외/테스트
```bash
# 부하 테스트

$ ab -t <테스트 지속 시간(s)> -c <동시 요청 수> http://localhost:8949/
```


<br/>

### ✅테스트 결과
---
![image](https://github.com/user-attachments/assets/89fee6a8-c9cd-4f3c-a0ed-b5f75c83c0dc)
---
![image](https://github.com/user-attachments/assets/a8e05d27-193c-4bf0-9d2d-80621262c06a)
---
![image](https://github.com/user-attachments/assets/ee2f11c3-466a-4559-8abc-4fd74630a7e7)
---
![image](https://github.com/user-attachments/assets/29f56c0d-66c1-4a15-9dc3-03cef04b8e9e)

<br/>

## ⌨트러블 슈팅 및 PR
- [[Dev 0.1.0] 우선 구현해야 할거 정리](https://github.com/DE32FinalTeam2/FourthProject/pull/1)
- [Release 0.1.0](https://github.com/DE32FinalTeam2/FourthProject/pull/2)
- [Streamlit cpu 사용량, 메모리 사용량, 네트워크 대역폭 사용량 차트](https://github.com/DE32FinalTeam2/FourthProject/pull/3)
- [1차 작업물 통합하기](https://github.com/DE32FinalTeam2/FourthProject/pull/4)


<br/>

# 🔄KPT 회고

## 김동욱
<details>
<summary>KEEP</summary>
<div>
<figure align="center">
  <p>1. 업무 분담이 확실하게 이루어졌다.</p>
  <p>2. 이전에 수업했던 내용들을 종합하여 복습할 수 있었다.</p>
  <p>3. 최종 프로젝트에서 설계될 구조를 미리 학습할 수 있었다.</p>
 </figure>
</div>
</details>

<details>
<summary>PROBLEM</summary>
<div>
<figure align="center">
  <p>아직 kubenetes, prometheus, exporter에 대한 이해가 부족해서 공부하면서 프로젝트를 진행하려니 시간이 다소 소모되었다.</p>
 </figure>
</div>
</details>


<details>
<summary>TRY</summary>
<div>
<figure align="center">
  <p>Grafana를 활용하여 Spark 지표를 모니터링 및 시각화 하도록 개선해야겠다.</p>
 </figure>
</div>
</details>

## 김도현
<details>
<summary>KEEP</summary>
<div>
<figure align="center">
  <p>목표와 해야할 일을 정해놓고 분업화가 원할하게 된 것</p>
 </figure>
</div>
</details>

<details>
<summary>PROBELM</summary>
<div>
<figure align="center">
  <p>프로메테우스나 exporter에 대한 이해가 부족해 팀원이 자신이 한 일을 설명해주어도 이해하는데 시간이 걸림</p>
 </figure>
</div>
</details>

<details>
<summary>TRY</summary>
<div>
<figure align="center">
  <p>컨테이너의 메모리 사용률이나 컨테이너의 네트워크 대역폭을 읽어올 수 있는 방법이 있다고 생각함.</p>
  <p>단순히 네트워크 대역폭 최대치나 메모리 용량 metric을 상수로 받아오는 것 보다는 컨테이너의 각 리소스 metric을 실제로 읽어오는 방식을 시도하고 싶음</p>
 </figure>
</div>
</details>

## 이상우
<details>
<summary>KEEP</summary>
<div>
<figure align="center">
  <p>1. 저번 프로젝트 보다 공유도 잘되고 분업도 잘된것 같다.</p>
  <p>2. 프로젝트를 진행하는 중에 JAM이 걸리지 않아서 프로젝트 완성속도나 프로세스 진행면에서 발전된 형태를 보였다.</p>
  <p>3. 최종 프로젝트를 대비해서 미리 체험해봐야할 오류를 경험한 듯한 느낌이다 .</p>
 </figure>
</div>
</details>

<details>
<summary>PROBLEM</summary>
<div>
<figure align="center">
  <p>1. 내가 일에 참여한 시간에 비해서 내 퍼포먼스가 좀 별로였다.</p>
  <p>2. 아직 새로운 영역의 기술을 사용하거나 기존 사용하던 기술에 조금 더 발전된 테크닉을 적용시키는데 어려움이 있는 것 같다.</p>
 </figure>
</div>
</details>

<details>
<summary>TRY</summary>
<div>
<figure align="center">
  <p>1. 사람이 빠져도 진행될 수 있는 팀을 구현하기 위해서 일정을 프로젝트 적용 (기술 + 태스크) 병렬형태로 짜봤으면 좋겠다.</p>
  <p>업무 진행상황, 어려움을 겪고있는 상황이나 진행이 잘 되지 않는 상황을 ISSUE로 적극적으로 공유해봤으면 좋겠다.</p>
 </figure>
</div>
</details>

## 이상훈
<details>
<summary>KEEP</summary>
<div>
<figure align="center">
   <p>분업이 잘된 느낌이고 공유가 잘됐다.</p>
 </figure>
</div>
</details>

<details>
<summary>PROBLEM</summary>
<div>
<figure align="center">
  <p>spark 등 툴에 대한 정확한 이해도가 부족해서 트러블 슈팅시간이 좀 걸렸다.</p>
  <p>전반적으로 학습이 더 필요하다는 느낌을 많이 받았다.</p>
 </figure>
</div>
</details>

<details>
<summary>TRY</summary>
<div>
<figure align="center">
  <p>전체적인 아키텍처를 사용하고자 하는 기술을 더해 구상할 수 있는 능력을 많이 길러야겠다.</p>
 </figure>
</div>
</details>

## 조하영
<details>
<summary>KEEP</summary>
<div>
<figure align="center">
  <p> 새로 배운 것을 프로젝트에 적용해본다는 점에서 의미 깊었다.</p>
 </figure>
</div>
</details>

<details>
<summary>PROBLEM</summary>
<div>
<figure align="center">
  <p> 코드에서의 문제가 없었으나 실행이 되지 않는 이유를 코드에서만 찾는 경향이 있다.</p>
 </figure>
</div>
</details>

<details>
<summary>TRY</summary>
<div>
<figure align="center">
  <p> 문법 이슈 외에 다른 환경설정 사항들도 고려해볼 것</p>
 </figure>
</div>
</details>

<br/>

## 🔍최종 검토 및 개선

### 1. **Spark 모니터링 (완료)**

- **Grafana 대시보드 개선**: Spark 성능 지표 추가 및 대시보드 개선
- **알림 시스템 설정**: 성능 이상 발생 시 알림 받도록 설정
- **클러스터 상태 모니터링**: 각 노드 상태 실시간 추적

---

### 2. **Spark Worker Manual Scale In/Out (완료)**

- **CPU 사용량에 따른 수동 Warker 스케일링 구현**
- **스케일링 정책 설정**: 임계치 확인 및 수동 스케일 아웃

---

### 3. **기타 개선/추가 사항**

- **에러 핸들링 및 로깅 개선**: 장애 시 알림 및 로그 기록
- **부하 테스트 환경 개선**: 다양한 시나리오 테스트 추가
- **CI/CD 파이프라인 설정**: 자동 배포 파이프라인 추가



