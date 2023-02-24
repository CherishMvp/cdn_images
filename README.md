##  用户名/仓库名@版本号/文件名
https://cdn.jsdelivr.net/gh/user/repo@version/file
// load jQuery v3.2.1
https://cdn.jsdelivr.net/gh/jquery/jquery@3.2.1/dist/jquery.min.js


## 使用一个范围内的版本
https://cdn.jsdelivr.net/gh/jquery/jquery@3.2/dist/jquery.min.js
https://cdn.jsdelivr.net/gh/jquery/jquery@3/dist/jquery.min.js


## 忽略版本号则默认使用最新版
### you should NOT use this in production
https://cdn.jsdelivr.net/gh/jquery/jquery/dist/jquery.min.js


## 在任意JS/CSS文件后添加 .min 能得到一个缩小版
## 如果它本身不存在，我们将会为你生成
https://cdn.jsdelivr.net/gh/jquery/jquery@3.2.1/src/core.min.js


## 在末尾加 / 则得到目录列表
https://cdn.jsdelivr.net/gh/jquery/jquery/
