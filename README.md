# Frontend Boilerplate

Next.js + Typescript 활용한 React 기반 프론트엔드 기본 설정 Boilerplate.
해당 프로젝트에 설정된 부분은 [여기를](https://www.notion.so/Frontend-Boilerplate-b4f07b67713243f1bb0050cd35970bc9) 확인!!

### Tech stack

- [Next.js](https://nextjs.org/docs/getting-started)
- [Typescript](https://www.typescriptlang.org/docs/)
- [ESLint](https://eslint.org/) + [Prettier](https://prettier.io/) + [airbnb Style Guide](https://github.com/airbnb/javascript)
- [Jest](https://jestjs.io/docs/next/getting-started) + [testing-library](https://testing-library.com/docs/)

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```


### github action 
[push directory to another repo](https://github.com/marketplace/actions/push-directory-to-another-repository)
대상이 './' 이면 안됨 -> `.github/workflows/ci.yml` 까지 모두 가져가므로...