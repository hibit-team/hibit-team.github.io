# 히빗팀 기술 블로그

## Setting 과정

- 해당 repository(hibit-team/hibit-team.github.io)를 fork 한다.
- fork한 폴더에서 VScode를 실행한 다음, 터미널에 아래와 같은 명령어를 입력한다.
(사전에 npm, node가 설치되어 있어야 한다)

> node --version: v14.15.0
<br>npm --version: 6.14.8

- npm, node가 설치되어 있으면 아래와 같은 명령어를 입력하여 로컬 서버를 띄운다.

```shell
npm install
npm start
```

- `npm start` 명령어가 제대로 동작되면, 로컬 url 주소가 나오게 된다.
- 로컬 주소에서 post를 작성하면 된다.

```shell
npm run post
```

- 작성한 post를 복붙해서 관리자(devFancy)에게 넘겨준다.
- 자세한 건 [Gatsby 기반의 팀 기술 블로그 생성](https://hibit-team.github.io/gatsby/tech-blog-setting/)에 확인하면 된다.
