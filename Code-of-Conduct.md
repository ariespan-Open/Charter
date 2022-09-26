# ariespan-Charter
## Code of Conduct
#### 对维护者的要求
- 是在地球上的人类
- 有人教版英语初中二年级及以上水平
- 较为熟练使用GNU/Linux发行版，熟悉相关命令(P.S.:其他类UNIX也可，如:FreeBSD MacOS.因为有很大相似/相通之处)
- 搭建过网站，熟悉Nginx/Apache的安装与使用，网站程序基本结构等
- 熟悉基本的html语法
#### 对文件管理员的要求
- 是在地球上的人类
- 有脑子
### 操作规范
在对网站进行一些操作时，您需要填写[LOG(维护日志)](https://github.com/ariespan-Open/ariespan-log)
#### 这包括但并不限于
- 对网站源代码的更改
- 站点平台变量更改
- 文件的删除
- 站点服务器内核升级，防火墙策略变更等
- ~~站点文件添加，新建文件夹~~（自2022年9月26日起，此项操作并不需要填写log.但新建一级文件夹仍然需要）
### Git操作规范
- 非必要不要使用rebase
- 禁止Force Push
- 如果网站源代码的commit来自上游或其他地方，chery-pick必须保留原提交信息和作者
- commit必须使用GPG/SSH/Github网页在线编辑器的密钥进行签名(即Commit后带有Verified标签)，以证明提交确为您本人所做