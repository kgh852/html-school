# CSS 텍스트와 목록, 표 스타일 정리

## 텍스트 스타일

### font-family : 글꼴 지정
- **구문**: `font-family: <글꼴명> [, <글꼴명>, ...];`
- 여러 글꼴을 쉼표로 구분해 순서대로 지정.

---

### font-size : 글자 크기
- **구문**: `font-size: <절대 크기> | <상대 크기> | <백분율>;`
- 절대 크기: 고정된 크기 (e.g., `16px`, `large`).
- 상대 크기: 부모 요소 기준 비율 (e.g., `1.5em`, `3rem`).
- 백분율: 부모 요소 기준 퍼센트 (`%`).

#### CSS 크기 단위
| 단위 | 설명 |
| --- | --- |
| `em` | 부모 요소 기준 대문자 M의 너비를 1em으로 사용 |
| `rem` | 루트 요소 기준 비율 |
| `px` | 화면 1픽셀 기준 |
| `pt` | 인쇄에서 사용하는 포인트 단위 |
| `ex` | 글꼴의 소문자 x의 높이 기준 |

---

### font-weight : 글자 굵기
- **구문**: `font-weight: normal | bold | bolder | lighter | 100 ~ 900;`
- 숫자값: 100~900 (`400`: 기본값, `700`: 굵게).

---

### font-style : 이탤릭체
- **구문**: `font-style: normal | italic | oblique;`

---

### color : 글자 색상
- **구문**: `color: <색상>;`
- 색상 표현: 16진수, RGB, HSL, 색상 이름 등.

---

### text-align : 텍스트 정렬
- **구문**: `text-align: start | end | left | right | center | justify | match-parent;`
- 주요 옵션:
  - `left`: 왼쪽 정렬.
  - `right`: 오른쪽 정렬.
  - `center`: 가운데 정렬.
  - `justify`: 양쪽 정렬.

---

### line-height : 줄 간격
- **구문**: `line-height: <숫자> | <백분율>;`
- 부모 요소 대비 비율 지정 가능.

---

### text-shadow : 텍스트 그림자
- **구문**: `text-shadow: none | <가로> <세로> <번짐> <색상>;`
- 주요 속성:
  - 가로/세로 거리: 그림자 위치.
  - 번짐: 음수는 축소, 양수는 확산.
  - 색상: 그림자 색.

---

### text-transform : 대소문자 변환
- **구문**: `text-transform: none | capitalize | uppercase | lowercase | full-width;`
- 주요 옵션:
  - `capitalize`: 단어 첫 글자 대문자.
  - `uppercase`: 모든 글자 대문자.
  - `lowercase`: 모든 글자 소문자.

---

### text-decoration : 텍스트 장식
- **구문**: `text-decoration: none | underline | overline | line-through;`
- 주요 옵션:
  - `underline`: 밑줄.
  - `overline`: 텍스트 위 선.
  - `line-through`: 취소선.

---

### letter-spacing, word-spacing
- `letter-spacing`: 글자 간격 조절. (`letter-spacing: <크기>;`)
- `word-spacing`: 단어 간격 조절. (`word-spacing: <크기>;`)

---

## 목록 스타일

### list-style-type : 불릿 모양과 번호 스타일 지정
| 종류 | 설명 | 예시 |
| --- | --- | --- |
| `disc` | 채운 원 | ● |
| `circle` | 빈 원 | ○ |
| `square` | 채운 사각형 | ■ |
| `decimal` | 숫자 | 1, 2, 3 |

---

### list-style-image : 불릿 대신 이미지 사용
- **구문**: `list-style-image: url(이미지 파일 경로);`

---

### list-style-position : 목록 들여쓰기
- **구문**: `list-style-position: inside | outside;`
- `inside`: 불릿을 목록 안쪽에 위치.
- `outside`: 기본값, 목록 바깥에 불릿 위치.

---

### list-style : 목록 속성 한 번에 설정
- **구문**: `list-style: <타입> <위치> <이미지>;`
- 예) `list-style: square inside;`

---

## 표 스타일

### caption-side : 캡션 위치 조절
- **구문**: `caption-side: top | bottom;`

---

### border-collapse : 테두리 설정
- **구문**: `border-collapse: collapse | separate;`
- `collapse`: 테두리 결합.

---

### border-spacing : 셀 간 여백
- **구문**: `border-spacing: <수평거리> <수직거리>;`
