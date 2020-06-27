# Dingbot  :  一个为控制钉钉群机器人而生的项目
##### 由 吴君凯 ( wujunkai20041123@outlook.com ) 
##### 和 吴君明 ( 2706914036@qq.com ) 编写

### 介绍
　　这是一个 python 项目，在 python 2.17.7 的环境下编写而成。同时可在 python 3.x 的环境下运行。  
　　除了 python 的内置库，此项目的运行不依赖其他第三方库。  
　　开发者努力让所有人——无论是否接受过编程教育——都可以快速上手，开发了 `line.py` 模块，可用于命令行。
### 使用方法
#### 模块
　　现在，整个机器人机器人接口仅有一个源文件，即 `dingbot.py` 。它可以对机器人进行最基本的操作。  
　　这是 `dingbot.py` 的树形结构：
> dingbot.py  
>> def GET\_URL()  
>> def configure(file,default={})  
>> def update()  
>> def download(path,turn=False)  

>> class \_info(object)  
>>> def \_\_init\_\_(self,webhook,secret='')  

>> class \_