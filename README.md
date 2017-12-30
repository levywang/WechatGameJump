# How to use?
## 安装抓包工具

Windows推荐安装fiddler，Macos推荐安装Charles

## 如何抓包

[fiddler参考文章](http://blog.csdn.net/lhorse003/article/details/72473212)

[charles参考文章](https://www.jianshu.com/p/fdd7c681929c)

## 抓包

安装完抓包工具配置好后，进跳一跳游戏，跳几步输掉游戏，去抓包工具中找包含有wxagame文字的包，找到其中的session_id后面的代码，输入到python源码中替换即可，然后更改源码中的times和score，运行python脚本，重新进游戏即可看到分数的变化。
