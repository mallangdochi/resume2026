# 💻 정종범 개인 포트폴리오 웹사이트 (Jeongbeom Portfolio)

프론트앤드 기술과 모션 그래픽 요소를 웹 디자인에 녹여낸 반응형 인터랙티브 포트폴리오입니다.

단순한 자기소개나 텍스트 나열을 넘어, 방문자가 직접 클릭하고 경험할 수 있는 동적인 요소(룰렛, 3D 플립 등)를 한 페이지에서 직관적으로 확인할 수 있도록 제작했습니다.

<br>

## 🎥 프로젝트 미리보기

<img width="1872" height="1280" alt="image" src="https://github.com/user-attachments/assets/816a78b9-3163-41af-ada9-c1dec9904920" />


<br>

## 🔗 배포 주소

* **Portfolio Website** :https://mallangdochi.github.io/resume2026/

<br>


## 🛠️ 사용 기술

**Front-end**
* HTML5
* CSS3
* JavaScript (Vanilla)

**Design & Video**
* Premiere Pro
* After Effects
* Figma

**Tools**
* Git / GitHub
* VS Code

<br>

## 🎯 **프로젝트 목표**
* 눈에 피로감이 덜한 페이지 만들기
* CSS Grid와 Flexbox를 활용한 직관적이고 깔끔한 반응형 레이아웃 구성
* AI를 이용한 JavaScript 사용
* GitHub Pages를 이용한 웹사이트 배포 프로세스 습득

<br>

## ✨ **주요기능**
* 👤 **Hero & Profile**
  기본 인적 사항과 핵심 역량을 보여주는 메인 섹션

* 🎡 **Interests (인터랙티브 룰렛)**
  JavaScript를 활용하여 관심사 4가지를 랜덤으로 뽑는 기능
  버튼 클릭 시 회전 애니메이션과 함께 결과 팝업 출력

* 💻 **Development Skills (모달 팝업)**
  JS 없이 HTML Checkbox와 CSS만을 활용한 가볍고 빠른 스킬 상세 보기 팝업 구현

* 💼 **Work Experience (3D 플립 카드)**
  CSS 3D Transform을 활용해, 마우스 오버 시 카드가 180도 뒤집히며 상세 업무 성과가 나오는 입체적인 명함 형태 구현

<br>

## 🚧 **어려웠던 점**
1. 🧩 스킬 카드에 링크(a 태그)를 추가하는 과정에서 레이아웃 붕괴 (첫 번째 카드를 제외한 나머지 카드가 밖으로 밀려남).
   - 코드 확인 결과 기존 팝업을 지우면서 `</div>` 닫는 태그가 하나 더 남아 Grid 컨테이너가 일찍 닫힌 것을 발견, 불필요한 태그를 지워 원래 구조로 복구.

2. 📱 반응형 과정에서 계속 오른쪽이 비는 상태가 계속됨
   - `min-width`가 아닌 `max-width`로 되어있는 것을 발견 후 수정
   - `flex-direction`을 `column`에서 `row`로 변경

3. 🔧 인터랙티브 룰렛이 반응형 시 크기가 변하지 않음
   - CSS 미디어 쿼리(`@media`)를 사용하여 화면 너비가 `768px` 이하일 때 `.wheel`의 너비/높이를 줄이고, 내부에 눕혀진 `.text-item`의 폰트 사이즈와 패딩을 비율에 맞게 조정하여 모바일에서도 깨지지 않는 완벽한 반응형 룰렛을 구현함.
</div>
</details>

<br>

## 📬 Contact

**정종범**
* **GitHub** : https://github.com/mallangdochi
* **Email** : whdqja6943@gmail.com
