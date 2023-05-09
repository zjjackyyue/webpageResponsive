# webpageResponsive

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar)

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

## demo界面

![image-20230509174458968](E:\Project\Vue\vue3-demo-with-static-and-simple-pages\webpageResponsive\image-20230509174458968.png)

## 目录结构

webpageResponsive目录结构：
│   .gitignore
│   index.html 
│   package-lock.json
│   package.json
│   README.md
│   vite.config.js
│   
│       extensions.json
│       
└───src
    │   App.vue
    │   main.js
    │   
    ├───assets
    │       education1.jpg // 用于index.vue中的轮播图
    │       education2.jpg // 用于index.vue中的轮播图
    │       education3.jpg // 用于index.vue中的轮播图
    │       news.png // 用在了card的左上角图图标
    │       
    └───components
            card.vue
            Index.vue // 这是首页，引入整合了card.vue
            
