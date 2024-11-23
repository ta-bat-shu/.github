# 국립한밭대학교 컴퓨터공학과 '타밭슈' 팀<br/>
### 🚲 한밭대인을 위한 큐싱 피해 방지 공유 자전거 어플리케이션
<br/>

#### 💻 **팀 구성 및 역할**
  - 🧑🏻‍💻 20222562 사민경(PM) : Front-End, 3D printer
  - 👩🏻‍💻 20202689 오민석 : DB 구축
  - 👩🏻‍💻 20211072 유재윤 : Back-End
  - 👩🏻‍💻 20231988 이지현 : Front-End
  - 👩🏻‍💻 20231991 임미란 : Arduino 통신
<br/><br/>

#### 🕹️ 기술스택
  - 🖥 Front-End :
      <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">
      <img src="https://img.shields.io/badge/Android%20Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white">
      <img src="https://img.shields.io/badge/Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white">
      <img src="https://img.shields.io/badge/MiriCanvas-FF7F50?style=for-the-badge&logoColor=white">
        
  - 💾 Back-End :
      <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white">
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=MongoDB&logoColor=white">
      
  - ❤️ 협업 :
      <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">
      <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white">

  - 💬 기타 도구 :
      <img src="https://img.shields.io/badge/ChatGPT-10A37F?style=for-the-badge&logo=openai&logoColor=white">
      <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white">
      <img src="https://img.shields.io/badge/3D%20Printer-F9A825?style=for-the-badge&logoColor=white">
<br/><br/>

## <u>Teamate</u> Project Background<br/>
### 📕기획안 >><br/>
![오픈소스sw프로그래밍_프로젝트-기획안](https://github.com/user-attachments/assets/3002b78e-c9ca-4be3-8a03-322091a0b474) <br/><br/>
    
### 📈 프로젝트 개요
- 배경 및 필요성<br/><br/>
공유 자전거 서비스는 현대 도시에서 친환경적이고 효율적인 교통수단으로 자리 잡았으나, 악성 QR코드 부착을 통한 큐싱 범죄가 증가하며 사용자 피해가 지속적으로 보고되고 있다. 특히, 이러한 보안 위협은 사용자의 개인정보 유출 문제와 사용자 신뢰도 하락을 초래하며, 이를 방치할 경우 서비스의 근본적인 지속 가능성이 흔들릴 수 있다. 이에 따라, 보안성과 편리성을 동시에 만족하는 자전거 대여 플랫폼을 구축한다.<br/><br/>
 
- 목적<br/><br/>
  타슈 API를 기반으로 큐싱 범죄 피해를 예방하고 사용자 편리성을 극대화한 자전거 대여 어플리케이션을 개발하는 것을 목표로 함<br/><br/>
  ✔️ 큐싱방지 : QR코드 URI 인식 및 자전거 고유번호 인식으로 자동 신고기능창 로딩 구현<br/><br/>
  ✔️ 사용자 경험 개선 : 간편한 인터페이스와 직관적인 UX를 설계하여 누구나 쉽게 이용가능 지원<br/><br/>
  ✔️ 기능 안정성 확보 : 모형 자전거와의 실증 실험을 통해 시스템의 완성도를 검증<br/><br/>
  
- ### 기대효과
  ✔️ 큐싱 피해 감소 : 보안 검증 시스템 도입으로 사용자들이 안심하고 자전거를 대여할 수 있는 환경 조성<br/><br/>
  ✔️ 서비스 신뢰도 증대 : 안정성을 강화함으로써 공유 자전거 서비스에 대한 신뢰를 회복하고 이용률 증가<br/><br/>
  
### 🎯 프로젝트 목표 [기능구현]<br/><br/>
> UX & UI
>> - 한밭대인을 위한 학번 로그인 기능
>> - 충전 및 마일리지 확인 / 이용내역 확인 / 신고창
>> - 근처 타밭슈 공유 자전거 찾기 기능 / QR스캔 대여 기능
>> - 악성 QR감지시 자동 신고창 로딩 기능 <br/><br/>

> 다중 중첩 보안
>> - 등록된 QR데이터 인식
>> - 자전거 고유번호 데이터 인식
>> - 악성 QR 및 잘못된 사이트 감지시 자동 신고창 로딩 및 데이터 전송
>> - 이상 감지된 공유 자전거 이용시 잠금 기능
>> - 여러 보안 기능 통해 인증된 공유 자전거 이용시 잠금 해제 기능 <br/><br/>

### 📅 추진 일정
  - 2024.09.19 목 (팀결성) ~ 2024.12.05 목 (최종발표일)<br/><br/>
