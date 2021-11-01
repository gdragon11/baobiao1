# rut

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### router.replace() 跳转路由，不会留下历史记录 当返回前一个页面时this.$router.go(-1) 会无效
router.push() 跳转路由，会留下历史记录 当返回前一个页面时this.$router.go(-1) 可以实现
