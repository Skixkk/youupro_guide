# Build Website

> 基于 github.io 构建 个人网站

> 基于 github.io 构建 vue vite Nuxt Nuxtjs vitepress 的个人网站

## Skixkk.github.io

> 以 `Skixkk.github.io` 为例

> Nuxt 作为 主页；vitepress 写一下 文章笔记；笔记

### Nuxt

[Nuxt install](https://nuxt.com/docs/4.x/getting-started/installation)

### Vitepress

[vitepress install](https://vitepress.dev/guide/getting-started)

### 一系列命令

```bash
node -v
npm -v

npm install -g bun

bun create nuxt@latest Skixkk.github.io

bun add -D vitepress@next

bun vitepress init

```

### npm 国内镜像 {id="npm_1"}

查看当前的镜像源

```Bash
npm config get registry
```

设置为淘宝镜像

```Bash
 npm config set registry https://registry.npmmirror.com
```
设置为 npm 官方原始镜像

```Bash
npm config set registry https://registry.npmjs.org/
```

#### 管理 npm 镜像

nrm 是一个 npm 源管理器，允许你快速地在 npm 源间切换。
```Bash
npm install -g nrm
```
查看可选的源
```bash
nrm ls    
```
如果要切换到taobao源，执行命令
```Bash
nrm use taobao
```
测试速度
```Bash
nrm test     
```

> [参考：国内npm源镜像（npm加速下载） 指定npm镜像](https://blog.csdn.net/qq_43940789/article/details/131449710)
