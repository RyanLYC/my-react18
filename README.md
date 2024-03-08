## 技术选型

- Mono-repo
- Pnpm workspace
- Rollup

## 代码规范

- ESLint & Prettier & husky & commitlint

  ```js
    pnpm i eslint -D -w
    npx eslint --init
    pnpm i prettier -D -w
    pnpm i eslint-config-prettier eslint-plugin-prettier -D -w
    // 处理 eslint prettier 冲突
    pnpm i husky -D -w
    npx husky init
    // pre-commit 内容文件修改为  pnpm run lint
    pnpm i commitlint @commitlint/cli @commitlint/config-conventional -D -w
  ```

-
