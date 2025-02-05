# Dev

## Git submodule 적용하기

`git clone { repository }`

`git submodule init`

`git submodule update`

그리고 각 서브모듈에 대해서 .env 파일을 만들어서 환경변수를 설정해줌

### 추가적으로 submodule을 옵션에 맞게 업데이트 하고 싶으면

```
git submodule update --remote --merge

# .gitmodules 파일에 정의되어 있는 브랜치의 최신 버전으로 업데이트 (혹은 default 브랜치)
git submodule update --remote

# 로컬에서 작업 중인 부분과 원격에 작업된 부분이 다른 경우 머지까지 진행
git submodule update --remote --merge
```
