# ESlint + Prettier

1. npm install
```bash
$ npm install eslint  -D
$ npm install prettier -D --save-exact
$ npm install eslint-config-prettier eslint-plugin-prettier -D
```

2. .eslintrc 파일 생성
3. .prettierrc 파일 생성
4. VSCode 확장에서 ESLint, Prettier install
5. 파일->기본설정->설정->
![설정열기(JSON)](./설정열기(JSON).png)
설정열기(JSON)->settings.json 파일에 아래 코드 추가
```json
{
  // 저장할때 마다 고치기 설정
  "eslint.enable": true,
    "editor.codeActionsOnSave":{
        "source.fixAll.eslint": true
    }
}
```