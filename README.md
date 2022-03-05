# self-develop-web
self develop web

# install packages
아래 명령어로 패키지를 설치해줍니다.
```
npm i
```

# PR 규칙
1. 한 브렌치로 여러 PR을 보내지 마세요.
2. PR운선순위는 PR 등록 순 입니다. 충돌이 발생하지 않도록 조심해 주세요.
3. 되도록 PR전 `lint`와 `prettier`를 적용해 주세요.

lint: 
```
npm run lint:fix
```

prettier:
```
npm run prettier:write
```