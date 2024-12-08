### display : 블록 레벨 요소, 인라인 레벨 요소를 바꿀 때 사용

#### display 속성
- **구문**: `display: block | inline | inline-block | none;`

| **종류** | **설명** |
| --- | --- |
| block | 인라인 요소를 블록 요소로 바꿈 |
| inline | 블록 요소를 인라인 요소로 바꿈 |
| inline-block | 인라인과 블록 요소의 속성을 모두 가지고 있으며 마진, 패딩 지정 가능 |
| none | 해당 요소를 화면에 표시하지 않음 |

---

### float : 요소를 왼쪽이나 오른쪽에 띄움(수평정렬)
- **구문**: `float: left | right | none;`
- 다른 요소에 영향을 주지 않으면서 자연스럽게 배치할 수 있음.

---

### clear : float 속성 무효화
- **구문**: `clear: left | right | both;`
- float의 흐름을 무효화하고 다음 라인으로 이동하여 배치.

---

### position : 웹 문서 내 요소 배치(x,y축)

#### position 속성
- **구문**: `position: static | relative | absolute | fixed;`

| **종류** | **설명** |
| --- | --- |
| static | 기본값. 다른 태그와의 관계에 의해 자동 배치, 위치 지정 불가 |
| relative | 이전 요소에 자연스럽게 연결하여 배치하고, 위치 지정 가능 |
| absolute | 가장 가까운 `relative` 부모 요소를 기준으로 상하좌우 배치. 부모가 없으면 `body` 기준 |
| fixed | 다른 요소와 상관없이 뷰포트를 기준으로 고정 배치, 스크롤해도 움직이지 않음 |

---

### z-index : 우선순위에 따라 화면 전면 배치(z축)

#### z-index 속성
- **구문**: `z-index: <숫자> | auto;`
- 숫자가 클수록 전면으로 배치되며, `position`이 `static`인 요소에는 적용되지 않음.

---

### overflow : 자식 요소가 부모 요소를 벗어났을 때 처리 방법

#### overflow 속성
- **구문**: `overflow: visible | hidden | scroll | auto;`

| **종류** | **설명** |
| --- | --- |
| visible | 부모 영역을 벗어난 부분도 표시 |
| hidden | 부모 영역을 벗어난 부분 잘라냄 |
| scroll | 부모 영역을 벗어난 부분에 스크롤 표시 |
| auto | 벗어난 부분이 있을 때만 스크롤 표시 |
