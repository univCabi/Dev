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


# UnivCabi
<p align="center">
  <img width="500" alt="UnivCabi Logo" src="https://github.com/user-attachments/assets/472b39df-2c89-4561-b01a-952cbd1c457e" />
</p>

## 목차
- [📝 프로젝트 소개](#introduction)
- [🛠️ 기술 스택](#tech)
- [🌟 주요 기능](#function)
- [🧑🏻‍💻 프로젝트 멤버](#member)

## <span id="introduction">📝 프로젝트 소개</span>
- **프로젝트 기간** : 2024.09 ~ 2025.04
- **목적**
  - 기존 부경대학교 내 사물함은 각 학과에서 SNS를 통해 선착순으로 대여하고, 이를 수기로 관리하고 있습니다. 
  - 이러한 수기 관리의 불편함을 해소하고자 사물함을 전산화하고, 학생들의 사물함 대여와 반납의 편의성을 위해 사물함 대여 서비스를 개발하였습니다.

- **기대 효과**
  - 학과 : 사물함 대여 현황 및 상태를 손쉽게 관리할 수 있어 효율성이 증대됩니다.
  - 학생 : 현재 대여 가능한 사물함 목록을 한 눈에 볼 수 있으며, 클릭 한 번으로 편리하게 사물함 대여 및 반납이 가능합니다.

## <span id="tech">🛠️ 기술 스택</span>
<table>
  <thead>
    <tr>
      <th>분류</th>
      <th>기술 스택</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>프론트엔드</td>
      <td>
        <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=white"/>
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white"/>
        <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white"/>
        <img src="https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white"/>
      </td>
    </tr>
    <tr>
      <td>백엔드</td>
      <td>
        <img src="https://img.shields.io/badge/django-092E20?style=flat&logo=django&logoColor=white">
        <img src="https://img.shields.io/badge/Django%20REST%20Framework-FF1709?style=flat&logo=django&logoColor=white">
        <img src="https://img.shields.io/badge/spring-6DB33F?style=flat&logo=spring&logoColor=white">
        <img src="https://img.shields.io/badge/python-3776AB?style=flat&logo=python&logoColor=white"> 
        <img src="https://img.shields.io/badge/Java-007396?style=flat&logo=java&logoColor=white">
      </td>
    </tr>
    <tr>
      <td>데이터베이스</td>
      <td>
        <img src="https://img.shields.io/badge/sqlite3-003B57?style=flat&logo=sqlite&logoColor=white">
