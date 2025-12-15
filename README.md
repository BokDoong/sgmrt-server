# 고스트러너

<img width="1500" height="800" alt="image" src="https://github.com/user-attachments/assets/81ffec36-6c2c-48d1-b598-39a268052ef6" />

언제 어디서나 함께 달리는 고스트러너
([🔗 앱스토어 바로가기](https://apps.apple.com/kr/app/ghostrunner/id67477))

<br><br>

## 프로젝트 소개📄

- 📆 프로젝트 기간 : 2025.06.01 ~
- 고스트러너는 코스 지도를 통해 주변 러닝 코스를 탐색하고 과거 기록과의 경쟁을 통한 러닝에 대한 지속적인 동기를 부여한다. 여기에 사용자 데이터 기반의 맞춤형 AI 고스트로 훈련 방향성과 성장을 강화함으로써 러너가 시작 - 지속 - 성장으로 이어지는 선순환 경험을 체계적으로 구축하도록 돕는다.

<br><br>

## 프로젝트 기술 스택💻

#### 📌 프로그래밍 언어 및 프레임워크
- Java, Spring MVC
- MySQL, Redis
- AWS Beanstalk, AWS CodePipeline, AWS Route53, AWS S3
- OpenAI

#### 인프라 환경
<img width="1100" height="900" alt="image" src="https://github.com/user-attachments/assets/611ba073-b589-47da-9b93-2e4b4f18ce3c" />

## 프로젝트 주요 기능⚙️

### 코스 탐색 및 러닝

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/271fadda-6533-4c1c-8bd6-68dd6a3de3c6" />

- 코스 지도에서 주변 러너들이 러닝 후 등록한 주변 코스를 확인할 수 있다.
- 러닝 시작부터 종료 시점까지의 생체 데이터를 기록한다. 러닝 도중의 페이스, 완주 거리, 케이던스, 심박수 등을 확인할 수 있다.
- 러닝을 마치면 코스 공개 여부를 선택하고, SNS를 통해 공유할 수 있다. Apple Fitness 연동을 통해 타 러닝 앱에서도 확인 가능하다.

### 고스트와 러닝

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/82fb81c8-c8c5-406d-a685-d09171101280" />

- 자신의 과거 최고 기록과 함께 달릴 수 있다.
- 달리는중에는 거리 차이와 추월하고 당하는 등의 이벤트 기반 음성 안내를 제공받는다.
- 러닝 후 고스트와 비교한 기록을 확인할 수 있다.

### AI 고스트 ( 고스티 ) 

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b859e5e6-0fa8-4fb4-b452-73d1eccf40ce" />

- AI를 통해 가상의 고스트를 만들 수 있다. 이때, 사용자의 맞춤형 훈련표 형태로 제공된다.
- 사용자가 입력한 러닝의 목적, 컨디션을 바탕으로 내부적으로 VDOT(러닝 퍼포먼스) 기반 Rule-Base 훈련표와 사용자의 정보(나이, 성별, 몸무게 등)을 바탕으로 LLM을 통해 가공한다.

### 코스 네비게이션 & 애플워치 연동

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/12bac908-4a79-48ef-83b2-81841415bc2b" />

- 낯선 코스를 달리는 사용자를 위해 코너(꺽는 지점)에서 시계 방향의 음성 안내를 제공한다.
- 일반 러닝에는 애플워치를 연동해 함께 달릴 수 있다.
