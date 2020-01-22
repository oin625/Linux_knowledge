**sudo dpkg -i** sogoupinyin_2.1.0.0082_amd64.deb    --安装安装包

lsb_release -a  -- 查看当前Linux系统版本

ping www.baidu.com 验证IP数据报是否到达目的地。并且可以查看IP地址。

nslookup 

.>server      查看默认DNS服务器地址



查看进程(可能会有其他的，这里的笔记仅仅只是我目前有的知识，不全面)

> top   动态的显示进程     top | grrp id
>
> ps   按下ps的那个时刻的进程状态。 ps -ef | grep id 或者 ps aus | grep id都可
>
> 其中 ps -ef 和 ps aux的区别:
>
> 用aux 的时候，COMMADN列如果过长，aux会截断显示，而-ef不会。

结束进程

>kill  kill -9  killal
>
>①kill和kill-9的区别
>
>kill 有局限性，kill-9相当于强制杀死。
>
>②kill和killall的区别
>
>kill + id
>
>killall + name

查看文件所在位置

> whcih codeblocks