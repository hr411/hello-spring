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
@ git status
```

### 커밋생성
```
@ git commit -m '커밋명'
```

### 커밋 업로드
```
@ git push 
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