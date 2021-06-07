#httpfuse
***测试功能代码,仅供参考和学习,不具备项目使用***
### 前置
   > sudo apt-get install libfuse-dev fuse-utils build-essential make

## 功能
  - 利用linux中fuse的库文件,实现自己的文件系统
  - hello中实现了文件创建和查看,hello1中实现了文件删除和创建

## 使用
  - 直接cmake生成Makefile文件,再进行make就可以生成可执行文件`fusehello`
  - `./fusehello /tmp/mnt`即可使用,`/tmp/mnt`是fuse挂载文件夹.

## 原理

参考我的博客`http://linkmecry.cn/2021/06/07/Linux%E4%B8%8Bfuse%E7%9A%84%E5%AE%9E%E7%8E%B0%E5%8E%9F%E7%90%86/`的上半部分.
