# HTML 태그 - Body, Form 관련 태그

## Body 태그
- `body`: 웹 문서의 본문 내용을 표시하는 태그.  
  - 모든 화면에 표시되는 콘텐츠는 `body` 태그 안에 작성된다.

---

## Form 태그
### `form`
- 사용자로부터 데이터를 입력받아 서버로 전송하는 영역을 정의하는 태그.
  - 주요 속성:
    - `action`: 데이터를 전송할 URL.
    - `method`: 데이터를 전송하는 방식 (`GET` 또는 `POST`).

### `fieldset`
- 관련 있는 폼 요소들을 그룹화할 때 사용하는 태그.

### `legend`
- `fieldset` 태그로 그룹화한 폼 요소의 제목을 나타내는 태그.

---

## Label 및 Input 태그
### `label`
- 입력 필드에 대한 설명을 제공하는 태그.
  - 주요 속성:
    - `for`: 입력 필드의 `id`를 참조하여 연결.

### `input`
- 사용자로부터 데이터를 입력받기 위한 태그.
  - 주요 속성:
    - `type`: 입력의 종류를 설정 (예: `text`, `password`, `radio`, `checkbox`, `email`, `file`, `submit` 등).
    - `name`: 데이터를 구분하기 위한 이름.
    - `value`: 기본값 설정.
    - `placeholder`: 입력 필드에 표시할 힌트 텍스트.
    - `required`: 필수 입력 항목 설정.
