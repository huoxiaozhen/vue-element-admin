一   安装element-ui
二   安装js-cookie
三   安装svg-sprite-loader
login 
```
watch: {
    $route: {
      handler: function(route) {
        console.log(route)
        const query = route.query
        if (query) {
          this.redirect = query.redirect
          this.otherQuery = this.getOtherQuery(query)
        }
      },
      immediate: true
    }
  }
```