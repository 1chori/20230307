# 20230307

<!-- md 문서 작성 -->
<!-- # 제목 작성(h1~h5) -->

## 20230307

### 20230307

#### 20230307

##### 20230307

<!-- 리스트 형태 작성 -->

# git 프로젝트

- git이 뭐냐

1. 형상 관리 도구 중 하나
   형상관리 도구 : 버전 관리 시스템
   작업하면서 작업의 리스트를 관리 할 수 있다.

- git의 장점

  - 협업하는 단계에서 소스 코드를 파일로 주고 받을 필요가 없이 같은 파일을 팀원과 병렬로 작업 가능
  - 눈으로 보고 찾는 것보다 효율이 좋고 작업이 편하다
  - 코드의 다른 부분을 바로 찾을 수 있다

- git bash에 들어온 후 git 사용자 설정(ctrl + ~ : VSCode 내 tml 활성화)

  - git config --global user.name "본인 깃허브 닉네임"
  - git config --global user.email "본인 깃허브 이메일"

- 설정이 제대로 되었는지 확인

  - git config --global --list

- cd.. : 경로 지정

  - cd.. 입력할 때마다 이전 폴더로 이동
  - ls -a : 경로의 파일을 모두 확인할 수 있다
  - cd 폴도명 : 해당 폴더로 이동
  - cd 앞부분 폴더명 쓰고 기억이 안나면 tab 버튼 눌러서 비슷한 폴더명 확인 가능

- git 저장소 초기화 저장소를 생성하는 명령
- 해당 프로젝트의 경로에서
- git init

- 저장소와 파일의 내용이 다를 때 컬러로 표현 해준다

- git 저장소 파일 스테이징
- 업로드 전 준비 업로드할 파일들

- gid add 해당 파일 이름
- gid add . : 모든 파일 스테이징

- 커밋 메시지 작성
- git commit -m "메시지 내용"
- 파일 올릴 준비 끝
- git remote add origin "연결할 원격 저장소 주소"

- 원격 저장소에 업로드
- git push
