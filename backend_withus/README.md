launch.json에 넣어서 디버깅 하면 리로드 됩니다.
{
    "type": "java",
    "name": "RemoteReload",
    "request": "launch",
    "mainClass": "org.springframework.boot.devtools.RemoteSpringApplication",
    "args": "http://localhost:8000"
},