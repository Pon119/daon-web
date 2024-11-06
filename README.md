[![daon](https://github.com/user-attachments/assets/a3256e34-4344-4a52-b753-7ee4b3517bdb)](https://qodql.github.io/daon/)

<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/Sass-CC6699?style=flat-square&logo=Sass&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>

## 🏕 다온펜션 리뉴얼 프로젝트

기존의 '다온펜션' 사이트를 리디자인 및 재구성한 리뉴얼 프로젝트입니다.

![daon_main](https://github.com/user-attachments/assets/5a9f5349-b190-457e-961a-282c00bf717b)

## 🔗 사이트 URL

- 기존 <http://www.daonpension.kr/>
- 리뉴얼 <https://qodql.github.io/daon/>
<!-- - [개인](https://0011git.github.io/daon/) -->

## 📑 개요

1. **주제**
   - '다온펜션' 사이트 리뉴얼
2. **목표**
   - 전반적으로 노후화된 기존 사이트를 리뉴얼해 사용자 경험을 개선하고 만족도를 높이는 것을 목표로 함
3. **개발 환경**
   - HTML, SCSS, Vanilla Javascript
4. **기간 및 인원**
   - 2024.06.19 ~ 2024.09.12 (86일), 5인

## 🙌 담당 직무

|    이름    |                   GitHub                    |     직무     | 해당 |
| :--------: | :-----------------------------------------: | :----------: | :--: |
|   이한주   | [Lee-Hanjoo](https://github.com/Lee-Hanjoo) | 팀장, 디자인 |      |
|   성주영   |    [0011git](https://github.com/0011git)    | 리소스 수집  |      |
|   윤경빈   |      [qodql](https://github.com/qodql)      |     배포     |      |
|   이홍영   |    [Infouse](https://github.com/Infouse)    |     개발     |      |
| **허다영** |   **[Pon119](https://github.com/Pon119)**   |   **기획**   |  ✔   |

## 💡 새로 추가된 주요 기능들

1. **메인 페이지 예약 퀵메뉴**

   - 날짜, 인원 등 세부항목 선택 가능한 예약 퀵메뉴를 메인에 추가하여 예약 기능에 빠르게 접근할 수 있도록 지원

2. **회원가입 및 로그인**

   - sns 로그인 (카카오, 네이버, 구글) 지원
   - 이메일, 비밀번호 등의 입력값 유효성 검사
   - 회원가입 완료와 동시에 로그인이 이루어지도록 함

3. **ChannelIO(채널톡) 챗봇 실시간 상담 서비스**

   - [채널톡](https://developers.channel.io/reference/welcome-to-channel-kr) 사용
   - 채널봇 구동에 필요한 자바스크립트 추가
   - 챗봇의 홈과 대화방을 사이트 주제에 알맞은 내용으로 커스텀, 운영 시간 설정

4. **OpenWeather API 날씨**

   - [OpenWeather API](https://openweathermap.org/) 사용
   - 펜션의 위도 및 경도값으로 실시간 날씨 정보를 불러와 우측 하단 퀵메뉴에 노출

5. **카카오맵 API 지도**

   - [카카오맵 API](https://apis.map.kakao.com/web/) 사용
   - 메인과 about-오시는 길 페이지에서 사용

6. **반응형 웹**

   - 모바일 스몰(~479px), 모바일 라지(480\~767px) 태블릿(768\~1279px), PC(1280px\~) 해상도 지원

7. **예약 달력 기능**
   - [Tui Datepicker](https://ui.toast.com/tui-date-picker) 라이브러리 사용
   - cookie와 localstorage에 데이터를 저장한 후 다른 페이지에서도 불러올 수 있게 작업

## 📚 참고 URL

- 기획 및 화면 설계 :
  [daon Figma](<https://www.figma.com/design/1zlcRdL0iDs2TWlgb5Thoq/240618_%EB%8B%A4%EC%98%A8%ED%8E%9C%EC%85%98-(Copy)?node-id=0-1&node-type=canvas&t=QkvAdj1lJY9kWkMd-0>)
- 1차 계획 ppt :
  [daon Canva](https://www.canva.com/design/DAGIplQ9SSA/yVOa3ghyW9enxSPvzQCcVw/edit?utm_content=DAGIplQ9SSA&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
- 발표 ppt :
  [daon Canva](https://www.canva.com/design/DAGPld1e67I/bYGbjtRsdfuDOY-Lullv-w/view?utm_content=DAGPld1e67I&utm_campaign=designshare&utm_medium=link&utm_source=editor)

<!--## 📱 스크린샷 : 개인거 말고 팀꺼에 넣기 -->

---

## 🙋‍♀️ 담당 개발 상세 : 허다영

- **담당 직무** :
  기획
- **담당 페이지** :
  [시설 안내](https://pon119.github.io/daon-web/sub3_facilities.html), [FAQ](https://pon119.github.io/daon-web/sub5_community_faq.html)

- **담당 주요 기능** :
  - 인터페이스 기능 :
      - 스와이퍼 기능 추가 
      - 탭 기능을 추가하여 원페이지에서 모든 시설 정보를 조회할 수 있도록 편의성 제공
  - 시스템 기능 :
    - 키워드별 검색 기능 제공

## ⛳ 시설 안내 페이지

<p align="center">
<img src="https://github.com/user-attachments/assets/63ca187a-9908-48b0-b196-a6a74b080428">
</p>

1. **데이터 수집**

- 시설 안내의 바베큐, 옥상 정원, 야외 수영장 3개의 카테고리만큼 
3페이지로 구분되어 있었던 것을 1개의 페이지에서 탭 기능을 통해 확인할 수 있도록 진행

   1-1 처리 순서

   1) 1차적으로 JSON에 사용자가 확인할 내용을 DATA 처리 진행
      (DATA 처리 구분: 
      ITEM – 각 항목별 페이지(BBQ, 옥상 정원, 야외 수영장) - 타이틀/IMG/TEXT로 구분)

   2) JSON DATA 처리 후 해당 내용들을 JS의 INNET HTML에 적용. (예시: ${data.img[0]})

      각 JSON의 값이 자동 갱신되도록 데이터 처리 진행
   유저가 각 항목별 클릭을 진행하였을 때의 상황을 가정하여 케이스 3개를 지정.
   이를 swich를 이용하여 내용이 갱신되도록 함 

   3) 서버와 비동기적으로 통신하여 페이지를 새로고침 하지 않고도 데이터를 받을 수 있도록 진행
   pageType을 선언하여 로컬스토리지에 데이터값을 저장하도록 함. 
   지정된 값이 노출되지 않는다면, 아래와 같이 값을 지정하여 
   기본 옵션으로 바베큐 화면이 노출될 수 있도록 설정.
   ```     
    let pageType = Number(localStorage.num) || 0; 
    ```

   저장된 데이터값을 이용하여 한 페이지에서 값을 저장하여 불러올 수 있도록 함.
   이를 통해 유저에게 실시간 피드백 제공

- 시설 안내의 ‘바베큐’ ‘옥상정원’‘야외 수영장’ 3개의 페이지를 
   탭 기능을 추가하여 한 개의 페이지에서 모두 확인할 수 있도록 재구성함. 
   기존에 무분별하게 배치되었던 시설 이미지를 JS.슬라이드 기능을 추가하여 이용성을 높힘.
- 슬라이드 기능의 경우,
   json data 처리 항목에서 이미지를 함께 json data 처리를 통해 제어할 수 있도록 하며, 슬라이드 “기능”만 swiper 홈페이지에서 가져와서 적용하도록 함

## 🔍 Faq 페이지

<p align="center">
<img src="https://github.com/user-attachments/assets/9c573735-a6d4-407c-bb84-2a9a122caf25">
</p>

1. **데이터 수집**

- 각 키워드에 맞는 질문/답변을 재배치하여 JSON DATA 작업을 통해 나눔.
  이후 JS 기능을 통해서 각 동작 값을 부여하여 사용성을 높힘

```
(JSON DATA 처리 구분:
ITEM – (T/Q/A) 한 묶음으로 지정하여 각 타이틀, 질문, 답변을 나뉘어서 구성 진행
* T-타이틀(예약, 시설, 키워드별 항목)
  Q-질문 (EX. 객실은 어떤 종류가 있나요?)
  A-답변(EX.I LOVE YOU/ONLY YOU 두 종류가 있습니다.)
```

- 처리 순서
  1. 1차적으로 JSON에 사용자가 확인할 내용을 DATA 처리 진행
  2. JSON DATA 처리 후 해당 내용들을 JS의 INNET HTML을 적용 (예시: <p>${item.q}</p>)
     INNER HTML로 적용한 내용들을 IF로 묶어 디폴트 값으로 페이지 첫 진입, 새로고침 진행할 경우
     ‘전체’질문이 노출될 수 있도록 처리
     (예시: if (item.t == type || type == "all") )
  3. DOM 조작:
     JSON 데이터로부터 질문과 답변을 동적으로 생성 및 유저 클릭에 따라 전환할 수 있도록 함.
     해당 기능을 위해서 위와 같이 SWICH를 사용하여 각 타입(예약, 시설, 오시는 길, 기타)를 설정.

```(예시: switch (item.t)
            case "예약":
              t = col[0];
              break; … 생략 )
```

- 이벤트 처리
  - 사용자가 질문을 클릭하면 해당 질문의 답변을 표시하거나 숨김처리 진행
    해당 기능은 forEach을 1차적으로 값을 구함.
    이후 onclick 이벤트를 추가하여 classList.add (‘active’)값을
    추가 및 remove 기능을 통해 제거함


## 💥 트러블 슈팅

1. **FAQ**
 - 헤더에 배치되어 있는 카테고리 (바베큐, 옥상정원, 야외 수영장)을 클릭 시 
개별 페이지로 생성 및 이동되는 이슈 발생.

   ***해결 방안*** 
   localStorage에 데이터 넘버를 부여하여 페이지 값을 연결시켜 이동될 수 있도록 우회함


<!-- 이미지 or gif -->
