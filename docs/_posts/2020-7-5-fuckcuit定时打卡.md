# fuckcuit定时打卡

我看某群友想搞一个，就顺便水一篇好了

签到的py jo本嫖的是longlone的，我就不放出来了，建议直接去找他要。（我寻思不能断了他五块钱的财路

反正现在也没验证码了，当时我处心积虑在里面插一个ocr也没啥用了。

那么关键问题是怎么定时运行

我的脚本是挂在一个Windows服务器里（和coolq机器人放在一起，懒得docker了。）Windows下定时启动py脚本的教程：https://blog.csdn.net/wwy11/article/details/51100432

Linux也有相应功能，crontab，貌似很多发行版都有自带的，会定时自动运行bash，写一个简单的shell来定时运行就行了。这里也放一个教程：https://blog.csdn.net/sunboy_2050/article/details/6817019

把这些挂载在服务器上， 就可以很简单的实现自动跑jo本的功能。