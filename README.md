# lcn-vue-web


## npm 的一些配置，不涉及项目的运行

${你安装 node 的目录}/node_modules/npm/npmrc 这个文件
```sh
# prefix=${APPDATA}\npm 原本的配置， 这个指定的是 npm 全局安装的目录，默认为 C:\Users\电脑的用户名\AppData\Roaming\npm
prefix=E:\Node\npm

# npm 全局缓存，默认为 C:\Users\电脑的用户名\AppData\Roaming\npm-cache
cache=E:\Node\npm-cache

# 配置 npm 下载时的源路径，
registry=https://registry.npm.taobao.org
```

## 如果修改了全局的配置, 那么需要把这个位置配置到环境变量中去，才能在使用到安装的全局包，既把上面的 prefix 的 value 值添加到环境变量中


## 查看已有的配置
```sh
npm config ls
```




## Reference

https://github.com/byteblogs168/hello-blog

https://github.com/REmango/vue-blog

https://github.com/moxi624/mogu_blog_v2