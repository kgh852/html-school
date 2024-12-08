### 박스 모델(Box Model)

#### 구성 요소
- **콘텐츠(Content)**: 실제 내용이 들어가는 영역.
- **패딩(Padding)**: 콘텐츠와 박스 테두리 사이의 여백.
- **테두리(Border)**: 박스를 둘러싼 경계선.
- **마진(Margin)**: 박스와 다른 요소 간의 외부 여백.

---

### width, height : 가로 세로 크기 설정
- **구문**: `width: auto | <크기> | <백분율>;`
- **특징**:
  - 기본값은 `auto`.
  - 부모 요소 크기에 따라 `%`로 반응형 설정 가능.
  - 콘텐츠가 넘칠 경우, 스크롤이 발생할 수 있음.

---

### max-width, max-height : 최대 가로/세로 크기
- **구문**: `max-width: auto | <크기> | <백분율>;`
- **특징**:
  - 콘텐츠 크기를 부모 요소보다 크지 않게 제한.
  - 반응형 이미지에서 자주 사용.

---

### box-sizing : 박스 크기 계산 방식
- **구문**: `box-sizing: border-box | content-box;`
- **종류**:
  - `border-box`: 테두리와 패딩을 포함한 너비.
  - `content-box`(기본값): 콘텐츠만 기준으로 너비를 계산.

---

### 테두리(Border) 스타일
#### border-style
- **구문**: `border-style: none | dashed | dotted | solid;`
- 방향별 설정 가능: `border-top`, `border-right`, `border-bottom`, `border-left`.

#### border-width
- **구문**: `border-width: thin | medium | thick | <크기>;`

#### border-color
- **구문**: `border-color: <색상>;`

#### border
- **구문**: `border: <스타일> <너비> <색상>;`

#### border-radius : 둥근 테두리
- **구문**: `border-radius: <크기> | <백분율>;`
- 방향별 설정 가능: `border-top-left-radius` 등.

---

### 여백(Margin)과 내부 패딩(Padding)
#### margin
- **구문**: `margin: <크기> | <백분율> | auto;`
- 가운데 정렬: `margin: auto;` (단, 요소 크기가 명시되어야 함).

#### padding
- **구문**: `padding: <크기> | <백분율>;`
- 콘텐츠와 테두리 사이의 간격 설정.

#### 마진 중첩 현상
- 세로 방향으로 배치된 요소의 마진이 겹쳐지며 큰 값으로 통합됨.

---

### 박스 그림자 (box-shadow)
- **구문**: `box-shadow: <수평> <수직> <흐림> <번짐> <색상> inset;`
- **옵션**:
  - `inset`: 그림자가 내부로 들어감.
  - 흐림과 번짐 값 조정으로 효과 다양화 가능.

---

### 테두리와 여백의 설정 순서
- 4개 방향 설정 시 순서: **상단 → 우측 → 하단 → 좌측**.
