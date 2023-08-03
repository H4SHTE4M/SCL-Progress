# Security Coding Lab Progress
本仓库用于追踪大家的进度，同时也可以帮助大家学习Git的使用。

# 使用说明

首先在本仓库中创建分支，分支名为你的github id，如```lwzhenglittle```。

在自己分支的```README.md```中更新自己的进度，commit并push到仓库中，每次push都需要开一个PR请求将自己的分支合并到主分支```main```中，主分支每天进行合并请求的处理。

禁止任何成员直接操作主分支，同时在编辑过程中也要注意不要修改他人的进度。

# lwzhenglittle

- NJU OS: Operating System Design and Implementation
  - 7.9 还没开始看

# icfh-13

# thebeastofwar
- 项目名称:webshell管理工具 中国鼠妇 测试项目地址:https://github.com/TheBeastofwar/SCL-Progress
- 刚开始我看到学长在群里发了一个有关什么poc的教程,以为要开发武器之类的,没想到是底层；然后,我们在5月19日搞了个教育部攻防演练,我测试了多个网站,但是只有6个网站符合0-day利用条件,其中别的师傅在两个网站写了马,但是因为webshell特征太明显了(不论从静态代码层面,还是从动态流量层面),所以分别只给了我们十几分钟的时间进行利用,导致那次RCE得到的分数既然和后台弱口令分数一样,都是100分。这是一个遗憾,学长要我们写一些底层代码,但我这个项目在常规的三大主流webshell管理工具(蚁剑,冰蝎,哥斯拉)有多了些新点子,也基于一些协议,隧道,系统,二进制等相对底层的知识,所以打算先把这个项目先用python基本完成一些常用功能,然后再看一些webshell研究的文章之类的
- 至于这个工具为什么叫鼠妇,一个原因是因为蚁剑和冰蝎都是昆虫,另一个原因是这个工具相对蚁剑和冰蝎比较垃圾。
- 目前,针对webshell检测研究,我打算通过配备ip代理池绕过ip访问频率检查,并发中量或大量垃圾访问数据包绕过检测文件访问频率统计,效仿cobaltstrike那样的流量加密,学习一点webshell的免杀技巧(虽然另一个学长说没人研究这个),尽量实现无感渗透(尽量),还有其他等等
- 因为我主要想学习webshell的隐匿术,所以在功能上相对比较少,只有命令执行功能,后续打算添加文件管理,内网穿透,数据库管理,二进制木马(像cs那样)等功能,如果还有精力的话打算用别的语言重构
- 7.12 冰蝎2.0流量分析

# moonflowersl

# SabYic

# hellowoe23

# kryonsir

# moukok
####  CS61A：
- 7.12 lab0
- 7.14 lab1
# Detectiveyw

# shuiyc


# lmarch2
- CS50P Introduction to Programming with Python
- 感觉把coding lab当成了一个学习新语言的机会了，并没有搞什么复杂的project，更多的是抱着学习pyhton
  的态度去看一些课，做一些homework来巩固知识
- 贴一个学习过程中做的一些丑陋的[笔记](https://www.notion.so/Python-eaa75da8d05c4f7dbed9e780dd1946bf?pvs=4)
- 一些简单的lab放在我[仓库](https://github.com/lmarch2/CS50P)了
=======

# Chinazhuzi
- 学习PHP 弱类型语言
```php
<?php
show_source(__FILE__);
include("config.php");
$a=@$_GET['a'];
$b=@$_GET['b'];
if($a==0 and $a){
    echo $flag1;
}
if(is_numeric($b)){
    exit();
}
if($b>1234){
    echo $flag2;
}
?>
```
- 有两种比较方式 == 和===
- 第一种会发生类型转化，比较转化后的结果是否相等，后者先比较类型是否一样。
- 字符串如果数字开头则转成数字，字母开头会转换成0

# AlmostGPH
8.2 好久没学习了，手痒痒，决定列个清单先
- MIT-Missing-Semester
- 0day安全
- 汇编语言
- 计算机组成原理