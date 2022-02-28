# 꽃 쇼핑몰 웹 페이지

## 프로젝트 소개

> Vanila JavaScript만을 활용하여 꽃 쇼핑몰 페이지를 구현하였습니다.

| 팀 구성 | 담당                  |
| ------- | --------------------- |
| 이현호  | Footer, iframe 동영상 |
| 박훈주  | GNB                   |
| 윤창현  | 배너, 팝업창          |
| 이주영  | 플라워클래스 섹션     |

### member

<table>
  <tr>
        </td>
      <td align="center">
      <a href="https://github.com/LEEHYUNHO2001"
        ><img
          src="https://avatars.githubusercontent.com/LEEHYUNHO2001"
          width="100px;"
          alt=""
        /><br /><sub><b>이현호</b></sub></a>
    <br />
    </td>
    <td align="center">
      <a href="https://github.com/hoonjoo-park"
        ><img
          src="https://avatars.githubusercontent.com/hoonjoo-park"
          width="100px;"
          alt=""
        /><br /><sub><b>박훈주</b></sub></a
      ><br />
    </td>
    <td align="center">
      <a href="https://github.com/Yoon-CH"
        ><img
          src="https://avatars.githubusercontent.com/Yoon-CH"
          width="100px;"
          alt=""
        /><br /><sub><b>윤창현</b></sub></a
      ><br />
    </td>
    <td align="center">
      <a href="https://github.com/devjoylee"
        ><img
          src="https://avatars.githubusercontent.com/devjoylee"
          width="100px;"
          alt=""
        /><br /><sub><b>이주영</b></sub></a
      ><br />
  </tr>
</table>

<br />

## 사용 기술 및 스택

- Stack
  - JavaScript, HTML5, SCSS
  - Babel
  - Deploy : Netilfy
  - Other : Git / GitHub
  - Code Quality Tool (Prettier)

<br />

## 주요 기능 구현 설명

### 팝업 창
- 초기 HTML 문서를 완전히 불러오고 분석했을 때 발생하는 `DOMContentLoaded` 이벤트에 쿠키에 저장된 값을 확인하는 함수를 부여하였습니다.
- 최초 팝업 창에서 `오늘은 더 이상 보지 않기` 체크박스를 선택하면 그 기억된 값을 쿠키에 저장시키고 X 버튼을 눌러 팝업 창을 숨기게 하였습니다.
- 이를 통해 쿠키에 저장된 여부에 따라 하루동안 팝업을 보이지 않게하는 기능과 단순 제거 기능을 부여한 팝업 창을 구현했습니다.
<img width="500" alt="팝업창" src="https://user-images.githubusercontent.com/87757602/155990242-0db4c4df-7053-47e3-9602-1d9ae761a40f.png">

### 배너
- 하단 배너에 background-image를 입혀 hover 시 이미지만 부드럽게 확대되는 기능 구현
<img width="500" alt="배너" src="https://user-images.githubusercontent.com/87757602/155990250-16afc41f-f3b0-4f44-a9ee-6c4b423bd8e7.png">


### GIF 렌더링 시 쿠키 여부를 확인하여 팝업창 재렌더링 여부 구현 (오늘 더 이상 보지 않기 클릭 여부) 및 배너 확대 애니메이션
![꾸까 기능](https://user-images.githubusercontent.com/87757602/155990282-873ae465-855a-4ac6-a5b6-b242cf6ef2c0.gif)

<br />

## CRA 구조

```markdown
src
│
├─public
│ ├── css
│ └── index.html
│
└──src
├── images
├── js
├── script
│ └── cross
└── scss
```

<br />

## 커밋 컨벤션

깃모지를 사용하여 직관성을 높이고, 기능이나 UI 설계에 따른 메세지를 커밋 메세지에 담는것을 컨벤션으로 결정했습니다. 깃모지로 인해 상대방이 어떤 작업을 수행했는지 한 눈에 확인할 수 있고, 메세지를 보며 조금 더 상세한 상황을 파악할 수 있습니다.

| 깃모지 | 사용 예시               |
| ------ | ----------------------- |
| 🎉     | init                    |
| 🚚     | 디렉토리 또는 파일 이동 |
| ✨     | 기능 구현               |
| 💄     | CSS 스타일링            |
| ♻️     | 리팩토링                |
| 📝     | Readme 수정             |
| ➕     | 모듈 추가               |
| 🐛     | 버그 해결               |
| 🚑️    | 치명적인 오류 해결      |

<br />

## 과제 후기

### 윤창현 ✨

바닐라 자바스크립트를 이용하여 프로젝트를 진행하면서 기본기의 중요성을 다시 한 번 깨달았습니다. 그동안 새로운 기술과 react에 중점을 두었다면, 앞으로는 프론트엔드 개발자로서 기본기에 중심을 두고 공부를 하고 탄탄하게 성장해야겠다는 다짐을 하게 되는 시간이었습니다.
