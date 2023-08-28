# preonboarding
원티드 프리온보딩 사전과제를 위한 레포지토리
피그마 링크: https://www.figma.com/file/rEbLeBRtg5gTpYXWv7SNvI/%E1%84%80%E1%85%AA%E1%84%8C%E1%85%A6?type=design&node-id=0%3A1&mode=design&t=YT48cm3Zf4DvAWMk-1

# 브랜치 이름
main - dev/영어이름 - feat/기능이름

    ex) dev/jihyyeon, feat/banner
    //터미널 새로운 브랜치 생성하고 이동하는 명령어
    git checkout -b feat/기능이름 dev/영어이름

- main 브랜치 기반으로 위의 브랜치들을 만들어서 사용합니다.
- feat/기능이름의 경우 해당 기능이 끝나면 브랜치는 최종 PR과 함께 사라집니다.
- dev/영어이름의 경우 작업물의 최종 버전입니다.
- main은 별도로 올리지 않습니다!

# 커밋 컨벤션
`키워드` - 커밋 메세지

    ex) ADD - 이벤트 추가

- 키워드: ADD, UPDATE, MODIFY, RENAME, FIX, BUG

# 폴더 및 파일 이름 컨벤션
index.html - 하나의 페이지로 작성

css/
-  reset.css
-  common.css
-  header.css
-  footer.css
-  section-`개별이름`.css
-  media.css
  
js/
- main.js
- `기능이름`.js

image/
- 케밥케이스

# 식별자 네임 컨벤션
- 카멜 케이스로 작성
- 함수: 동사+대상 ex) addNumbers
- 변수: 명사+자료구조 ex) numberArray
