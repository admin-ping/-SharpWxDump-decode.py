> **⚠️ 本仓库已归档（只读）**，项目已迁移至新仓库：
> **https://github.com/admin-ping/wechat-db-decrypt**
>
> 新仓库已重写为**微信 4.0 支持**的纯 Python 实现（进程内存取密钥 + SQLCipher 4 解密），
> 替代已下架的 SharpWxDump；旧版微信 3.x 的脚本保留在 git 历史中。
> 本仓库仅作存档，不再更新，请前往新仓库获取最新版本。

# -SharpWxDump-decode.py
基于SharpWxDump的解密脚本

基于SharpWxDump项目写了一个一键式调用及解密数据库的python脚本，写的勉强能用，此处提供一个基础的代码，希望大佬们能优化一下

内置已编译的SharpWxDump.exe，最高支持到3.9.6.33版本(额外支持了3.9.7.25、3.9.9.43版本)

使用方法：wx_decode.py -d "C:\Documents\WeChat Files\wxid_xxxxxxxxxx\Msg\Multi"

使用后会自动获取WxKey并将数据库文件复制到当前目录下进行解密


参考地址
SharpWxDump项目地址：https://github.com/AdminTest0/SharpWxDump

数据库解密脚本：https://mp.weixin.qq.com/s/4DbXOS5jDjJzM2PN0Mp2JA
