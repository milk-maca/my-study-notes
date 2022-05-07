## 버전과 업로드

### 개행 설정

- CRLF를 자동으로 OS에 맞게변환, 전역화

```Bash
git config --global core.autocrlf true

```


 
### 사용자 정보

- 커밋을 위한 정보

```Bash
git config --global user.name "name"

git config --global user.email "e@mail.com"
```


### 업로드를 위한 기본적인 명령어

- 해당 폴더의 변경사항을 추적
``` Bash
git init
```

- 변경사항 추척할 파일을 특정
```Bash
// 특정
git add test.ts
// 모든
git add .
//stage를 조회할수있음, 녹색으로 강조
git status 
```

- 변경점을 기록, 커밋 메시지 작성
  - commit 이후의 변경점이 있다면 다시 add -> commit
```Bash
git commit -m "msg"
```


- 원격 저장소 [저장소 이름]에 연결
```Bash
git remote add [저장소 이름] [해당 저장소의 URL] 
```

- [저장소 이름]의 [브랜치]에 변경사항을 푸쉬
```Bash
git push [저장소 이름] [브랜치] 
```
