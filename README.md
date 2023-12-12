## 📌 First

👉🏻 fork (잊지마!)
👉🏻 clone
👉🏻 브렌치 변경 (ddaeunbb)
👉🏻 gitignore를 위해 초기화 작업

```bash
git rm -r --cached .
git add .
git commit -m “커밋 메시지”
```

<br />

## 📌 Eslint, Prettier 설정

👉🏻 먼저 eslint설정

```bash
npm init @eslint/config
```

- To check syntax, find problems, and enforce code style
- import export
- none (framework)
- no (typescript)
- browser, node 모두 선택
- airbnb설정
- peerDependencies YEs
- javascript
- npm
  <br />

---

```bash
npm i -D eslint-config-prettier eslint-plugin-prettier prettier
```

👉🏻 아래 파일들 해당 레포에서 복붙

- `eslintrc.cjs`
- `.prettierignore`
- `prettierrc`

<br/>

## 📌 gitignore, npmrc설정

👉🏻 아래 파일들 해당 레포에서 복붙

- `gitignore`

👉🏻 npmrc는 노드 버전에 맞게 아래와 같이 설정

```bash
engines=node@14.x (버전사용해야할때)
engines.node>=18.17.1 (이상일때)
18.17.1 (특정버전일때)
```

<br/>

## 📌 폴더구조

- MVC 패턴 적용 시

  - model
  - view (outputView, inputView)
  - controller
  - utils
  - exceptions (CustomError.js 설정)
  - validators
  - constants (error.js 설정)
    <br/>

- 이외 경우
  - constants (error.js 설정)
  - controller
  - domain
  - exceptions (CustomError.js 설정)
  - validators
  - view (outputView, inputView)
  - utils

<br/>

## 📌 docs 파일 설정

👉🏻 아래 파일들 해당 레포에서 복붙

- `convention.md`
- `README.md`
  <br/>

## 📌 파라미터 타입

- 클래스 Definition

```js
/**
 * @classdesc 캐셔
 * 손님의 날짜와 메뉴에 해당하는 할인 금액을 계산한다.
 */
```

- 파라미터 및 리턴 값 타입

```js
/**
 * @param {string} date
 */

/**
 * 총 할인 금액 리턴
 * @return {number}
 */
```
