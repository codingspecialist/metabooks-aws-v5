# AWS 초급 강의 V5 엘라스틱 빈스톡 CI/CD 배포
- EC2 2개
- ALB
- NLB
- IAM
- GithubAction
- RDS
- 엘라스틱IP

# 변경사항
- setup-java@v4로 변경 
- distribution 필수임 (벤더사)
- gradle 캐시 설정함
- run밑에 shell 제거, 디폴트라서 안적어도 됨
- runs-on : ubuntu-latest 우분투 최신버전 변경
- einaregilsson/beanstalk-deploy@v22 노드 버전 업데이트

# 교재 부분
- 첫번째 도전 하지 말기!!
- 두번째 도전 하지 말기!!
- 처음부터 IAM만들고, 도전 성공 시키기

# 시도
1 실패
2 실패 (방언 설정 문제)
3 성공

# 엘라스틱빈스톡 프로그래밍 엑세스 방식 키 만드는 법 변경됨
- AWS 외부에서 실행되는 애플리케이션 선택해야함