#前言
20160326.
早就知道github，很久以前安装了github for Windows，然而不知道为什么我安装的github客户端不能用（时间有点久具体是怎么不能用我也不记得了）
然后机缘巧合，我就装了个gitbash，然后就又过了很久。
终于到了今天，我终于学会了往github上po我自己的文件了。dog脸.jpg
然后我想随着对git的深入应用总结些git的用法出来，只是为了巩固自己的学习。
#绑秘钥
绑秘钥这一步先省略吧
#po文件的流程
第一步：用（其实不用也行）gitbash，通过命令 mkdir  yourfilename，创建要po到github上的文件夹；

然后你就可以在这个文件夹里写各种语言的代码了。

第二步：git add yourfilename  ------------这一步是把你的文件放到暂存区，我其实一点也不清楚git的这个所谓暂存区。

我目前就只是记住了这几个流程，对git本身完全没有理解。

第三步：git commit -m "say sth about the version"----------------在命令行里 -x这种的都属于命令参数，对于 gitcommit这个命令来说，-m参数必不可少，因为它是交代文件的版本信息的（究竟是不是版本信息我明天再查查看）。

第四步：git remote add <name> git@github.com:youracountname/youreposnanme.git

第五步：git push <name> master

详细的内容我明天再更今天先到这里
