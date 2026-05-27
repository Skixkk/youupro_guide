# Technology Stack Selection

## Vue or React

### Vue

- Vue **vite** typescript scss (CSR)
- Vue **Electron** typescript scss (CSR Electron)
- Vue **Nuxt** typescript scss (SSG SSR)
- **uni-app** vue typescript scss

### React

- react **vite** typescript scss (CSR)
- react **Next** typescript scss Tailwind CSS (SSR)

## 根据业务选择技术栈

> 常用 Vue 技术栈

### website-网站

- CSR
    - Vue **vite** typescript scss (CSR)
        - 创建命令: bash `bun create vite`
        - **来源 [vite.dev](https://vite.dev/guide/) 官网**
- SSG & SSR
    - Vue **Nuxt** typescript scss (SSG SSR)
    - 创建命令: bash `bun create vite` or `bun create nuxt@latest <project-name>`
    - **来源 [nuxt.com](https://nuxt.com/docs/4.x/getting-started/installation) 官网**

### Desktop Software-桌面应用

- Vue **Electron** typescript scss (CSR Electron)
    - 创建命令: bash `npx create-electron-app@latest my-new-app --template=vite-typescript`
    - **来源 [electronforge.io](https://www.electronforge.io/templates/vite-+-typescript) 官网**

### mini-program : 小程序

- uni-app vue typescript scss
    - 创建命令: bash `npx degit dcloudio/uni-preset-vue#vite-ts <project_name>`
    - **来源 [uniapp](https://uniapp.dcloud.net.cn/quickstart-cli.html) 官网**

## Selection-react

### website-react

- CSR
    - react **vite** typescript scss (CSR)
        - 创建命令: bash `bun create vite`
            - **来源 [vite.dev](https://vite.dev/guide/) 官网**
- SSR -react
    - react **Next** typescript scss Tailwind CSS (SSR)
        - 创建命令: bash `bun add next@latest react@latest react-dom@latest`
            - **来源 [nextjs.org](https://nextjs.org/docs/app/getting-started/installation) 官网**

### Desktop Software -react

- react **Electron** typescript scss Tailwind CSS
    - 创建命令: bash `npx create-electron-app@latest my-new-app --template=vite-typescript`
    - **来源 [electronforge.io](https://www.electronforge.io/templates/vite-+-typescript) 官网**

<seealso>吧                                                                                       
    <category ref="wrs">
        <a href="https://youupro.xyz/guide/starter-topic.html">Guide-首页</a>
        <a href="https://youupro.xyz/">返回主页</a>
    </category>
</seealso>