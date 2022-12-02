# 📸 MIRRORLESS 정품 & 빈티지 카메라 판매 플랫폼
## 🏆 POSCO  & CODING ON 프론트엔드 프로젝트 종합 1등

<br/>
- 유명 정품 카메라부터 감성있는 빈티지 제품들을 한번에 볼 수 있는 카메라 구매 사이트를 제작하였습니다.<br/>
- 팀원들과 함께 사이트의 프론트엔드 영역의 UI와 기능을 구현하였습니다. <br/>
<br/>
⏱ 개발 기간 : 2022년 8월 1일 ~ 14일 (2주)<br/>

🖥 플랫폼 : Web (Frontend Page)

🔗 page link : <a>https://tranquil-lily-687501.netlify.app/</a>

👩🏻‍💻 개발 인원 

: 프론트엔드 3명 (강유림, 이소민, 모승환)

: 백엔드 1명 (모승환)
<br/><br/>
<img width="400" alt="aboutus_part" src="https://user-images.githubusercontent.com/105038512/188182587-c5a9c36c-5a76-4dc9-8172-16699516cdac.png">

### 개발 환경

언어 : HTML, CSS, SCSS, JAVASCRIPT

라이브러리 : Swiper, Gsap, Jquery

보조 프로그램 : Illustration

<br/>

### 페이지 제작 의도

<img width="700" alt="aboutus1" src="https://user-images.githubusercontent.com/105038512/188183380-8634d1a2-09b7-444a-b652-b1d9df7fa8d0.png">

<img width="700" alt="aboutus3" src="https://user-images.githubusercontent.com/105038512/188183396-815487b5-c42c-4e67-9b09-adf12e72c04e.png">


https://user-images.githubusercontent.com/105038512/188183405-22636e67-a42e-44cc-b370-e503edb09623.mov

<br/><br/>

### 페이지 주요 기능 6가지 (직접 구현한 기능만 작성)

### 1. **web page의 전체 디자인 컨셉 진행**

<img width="1000" alt="스크린샷 2022-09-03 오전 12 36 13" src="https://user-images.githubusercontent.com/105038512/188186245-fdace185-80d9-476b-8f2a-f6b6d214fbf9.png">
- 사용자의 타겟 연령층과 취향을 고려하여 orange, black을 메인 컬러로 사용하였습니다.<br/>
- 글씨체, 각 요소의 크기 등 bold하고 깔끔한 분위기로 연출하였습니다.<br/>
- detail 페이지 → All 페이지 illustration으로 카메라 크기를 균일하게 수정하여 연출하였습니다.<br/>


![mirrorless1 (1)](https://user-images.githubusercontent.com/105038512/186224508-450f577e-d6e0-4153-8520-12017bf59e69.gif)

### 2. **keyframe을 이용하여 img애니메이션 기능 구현**

- img를 illustration으로 이미지를 편집하여 3개의 이미지를 편집하여 사용하였습니다.
- keyframe의 transition과 scale을 사용하여 구현하였습니다.

### 3. **Scroll 시 각각의 이미지가 기존 돌아오는 기능 구현 (Gsap라이브러리 활용)**

- gsap라이브러리 추가 후 javascript에서 페이지의 특정 Y값에서 각각의 이미지 요소들의 scale이 작아지도록 구현하였습니다.
- 전체적인 디자인을 bold한 컨셉으로 진행하였기 때문에 각각의 카메라가 유별나게 튀어보이지 않도록 scroll 시 작아지는 효과를 통해 강조하였습니다.

### 4. 카메라 포스터에 mouseover했을 때 카메라 img 크기 커지는 기능

- SCSS, CSS의 position 속성을 활용하였습니다.
- mouseover 하였을 때 포스터 이미지에서 ‘카메라’만 강조될 수 있도록 구현하였습니다.


### 5. 다양한 색상의 카메라가 자동으로 보여지는 기능
https://user-images.githubusercontent.com/105038512/188183850-f2105de7-abdb-4971-af02-776d18a1c679.mov

- 카메라를 Custom할 수 있는 프로모션 강조를 위하여 같은 카메라의 다양한 색상이 보여지도록 하였습니다.
- javascript의 배열을 생성한 후 순서대로 이미지가 보여질 수 있도록 구현하였습니다.


### 6. 카메라 구매페이지에서 기능 구현
https://user-images.githubusercontent.com/105038512/188183977-c5faaad4-1d75-4dd8-a7f1-c8ec6fe30de6.mov

- 수량 : 증/감에 따라 숫자 변경, 총 금액 변경
- 컬러 : 컬러 선택 시 해당 컬러 출력
- 이모지 : 이모지 선택 시 input box에 이모지가 출력
- input창의 아이콘 선택 시 회전되면서 List 나타나기, 선택 시 페이지 이동


