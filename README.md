# self-develop-web
self develop web

# Deploy
[Go to deploy page](https://self-develop-web-predeploy.web.app/)

# install packages
아래 명령어로 패키지를 설치해줍니다.
```npm i```

# PR 규칙
1. PR제목은 변경 사항에 대한 간단한 요약으로 작성해 주세요.
2. 이슈에 대한 PR은 PR본문에 이슈를 멘션해 주세요. (`#이슈번호` 로 작성)
3. 이전 커밋이 함께 나타나지 않도록 조심해 주세요.
4. 반드시 pull을 하고 작업을 진행해 주세요.
5. 커밋은 명령문으로 간단히 작성해 주세요. (e.g. fix typo)
6. 작업이 길어질것 같으면 draft를 작성해 주세요.
7. 한 브렌치로 여러 PR을 보내지 마세요.
8. PR운선순위는 PR 등록 순 입니다. 충돌이 발생하지 않도록 조심해 주세요.
9. 되도록 PR전 `lint`와 `prettier`를 적용해 주세요. (extension사용 가능)

lint: 
```npm run lint:fix```

prettier:
```npm run prettier:write```
