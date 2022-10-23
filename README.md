# Vue.js 시작하기

[Vue.js 시작하기 인프런 강의](https://www.inflearn.com/course/Age-of-Vuejs) 리포지토리입니다.

![인프런 Vue.js 시작하기 강의 썸네일](https://cdn.inflearn.com/public/courses/324088/course_cover/ac203578-d458-44f4-b273-81cb719a89b0/lv1.png)

## License & Copyright

**Copyright © 2021 Captain Pangyo**

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivs 4.0 Unported License</a>.

## Extension.
- Vetur
- Vue Theme
- Material Icon Theme
- Live Server
- ESLint
- Prettier
- Auto Close Tag

## CDN 코드
``` javascript 
// vue js
<script src="https://cdn.jsdelivr.net/npm/vue@2/dist/vue.js"></script>
// vue router (vue기반으로 작성 되었기에 CDN순서 주의)
<script src="https://unpkg.com/vue-router@3.5.3/dist/vue-router.js"></script>
// axios
<script src="https://unpkg.com/axios/dist/axios.min.js"></script>
```

### CLI
``` sh
# install (권한 문제 있는경우, Node 12.0.0 이상 버전 요구)
(sudo) npm install -g @vue/cli
# or
(sudo) yarn global add @vue/cli

# version check
vue --version

# upgrade
npm update -g @vue/cli
# or
yarn global upgrade --latest @vue/cli
```

### Node Version Update (Not Support Window)
``` sh
1. 버전확인
    node -v
2. NPM 캐시 제거
    npm cache clean -f
3. N 모듈 설치 (노트 버전 관리)
    npm install -g n
4. N 모듈 사용하여 설치 (권한 필요)
    n stable : 안정 버전
    n latest : 최신 버전
    n lts : lts 버전
    n x.x.x : 특정 x.x.x 버전
5. 업데이트 확인
    node -v
```

###  Node Version Update (Window)
``` sh
1. Scoop 설치 (PowerShell terminal)
    > Set-ExecutionPolicy RemoteSigned -Scope CurrentUser # Optional: Needed to run a remote script the first time
    > irm get.scoop.sh | iex
2. node.js 설치 (주의. 버전 관리가 되지 않고 기존 버전 업데이트)
    scoop install nodejs
3. 버전 확인
    node -v
```
## 테스트 서비스
- json 데이터 샘플제공 해주는 사이트 
    + https://jsonplaceholder.typicode.com