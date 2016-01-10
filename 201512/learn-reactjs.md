# 学习ReactJS
这是我的第一个ReactJS项目，之前都是使用Angular+Ionic架构。
[ReactJS][1]是我想尝试的一种不同于传统的框架。
[ReactJS][1]配合[Webpack][2]。

## 如何搭建项目框架
**[yeoman][4]**是搭建项目框架的第一步，当然还要安装**[generator-reactjs][3]**作为项目的脚手架。
```shell
npm install -g yo
npm install -g generator-reactjs
npm install -g babel
yo reactjs
npm install --save gulp-sass
```
> generator-reactjs是一个相对轻量级的项目结构。
> 由于generator-reactjs本身支持less，所以我引入gulp-sass模块来支持sass功能。
> [babel][5]是ES6转换成ES5的利器。




[1]:http://facebook.github.io/react/docs/getting-started.html
[2]:http://webpack.github.io/docs/
[3]:https://www.npmjs.com/package/generator-reactjs
[4]:http://yeoman.io/
[5]:https://babeljs.io/