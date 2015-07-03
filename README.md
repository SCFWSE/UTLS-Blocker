# UTLS-Blocker
**请一定阅读完全文后再继续操作**
下载地址
---
普通：[UTLS Blocker.mobileconfig](https://raw.githubusercontent.com/SCFWSE/UTLS-Blocker/master/UTLS%20Blocker.mobileconfig)<br/>
高级：[UTLS Blocker-P.mobileconfig](https://raw.githubusercontent.com/SCFWSE/UTLS-Blocker/master/UTLS%20Blocker-P.mobileconfig)<br/>
撤销：[UTLS Remover.mobileconfig](https://raw.githubusercontent.com/SCFWSE/UTLS-Blocker/master/UTLS%20Remover.mobileconfig)<br/>
直接点击连接即可下载，**务必使用iOS自带的Safari浏览器**<br/>
如果你不明白这三者之间的区别，请下载普通<br/>
简介
--
UTLS-Blocker是一个描述文件，用来打开iOS系统中“阻止不信任的TLS连接”功能，这个功能打开后将阻止访问**任何使用非[Apple受信任证书](https://support.apple.com/zh-cn/HT5012)签名的网站（比如12306）**<br/>
同时，这可以避免MITM中间人攻击，并有效地避免由GFW DNS污染所造成iOS系统经常询问是否信任证书（直接拒绝并提示）。
使用教程
---
对于一般用户，下载“普通”即可<br/>
如果你对安全要求比较高，建议下载“高级”，使用这个版本将**禁止删除本描述文件**<br/>
在安装“高级”后，如需要删除，请下载“撤销”，这将恢复删除选项以及关闭功能，如不立刻删除，将在1天后重启时自动删除<br/>
作用效果
--
若要让本描述文件生效，请**一定注意使用Safari浏览器**。因为本描述文件**只作用于Safari和iOS系统**（大部分的第三方浏览器完全不能预防中间人攻击，**第三方浏览器一般会默认信任任何证书**），在安装描述文件后访问使用非Apple信任证书签名的网站，将自动阻止继续访问而不提供任何选项。<br/>
如果您一定需要使用这些网站，建议使用Chrome浏览器（可在App Store中下载）
建议
--
在安装本描述文件之前，建议恢复出厂设置，在iOS系统上，**一旦信任过一次其它证书，系统将永远默认信任**
