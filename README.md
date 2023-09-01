## CI/CD 환경 구축 테스트

### CI
1. local 환경과 dev환경 분리
2. github actions를 이용하여 프로젝트를 빌드 
3. 빌드된 프로젝트를 실행시킬 수 있는 Docker 이미지 파일 생성
4. Dockerhub에 이미지 등록

### CD
1. SSH로 AWS에 접속
2. AWS에서 Dockerhub에 있는 파일을 내려받음
3. 내려받은 Docker이미지 파일을 실행
