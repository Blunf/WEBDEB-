README>

----------------------------------------------------------------------------------------------------------
HTML>

처음 시작시 {!+tab}  -> 기본 구조 생성



----------------------------------------------------------------------------------------------------------
GIT>

1. 깃(Git) 설치 확인:
먼저 컴퓨터에 Git이 설치되어 있는지 확인합니다. 터미널에서 다음 명령어를 실행하여 Git의 설치 여부를 확인할 수 있습니다.

git --version


2. 깃 초기 설정:
Git을 설치한 후, 사용자 정보를 설정합니다. 이 정보는 커밋할 때 사용됩니다.

git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"


3. 깃 저장소 생성 및 초기화:
코드가 있는 디렉토리로 이동한 후, Git 저장소를 초기화합니다.

cd path/to/your/code
git init


4. 깃에 파일 추가:
모든 파일을 추가하기 위해 다음 명령어를 사용합니다.

git add .

혹은 특정 파일을 추가할 수 있습니다.

git add filename.py


5. 커밋 생성:
추가한 파일들에 대한 커밋을 생성합니다.

git commit -m "Initial commit"


6. 깃허브에 새로운 저장소 생성:
깃허브 웹사이트에서 새로운 저장소를 생성합니다.


7. 로컬 저장소와 원격 저장소 연결:
원격 저장소 URL을 사용하여 로컬 저장소와 원격 저장소를 연결합니다.

git remote add origin https://github.com/username/repository.git


8. 로컬 변경 사항을 원격 저장소에 푸시:

git push -u origin master
