# 3-8. CSS - 그리드 레이아웃

## 그리드 레이아웃이란?

CSS 그리드 레이아웃은 화면을 행(row)과 열(column)으로 나누어 2차원적으로 배치하는 방식이야.  
플렉스박스는 한 축(가로 또는 세로)만 사용하지만, 그리드는 **가로와 세로**를 둘 다 사용할 수 있어.  

- **플렉스박스**: 1차원 레이아웃 → 한 방향(가로/세로) 배치
- **CSS 그리드**: 2차원 레이아웃 → 복잡한 레이아웃에 유용  

---

## `display`: 그리드 컨테이너 만들기

그리드 레이아웃을 사용하려면 부모 요소에 `display: grid`나 `display: inline-grid`를 지정해.  

---

## `grid-template-columns` & `grid-template-rows`

- **열(column)**과 **행(row)**의 개수와 크기를 설정
- 예시: `grid-template-columns: 100px 200px 1fr;`

---

## 반복되는 값: `repeat()`, 최소/최대값: `minmax()`

- `repeat()`: 같은 값을 반복해서 짧게 쓰기
- `minmax()`: 최소/최대 크기 설정  

---

## 자동으로 공간 채우기: `auto-fit`, `auto-fill`

- 화면 크기에 따라 열의 개수를 자동으로 조절  

---

## 항목 간격: `gap`

- 그리드 항목 간의 간격을 설정하는 속성  

---

## 그리드 라인 사용하기

- **열**: `grid-column-start`, `grid-column-end`, `grid-column`  
- **행**: `grid-row-start`, `grid-row-end`, `grid-row`  

---

## 템플릿 영역: `grid-template-areas`

- 그리드 항목을 영역으로 나누어 배치  

```css
.grid-container {
  display: grid;
  grid-template-areas: 
    "header header"
    "main sidebar"
    "footer footer";
}
