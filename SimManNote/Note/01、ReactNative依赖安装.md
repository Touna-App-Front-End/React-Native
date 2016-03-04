# 01、ReactNative依赖安装

1、 安装NodeJs

```
wget https://nodejs.org/dist/v4.3.2/node-v4.3.2.pkg
```

2、安装 cnpm 

```
npm install -g cnpm --registry=https://registry.npm.taobao.org
```

3、安装 `watchman`, `flow`

```
brew install watchman
brew install flow
```
4、安装 react-native-cli

```
cnpm install -g react-native-cli
```

5、安装 nvm

```
git clone https://github.com/cnpm/nvm.git ~/.nvm && cd ~/.nvm && git checkout `git describe --abbrev=0 --tags`

. ~/.nvm/nvm.sh
```

6、创建项目

```
react-native init hello
```

