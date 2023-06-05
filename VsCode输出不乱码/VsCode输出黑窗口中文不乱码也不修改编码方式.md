创建txt文件命名:autorun.txt输入:
```
chcp 65001
cls
```
保存改后缀.bat
win+R: regedit
找到：HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Command Processor
![[Pasted image 20230605195139.png]]
新建字符串值，命名：autorun，数值数据写:autorun.bat文件的地址
![[Pasted image 20230605195252.png]]
