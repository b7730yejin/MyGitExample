### Git과 Github

#### git 저장소 연습장

- git init : git 프로젝트 초기 선언
- git master 계정이 문제가 있어서 main으로 바꿔줘야 함 -> git branch -M main
- 원격 저장소를 지정하는 건 git remote add origin "원격지 주소"
- git add -> git commit -m "커밋 메시지" -> git push -u origin main

#### git origin / master / HEAD

- origin : 원격저장소 경로
- master : 가장 기본적인 branch 경로
- HEAD : 현재 작업공간(현재의 branch)

#### Hub의 Repostitory 폴더를 새로 생성하지 않고 현재 폴더에 내려 받기

- git clone "저장소 주소" . (한칸 띄우는게 중요)
