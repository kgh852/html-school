### 배경색과 배경 범위 지정

#### background-color : 배경색 지정
- **구문**: `background-color: <16진수값> | <rgb, rgba> | <색상명>;`
- 배경색은 상속되지 않음.

---

### background-clip : 배경 범위 지정
- **구문**: `background-clip: border-box | padding-box | content-box;`

| **종류** | **설명** |
| --- | --- |
| border-box | 박스 모델의 가장 외곽인 테두리까지 적용 |
| padding-box | 패딩 범위까지 적용 |
| content-box | 콘텐츠 영역에만 배경 적용 |

---

## 배경 이미지 지정

### background-image : 배경 이미지 설정
- **구문**: `background-image: url(<파일 경로>);`
- 이미지가 배경으로 사용됨.

### background-repeat : 배경 이미지 반복 설정
- **구문**: `background-repeat: repeat | space | round | no-repeat;`
- 기본값은 `repeat`로 이미지를 반복하여 배경을 채움.

---

### background-size : 배경 이미지 크기 조정
- **구문**: `background-size: auto | contain | cover | <숫자> | <백분율>;`
  
| **종류** | **설명** |
| --- | --- |
| contain | 이미지가 요소 안에 맞춰 크기 조정 |
| cover | 요소를 완전히 덮도록 이미지 크기 조정 |

---

### background-attachment : 배경 이미지 고정
- **구문**: `background-attachment: scroll | fixed;`

| **종류** | **설명** |
| --- | --- |
| scroll | 화면을 스크롤하면 배경 이미지도 스크롤 |
| fixed | 스크롤해도 배경 이미지 고정 |

---

### background-position : 배경 이미지 위치 지정
- **구문**: `background-position: <수평위치> <수직위치>;`
  - 수평위치: `left`, `center`, `right`, `<백분율>`, `<길이 값>`
  - 수직위치: `top`, `center`, `bottom`, `<백분율>`, `<길이 값>`

---

### 그라데이션 효과

#### linear-gradient : 선형 그라데이션
- **구문**: `background: linear-gradient(to <방향>, <색상1>, <색상2>, ...);`
  - `to`와 함께 방향을 지정하거나 각도로 설정할 수 있음.
  - 색상 중지점 설정으로 부드러운 색상 변화를 만들 수 있음.

#### radial-gradient : 원형 그라데이션
- **구문**: `background: radial-gradient(<모양> <크기> at <위치>, <색상1>, <색상2>, ...);`
  - `모양`: `circle`(원형) 또는 `ellipse`(타원형).
  - `크기`: `closest-side`, `closest-corner`, `farthest-side`, `farthest-corner` 중 선택.
  - `위치`: 그라데이션이 시작되는 위치 지정.

---

### repeating-linear-gradient : 반복되는 선형 그라데이션
- **구문**: `background: repeating-linear-gradient(<방향>, <색상1>, <색상2>, ...);`
- 그라데이션이 반복되는 패턴을 생성하여 배경에 적용.
