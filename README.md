- 电脑安装npm环境
- 通过npm安装yarn
```
npm install -g yarn
```

-然后拉取github代码
```
git clone https://github.com/chathub-dev/chathub
```
-检出最新版, 默认分支有bug
```
cd chathub
git init
git checkout v1.36.7
```
修改`D:\Marx\MX_Chrome_Plugn\chathub\src\app\hooks\use-premium.ts`的内容, 进行会员破解
构建:
```
yarn install
yarn build
```
- 最后生成了一个文件夹 位于 `D:\Marx\MX_Chrome_Plugn\chathub\dist\`
在谷歌浏览器中, 管理扩展模块中开启开发者选项, 然后从本地加载插件, 选这个文件夹加载
