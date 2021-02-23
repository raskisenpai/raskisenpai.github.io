# 加快Kaskobi官网以及Launchpad Utility访问速度

简单来说就是利用Hosts

ps,采用Hosts修改比较吃地区，有的地区改了会变快而有的则不会反而可能变慢，第一次打开都是慢的，后面就会好一点

------

首先你需要打开hosts文件，路径如下

```
%SYSTEMROOT%\System32\drivers\etc\hosts
```

打开“运行”或者快捷键Win+R

![pic1](/easylinksite/images/runpic.jpg)

输入路径回车，选择记事本 或者 其他如果你有的各种文本编辑器

在hosts文件最后一行输入下方**两块共5个IP**  

------

Kaskobi Official Website

```
198.49.23.145 kaskobi.com
198.49.23.144 kaskobi.com
```

mat1jaczyyy Firmware Utility

```
18.140.226.100 fw.mat1jaczyyy.com
```

保存文件即可

若无法保存请戳[这里](https://blog.csdn.net/i_____miss__you/article/details/80652567)