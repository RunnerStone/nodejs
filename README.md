# nodejs
## install express 
npm install -g express --registry=https://registry.npm.taobao.org
npm install -g express-generator --registry=https://registry.npm.taobao.org 

## generate a project withyou
express -e withyou

## 自动重启 express
npm install --save-dev nodemon

修改 package.json 的 scripts：
"scripts": {
    "start": "node ./bin/www",
    "devstart": "nodemon ./bin/www"
  }
