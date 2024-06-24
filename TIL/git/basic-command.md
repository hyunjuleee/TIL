# Git command

> git 기본 명령어 정리

## init
- 현재 위치에 `.git` 폴더를 생성

```bash (터미널 안에서 사용하는 명령어임을 표시)
git init
```

## add
- working directory => staging area

```bash
git add .
. => 현재 위치에 있는 모든 파일
```

## status
- 현재 git 상태 확인

```bash
git status
```

## commit
- 현재 staging area에 올라간 내용을 스냅샷 찍기
    - `-m` 옵션을 통해 커밋 메세지를 바로 입력 가능

```bash
git commit -m "first commit"
```

## remote add

- 원격 저장소의 주소를 저장하는 명령어

```bash
git remote add origin http://~
git remote add {remote_name} {remote_url}
```

## push
-원격 저장소로 브랜치를 업로드하는 명렁어

```bash
git push origin master
git push {remote_name} {branch_name}
```

