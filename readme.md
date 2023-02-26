## 개요

https://www.inflearn.com/course/%EC%8A%A4%ED%94%84%EB%A7%81-%EC%9E%85%EB%AC%B8-%EC%8A%A4%ED%94%84%EB%A7%81%EB%B6%80%ED%8A%B8

을 배우는 저장소입니다.

## Git 명령어

### 저장소 코드추가

```bash
$ git add .
```

### 현재 상태확인

```bash
$ git status
```

### 커밋생성
```bash
$ git commit -m '커밋명'
```

### 커밋 업로드
```bash
$ git push 
```

### 커밋 히스토리 확인

옵션을 몇 가지 부여할 수 있다.

- --oneline: 커밋을 한라인으로 본다.
- --name-only: 커밋에 수정된 파일명을 같이 본다.
- --all: 모든 브랜치의 히스토리를 본다.
- --graph: 그래프 형식으로 본다.

```bash
$ git log
$ git log --oneline --name-only --all --graph
```


## IntelliJ 단축어

### 참고
[cheat sheet](https://www.jetbrains.com/help/idea/mastering-keyboard-shortcuts.html)

### 코드포맷팅
```
ctrl + option + L
```

### 최근 본 내용으로 돌아가기
```
command + e
```

### Context Actions
```
option + enter
```

### Generate
```
command + n
```

### 이전실행 다시실행
```
control +  R
```

## DB 설치

- https://www.h2database.com (1.4.200 버전 설치)
- 다운로드 및 설치
- h2 데이터베이스 버전은 스프링 부트 버전에 맞춘다. 
- 권한 주기: chmod 755 h2.sh (윈도우 사용자는 x) 
- 실행: ./h2.sh (윈도우 사용자는 h2.bat) 
- 데이터베이스 파일 생성 방법
  1. jdbc:h2:~/test (최초 한번)
  2. ~/test.mv.db 파일 생성 확인
  3. 이후부터는 jdbc:h2:tcp://localhost/~/test 이렇게 접속


