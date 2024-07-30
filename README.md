# firebase-연동법
-----------

flutter 설치 완료 시 아래 링크 들어감. (firebase 사이트)
https://firebase.google.com/docs/flutter/setup?hl=ko&platform=ios

![image](https://github.com/user-attachments/assets/0e09eb73-b6a3-4d6b-9ab3-3dc18364e0ae)

이후 안에서  " Google 계정을 사용하여 Firebase에 로그인합니다." 글자 링크 클릭.
(한 사람 아이디로 로그인 해야겠죠?) 
로그인 완료 후 firebase CLI 설치 링크로 들어감
https://firebase.google.com/docs/cli?hl=ko#setup_update_cli


이 안에서 독립형 바이너리와 npm이 있는데, 구글링에는 npm 방식이 더 잘 나와있으므로, npm 방식으로 하는 것을 추천하겠습니다.
독립형 바이너리로 해도 연동엔 상관 없어요! 

![image](https://github.com/user-attachments/assets/3081ace1-6682-496c-b754-bb1493a0bf6b)
위 화면에서 node.js 다운하는 링크가 있는데, 다운하세요. 

후에 android studio 터미널에다가 npm install -g firebase-tools 입력 후 완료되면
firebase login 누르면 아마 링크 탭으로 이동될 것임. 내 구글 아이디는 카톡으로 알려달라고 하면 알려드리겠음. 

이후 
![image](https://github.com/user-attachments/assets/d67451db-9c12-4e02-81df-8507c2fbb254)
이렇게 치면 되는데, pro_max_ject 디렉터리에서 진행되어야 함. 

그 다음 Which Android ... ~~ 'com.example.app'? 이 나오면 주소 입력 (이것도 카톡으로 알려드리겠음)

그럼 아마 될 것임. 
