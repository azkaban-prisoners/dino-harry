# 시작하기

1. `yarn` 명령어를 실행

- `Next.js`: `yarn dev` 명령어를 실행
- `Storybook`: `yarn storybook` 명령어를 실행

## VSCode SDK 설정

- VSCode에서 import한 라이브러리마다 발생하는 `Cannot find module...` 에러를 해결
- Yarn Berry 방식으로 다운로드된 라이브러리 코드 탐색 가능

> To support features like go-to-definition a plugin like [ZipFS](https://marketplace.visualstudio.com/items?itemName=arcanis.vscode-zipfs) is needed.
>
> 1. Run the following command, which will generate a new directory called **.yarn/sdks**:
>
> ```bash
> yarn dlx @yarnpkg/sdks vscode
> ```
>
> 2. For safety reason VSCode requires you to explicitly activate the custom TS settings:
>
> 3. Press `ctrl+shift+p` in a TypeScript file
>
> 4. Choose "Select TypeScript Version"
>
> 5. Pick "Use Workspace Version"
