# git_hook

Github 과 연계하여 사용하기위해 hook 설정 파일을 제공합니다.

## Usage 

1. 터미널을 엽니다. 
2. 현재 작업중인 프로젝트 상위 디렉토리로 이동합니다.
2. 아래의 코드를 복사 붙여넣기 합니다.

```
git init 
```

```
curl https://github.com/kidsnote/git_hook/raw/master/prepare-commit-msg > .git/hooks/prepare-commit-msg && chmod u+x .git/hooks/prepare-commit-msg
```

