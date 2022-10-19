# Deploy방법
1). gh설치
npm i gh-pages

2). package.json 스크립터 추가
	(1).scripts
    "deploy": "gh-pages -d build",
    "predeploy": "npm run build"
    
	(2)."homepage":"https://gitdgs.github.io/react-movie-app"
3). git 확인
git remote -v 

4). git Repository 생성 및 등록	
git remote add origin https://github.com/gitdgs/react-movie-app

# react-for-beginners
nomadcode
