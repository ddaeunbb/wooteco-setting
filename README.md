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
