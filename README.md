# -SharpWxDump-decode.py
基于SharpWxDump的解密脚本
基于SharpWxDump项目写了一个一键式调用及解密数据库的python脚本，写的勉强能用，此处提供一个基础的代码，希望大佬们能优化一下

内置已编译的SharpWxDump为2023/03/26版，最高支持到3.9.2.23版本

使用方法：wx_decode.py -d "C:\Documents\WeChat Files\wxid_xxxxxxxxxx\Msg\Multi"

使用后会自动获取WxKey并将数据库文件复制到当前目录下进行解密


参考地址
SharpWxDump项目地址：https://github.com/AdminTest0/SharpWxDump

数据库解密脚本：https://mp.weixin.qq.com/s/4DbXOS5jDjJzM2PN0Mp2JA
