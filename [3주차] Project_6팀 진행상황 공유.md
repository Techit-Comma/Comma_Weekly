## 팀 구성원, 개인 별 역할

---
- 조유민[팀장] - React Album Release 등 페이지 개발
- 조동국 - 알람 기능 마무리 , React Cookie, Main Page 등 페이지 개발
- 박상혁 - React Credit , Tosspayments 등 페이지 개발

## 팀 내부 회의 진행 회차 및 일자

---
1회차(2024.03.13) 프로젝트 고도화
   - 프론트 관련 회의 진행

2회차(2024.03.15) 보고
   - 개인별 진행상황 보고
   - 전체 일정 점검

## 현재까지 개발 과정 요약
조유민
- Album Release File Upload 모달 팝업 개발
    - Album을 업로드 시 기존에 한번에 처리했던 페이지에서 모달로 변경해 사전에 작업 후 처리
- Album Release Image Upload 모달 팝업 개발
    - File과 마찬가지로 미리보기를 기존에 파일을 업로드 받아 처리 후 메인 페이지에서 앨범 수정
- Album Release Page 수정
    - 위에서 가져온 Album 정보를 토대로 Release Page 개발 및 디자인적 수정

박상혁
- 토스페이먼츠 결제 기능 프론트 구현
    - 모달 이용하여 결제 진행
- Credit 메인페이지 프론트 작업
    - 잔여 크레딧, 크레딧내역, 출금 신청 내역

조동국
- 앨범 알림 기능 마무리
    - BackEnd에서 앨범 알림 기능 마무리
- React Cookie 기능 수정
    - Cookie 재발급 기능 구현 및 에러 해결
- React Main 페이지 구현 시작
    - Main 페이지에 나오는 여러 태그별 앨범 및 디자인적 표시 화면
---
## 개발 과정에서 나왔던 질문
- Album Modal에서 다음 모달로 변경 시 어떤 방식으로 해야 하는가?
    - 하나의 코드에서 변경 하기로 함. 내용만 변경 및 Count를 올려 순서대로 처리
- Album Modal의 디자인적 기능을 올리기 위해 어떠한 기능을 써야 할까?
    - MUI Modal 중 오픈 소스로 개발 된 MUI Dropzone 을 Import해 사용.
    - 실제 유저가 버튼이 아닌 전체적인 큰 칸을 사용할 수 있도록.
- Component에서 API요청시 오류 발생
    - use client 사용하여 Client 쪽에서 랜더링하도록 변경
- API 요청 성공 후 다른 페이지로 이동 처리하는 방법
    - Router 기능 사용하여 이동 하게끔 처리
---
## 개발 결과물 공유

---

- Github Repository URL: https://github.com/Techit-Comma
- Notion : https://likelion.notion.site/6-e7ff60a1b88041379f19ce1d75d1997f
