# react-root

- [react 英文官网](https://react.dev/)
- [react 中文官网](https://zh-hans.react.dev/)
- [github | react](https://github.com/facebook/react)

本项目是基于 **`react`** 框架集成各种前端组件示例。

## 目录结构

- [React项目结构介绍.md](docs/React项目结构介绍.md)

## 基础环境

- 确保你安装了最新版本的 [Node.js](https://nodejs.org/)

验证环境：

```
node -v
npm -v
```

本地环境验证示例：

```shell
# 本地采用的版本示例
node -v
v22.11.0
npm -v
10.9.0
```

切换Nodejs环境：

```shell
# 环境切换
nvm use 22.11.0       # 使用此版本，对应vue3
nvm use 18.16.0       # 使用此版本，对应vue2

# 查看环境
node -v
npm -v
```

## 快速开始

进入某个项目模块，安装依赖包:

```shell
# 进入某个项目
cd <your-project-name>
# 安装依赖包
npm install
```

本地运行：

```shell
npm run dev
```

当你准备将应用发布到生产环境时，请运行：

```shell
# 生成生产环境代码
npm run build
```

## IDE 支持 (推荐 VS Code)

- 强烈推荐 [Visual Studio Code](https://code.visualstudio.com/) (VS Code)，因为它对 TypeScript 有着很好的内置支持。

## 快速搭建项目示例

- 参考官网-[快手上手](https://react.dev/learn/creating-a-react-app)

### 创建一个 React 应用

#### 基础环境: 安装 Node.js 和 npm

同样，确保你的系统上已经安装了 Node.js 和 npm。可以通过以下命令检查：

```bash
node -v
npm -v
```

如果没有安装，请前往 [Node.js 官网 ](https://nodejs.org/)下载并安装最新版本。

#### 方式 1 使用 Vite 搭建 React 项目（更轻量、更快速）

创建React项目：

```shell
npm create vite@latest my-react-app-vite -- --template react
# 或
yarn create vite my-react-app --template react
```

进入项目目录并安装依赖：

```shell
cd my-react-app
npm install  # 或 yarn install
npm run dev  # 或 yarn dev
```

访问： http://localhost:5173/ 查看运行结果。

#### 方式 2: 使用 Create React App 搭建 React 项目 （官方推荐，适合新手）

创建React项目：

```shell
npx create-react-app my-react-app  # 使用 npm
# 或
yarn create react-app my-react-app  # 使用 Yarn
```

进入项目目录并启动：

```shell
cd my-react-app
npm start   # 或 yarn start
```

访问： http://localhost:3000 查看运行结果。


