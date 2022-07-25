# Project references bug in VS Code

Run `pnpm i` to install dependencies.

Run `pnpm tsc -b foo` - this will pass.

However, if you open `foo/index.ts` in VS Code, it will be reporting errors due to failed null checks.
