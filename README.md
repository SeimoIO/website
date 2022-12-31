# Website

release at 2022.07.28

## 如何为网站创建一个新版本

目前 docusaurus 支持手工的方式创建版本，我们必须在稳定的情况下创建对应的版本。

### 多版本管理原因

![image](./static/img/mutlis-versions.svg)

### 创建一个新版本的命令

可以使用的包管理方式，自行决定使用哪种方式

- npm

```bash
npm run docusaurus docs:version 1.1.0
```

- yarn

```bash
yarn run docusaurus docs:version 1.1.0
```

> 查看最新的更新 <https://docusaurus.io/docs/versioning>
