## Web server 网络服务器
网络环境下为客户提供某种服务的专用计算机。

Web / WWW:  World Wide Web （环球信息网） 中文名:万维网
www 服务器 :几乎所有网络主机 都会安装.很多软件都是用 www 作为显示接口的 非常重要.
一般用 Apache. 






Mail Server 邮件系统
企业可以组建自己的Internet邮件服务器.(需要固定 IP / 域名 / 服务器)

私人公司: 邮件有商业机密 或者 隐私 .这个就不放心用免费的邮箱了
需要自己搭建服务器.




smtp
SMTP（Simple Mail Transfer Protocol）即简单邮件传输协议,它是一组用于由源地址到目的地址传送邮件的规则，由它来控制信件的中转方式。SMTP协议属于TCP/IP协议族，它帮助每台计算机在发送或中转信件时找到下一个目的地。通过SMTP协议所指定的服务器,就可以把E－mail寄到收信人的服务器上了，整个过程只要几分钟。SMTP服务器则是遵循SMTP协议的发送邮件服务器，用来发送或中转发出的电子邮件。



pop3
POP3(Post Office Protocol 3)即邮局协议的第3个版本,它是规定个人计算机如何连接到互联网上的邮件服务器进行收发邮件的协议。它是因特网电子邮件的第一个离线协议标准,POP3协议允许用户从服务器上把邮件存储到本地主机（即自己的计算机）上,同时根据客户端的操作删除或保存在邮件服务器上的邮件,而POP3服务器则是遵循POP3协议的接收邮件服务器,用来接收电子邮件的。POP3协议是TCP/IP协议族中的一员，,由RFC 1939 定义。本协议主要用于支持使用客户端远程管理在服务器上的电子邮件



imap
Internet Mail Access Protocol（交互式邮件存取协议）IMAP是斯坦福大学在1986年开发的研发的一种邮件获取协议。它的主要作用是邮件客户端（例如MS Outlook Express)可以通过这种协议从邮件服务器上获取邮件的信息，下载邮件等。当前的权威定义是RFC3501。IMAP协议运行在TCP/IP协议之上，使用的端口是143。它与POP3协议的主要区别是用户可以不用把所有的邮件全部下载，可以通过客户端直接对服务器上的邮件进行操作。