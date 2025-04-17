# electron-study-app

An Electron application with Vue and TypeScript

## Recommended IDE Setup

- [VSCode](https://code.visualstudio.com/) + [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) + [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar)

## Project Setup
node版本20.16.0，
先通过脚手架pnpm create @quick-start/electron my-app --template vue-ts 构建基本项目，在把之前搭建好的vue项目合进去就行了。

注意electron版本不能太高，安装的时候会有问题

项目的配置文件如env,package.json,tsconfig.json,eslintrc.json等,都要在项目的跟目录下，不能放在renderer目录下



### Install

```bash
$ pnpm install
```

### Development

```bash
$ pnpm dev
```

### Build

```bash
# For windows
$ pnpm build:win

# For macOS
$ pnpm build:mac

# For Linux
$ pnpm build:linux
```
