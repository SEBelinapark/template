# ubuntu 20.04 에서 react.js 시작하기

---

### 1. curl install

    1. ctrl + alt + t :
        Terminal 을 켜줍니다
    2. sudo apt update && sudo apt upgrade:
        먼저, 업데이트랑 업그레이드를 해줍니다
    3. sudo apt install curl:
        curl 설치합니다
    4. curl --version:
        설치가 잘 되었는지 확인합니다

### 2. Node.js install

    1. curl -sL https://deb.nodesource.com/setup_14.x | sudo bash - :
        Node.js 설치를 위해 불러옵니다
    2. sudo apt install nodejs -y :
        Node.js 설치합니다
    3. node -v :
        설치가 잘 되었는지 확인합니다

### 3. npm install

    1. sudo apt install npm :
        npm 설치합니다
    2. npm -v :
        설치가 잘 되었는지 확인합니다
    3. sudo apt-get install build-essential :
        npm install 사용하기 위해 입력합니다

### 4. yarn install

    1. npm install -g yarn :
        yarn 설치합니다
    2. yarn --version :
        설치가 잘 되었는지 확인합니다

### 5. create react-app

    1. 폴더를 생성 또는 지정하여 경로를 설정합니다
    2. (1.)에서 선택한 폴더 우클릭 > Open in Terminal 클릭하여 새 터미널을 엽니다
    3. yarn create react-app 폴더명 :
        react-app 설치합니다
    4. cd (3. 폴더명) :
        react-app 이 설치완료되면 해당 폴더로 진입합니다
    5. code . :
        VScode 이용시, 코드를 열때 사용합니다
    6. yarn start :
        설치완료된 react-app을 실행합니다
