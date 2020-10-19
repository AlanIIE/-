# 安装环境
```
python 3.5
PyQt5==5.15.1
pywin32==228
```
# 代码
目的：按时提交英语作业
思路：将要发送的内容保存到剪切板，激活相应的窗口，再使用C-v黏贴到窗口中，A-s发送出去。
发送文字消息时，可以将文字先保存在文件message.txt中，文件内容举例：
```
嗯嗯？
2022的话 这个就比较赞了
那我可以考虑换个笔记本了
出个新版本就换本子？什么情况
怕卡
[群签到]请使用新版QQ进行查看。
早
早上好
大家好
以前哪个win10下载器谁有吗
去i tell you下
```

注意：
1. 仅适用于windows系统
2. QQ、微信发送窗口要打开，不能最小化，但是可以不在最上面一层（即，可以在没有被激活的状态）


