### ๐ ๋ฒ์ ๊ณผ ์๋ก๋
- ๊ฐํ ์ค์ 
- CRLF๋ฅผ ์๋์ผ๋ก OS์ ๋ง๊ฒ๋ณํ, ์ ์ญํ

```Bash
git config --global core.autocrlf true

```


 
### ๐์ฌ์ฉ์ ์ ๋ณด

- ์ปค๋ฐ์ ์ํ ์ ๋ณด

```Bash
git config --global user.name "name"

git config --global user.email "e@mail.com"
```


### ๐ ์๋ก๋๋ฅผ ์ํ ๊ธฐ๋ณธ์ ์ธ ๋ช๋ น์ด

- ํด๋น ํด๋์ ๋ณ๊ฒฝ์ฌํญ์ ์ถ์ 
``` Bash
git init
```

- ๋ณ๊ฒฝ์ฌํญ ์ถ์ฒํ  ํ์ผ์ ํน์ 
```Bash
// ํน์ 
git add test.ts
// ๋ชจ๋ 
git add .
//stage๋ฅผ ์กฐํํ ์์์, ๋น์์ผ๋ก ๊ฐ์กฐ
git status 
```

- ๋ณ๊ฒฝ์ ์ ๊ธฐ๋ก, ์ปค๋ฐ ๋ฉ์์ง ์์ฑ
  - commit ์ดํ์ ๋ณ๊ฒฝ์ ์ด ์๋ค๋ฉด ๋ค์ add -> commit
```Bash
git commit -m "msg"
```


- ์๊ฒฉ ์ ์ฅ์ [์ ์ฅ์ ์ด๋ฆ]์ ์ฐ๊ฒฐ
```Bash
git remote add [์ ์ฅ์ ์ด๋ฆ] [ํด๋น ์ ์ฅ์์ URL] 
```

- [์ ์ฅ์ ์ด๋ฆ]์ [๋ธ๋์น]์ ๋ณ๊ฒฝ์ฌํญ์ ํธ์ฌ
```Bash
git push [์ ์ฅ์ ์ด๋ฆ] [๋ธ๋์น] 
```
