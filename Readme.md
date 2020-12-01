(1) 全局安装：npm install browserify -g 
(2) 局部安装：npm install browserify --save  -dev
(3) 打包处理js: browserify js/src/app.js -o js/dist/bundle.js
 -o //output 输出的意思 //输出的文件名字
(4) 页面引用 <script type="text/javascript" src="./js/src/bundle.js"></script>


打包命令：
 browserify js/src/app.js -o js/dist/bundle.js