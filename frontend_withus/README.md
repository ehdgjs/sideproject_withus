안녕 지훈아 동헌이야

도커에서 실행을 하고 싶다고??? 걱정마 내가 해결했어 ㅎㅎ

먼저 powershell 이나 Ubuntu에서 "/withUs/frontend_withUs" 폴더로 이동해줘

그리고 "docker build -f Dockerfile.dev -t frontend_withus ." 을 입력해줘

그리고 "docker run -dp 3000:3000 -v $(pwd):/usr/src/app frontend_withus"

입력한 다음 docker desktop에서 컨테이너를 클릭하면 로그가 출력될꺼야 ㅎ

localhost:3000으로 이동하면 화면 출력!!!
