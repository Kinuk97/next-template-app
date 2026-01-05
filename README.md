# 기본 탬플릿

1. .editorconfig 추가

2. prettier 설정 추가

```shell
# 설치 후 .prettierrc, .prettierginore 직접 추가
npm install --save-dev --save-exact prettier
npm install -D prettier-plugin-tailwindcss

# 설치 후 eslint.config.mjs 수정
# import prettier from 'eslint-config-prettier/flat'
# defineConfig에 prettier 추가
npm i -D eslint-config-prettier

```
