# simplify-html-loader
简化的html-loader, 不检测link.
## 安装
```sh
$ npm install simplify-html-loader --save-dev
```
## 使用
```javascript
module.exports = {

  ...

  module: {
    loaders: [
      {
        test: /\.html$/,
        exclude:/node_modules/,
        loader: 'simplify-html-loader'
      }
    ]
  }
};
```
