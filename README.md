# Nuxst.js

- npx create-nuxt-app 이름
- vue를 입력해서 default form(past scaffold) 사용 가능
- pages에 'about.vue'라는 파일을 만들고, 작성하면 /about 갔을 때 알아서 routing. 또한, 폴더명 about을 만들고 안에 index.vue를 만들면 해당 폴더명이 route 대상
- components에서 vue를 만들 때, 이름이 겹칠 수 있으니 조심
- layouts에서 항상 띄워야할 layouts을 간편하게 import 가능
- {{ $route.params.id }} 하면 url의 parameter를 알 수 있음
- \<nuxt-link to="경로">를 이용하면 route를 쉽게 할 수 있음

# dadjokes

## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).
