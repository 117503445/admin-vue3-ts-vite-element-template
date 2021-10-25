# admin-element-vue

Vue3 + TypeScript + Vite + Element Plus 的后台管理模版

基于 <https://github.com/lqsong/admin-element-vue/tree/vite.ts>

## 使用文档

- [vite.ts](http://admin-element-vue.liqingsong.cc/vitets/)

## 自定义配置

### **(建议)** 本地或开发模式下，不要直接修改 '.env.development'

复制 '.env.development' 重命名为 ' .env.development.local' , 修改对应的参数.

### **(建议)** 生产模式下，不要直接修改 '.env.production'

复制 '.env.production' 重命名为 ' .env.production.local' , 修改对应的参数.

## 项目设置

### 一、Install dependencies

```bash
yarn
```

### 二、Compiles and hot-reloads for development

```bash
yarn dev
```

### 三、Compiles and minifies for production

```bash
yarn build
```

### 四、本地预览生产构建产物

```bash
yarn serve
```

### 五、精简 svg icon

```bash
yarn svgo
```

### 六、Run your unit tests

```bash
yarn test
```

## Edit

./config/setting.ts siteTitle & footText

./src/layouts/IndexLayout/components/Left.vue Line 6

./public/favicon.ico

./src/assets/images
