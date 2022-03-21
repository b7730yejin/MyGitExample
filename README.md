### Git과 Github

#### 1. git으로 파일 업로드하기

- git init : git 프로젝트 초기 선언
- git master 계정이 문제가 있어서 main으로 바꿔줘야 함 -> git branch -M main
- 원격 저장소를 지정하는 건 git remote add origin "원격지 주소"
- git add -> git commit -m "커밋 메시지" -> git push -u origin main

#### 2. git origin / master / HEAD

- origin : 원격저장소 경로
- master(main) : 가장 기본적인 branch 경로
- HEAD : 현재 작업공간(현재의 branch)

#### 3. Hub의 Repostitory 폴더를 새로 생성하지 않고 현재 폴더에 내려 받기

- git clone "저장소 주소" . (한칸 띄우는게 중요)

#### 4. 새 branch 생성

- git branch : 현재 생성되어 있는 모든 branch 확인
- git branch [name] : name이란 이름을 가진 branch 생성
- git checkout [branch] : 해당 branch로 전환

#### 5. main 외 branch에서 파일 올리고 병합하기

- 1. git checkout main 명령어로 일단 main으로 전환
- 2. git merge [branch] 명령어로 병합 진행
