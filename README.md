# vscode-github-

１．
参考这篇博客，太有用了：　

同步代码

这里说下平时修改代码后提交到云端的使用，和本地代码和云端同步

随便打开一个文件，添加一个注释


可以看到git图标有一个提示，打开git工作区可以看到就是修改的这个文件


然后点击右侧的+号，把他暂存起来。

再在消息框里输入消息，按ctrl+enter提交暂存


再点击push提交，代码就提交到云端了。


打开 码云就可以看到了。。

作者：前小白
链接：https://www.jianshu.com/p/f836da434e18
来源：简书
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。

２．配置同步是用的setting sync

这可以让不同的电脑使用相同的vscode配置

3.VS code返回按键，很有用：ctrl+alt+-


4.Vscode ＋　cmakelist文件：

https://blog.csdn.net/wanzew/article/details/83097457

不过vscode应该是有cmake插件的，也就是cmake tools，这个应该是可以直接用的，
且其使用在整个界面的最后一列都有选择，比如选择build？还是debug?还是run，也包括是运行哪个程序：
 
![image](https://github.com/pyni/vscode-usage/blob/master/Screenshot%20from%202020-06-30%2008-35-18.png)
 
5.VScode+C++ 尤其是两个json文件的配置：
包括了如何用std11运行等
https://blog.csdn.net/weixin_43374723/article/details/84064644#4tasksjson_73
注意launch.json里面，"program": "${workspaceFolder}/build/这里要用生成的exe文件才行"

６.VScode+python　２和３ 的两个版本切换：
找到“设置”里面（可参见最左下角的齿轮）的"python:python path",如果是用的python2,则输入为python2,如果用的python3,则输入python3

７.VScode　用参数进行调试：
https://blog.csdn.net/u012332816/article/details/80801106

8.vode 的临时文件是存放在　.cache/.vscode-cpptools　里面的

# spyder-github-


１．anaconda中使用spyder用法：　

如果要使用conda中的spyder，首先要安装spyder的核：

conda install spyder-kernels

再使用conda自带的spyder,在anaconda3/bin中：
 ./spyder  --new
 
最后，修改Tools --> preferences --> python Interpreter中的python路径即可，重启即可


