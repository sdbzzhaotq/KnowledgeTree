# 补课路线图

## 写在前面
Notion非常好，用它来记录平时碰到的知识点，时常整理汇集一下。

暂时的学习知识点顺序:<br>
1. C++ 11 以侯捷为主
2. C++ 并发编程
3. LeetCode
4. 深度学习
5. 线性代数

*****

## Tips
老码农总结的常用变量及其缩写，[链接](https://zhuanlan.zhihu.com/p/395995314)，自己备份一下，[本地链接](tips/abbr.md)
*****

## 1. C++ (C++ 11, 并发编程)
[高清 1080P 侯捷——C++11新特性](https://www.youtube.com/watch?v=TJIb9TGfDIw&list=PL-X74YXt4LVYo_bk-jHMV5T3LHRYRbZoH) <br>
[P1](https://www.youtube.com/watch?v=Ko2gkRf548o)
[P14](https://www.youtube.com/watch?v=sxBR8LK33Cg)

*****

## 2. Linux

### 1. 定时器

发现一个很好的[资源](http://www.ilovecpp.com/2019/01/16/timer/#more)<br>
[源代码](https://gist.github.com/baixiangcpp/b2199f1f1c7108f22f47d2ca617f6960)

<details>
<summary>代码</summary>
<pre>
<code>
int dispatch()
{
    ...
    TimerManager tm;
    tm.addTimer(1000, []() { std::cout << "hello world" << std::endl; }, NULL);
    tm.addTimer(5000, []() { std::cout << "hello baixiancpp" << std::endl; }, NULL);
    for(;;)
    {
        int ret = epoll_wait(epollfd,events,events_num,tm.getRecentTimeout());
        tm.takeAllTimeout();
    }
    ...
}
</code>
</pre>
</details>



***

## 3. 操作系统


公开课 北京大学 操作系统原理（Operating Systems） [coursera](https://www.coursera.org/learn/os-pku/home/welcome)

***
## 4. 数据结构/算法
LeetCode

*** 
## 5. OpenCV
一个很好的YouTube视频，[LEARN OPENCV C++ in 4 HOURS | Including 3x Projects | Computer Vision](https://www.youtube.com/watch?v=2FYm3GOonhk)
已经下载1080P资源，并上传至OneDrive[共享](https://khaitanpublicschool-my.sharepoint.com/:v:/g/personal/ztq519_odcn_live/ET5pqFKzdUxBkRaaTuF5PSEB4IKJsCB8HjNOVd27DColxw?e=YDhirx)

*****

# 帖子大杂烩

[YouTube 上有哪些计算机方面的值得推荐的公开课](https://www.zhihu.com/question/49071324)

[MIT-Challenge](https://chenyuxiaodhr.github.io/zh-CN/CS-Learning/MIT-Challenge/)

# 计算机

## 操作系统



# Operating Systems: Three Easy Pieces
[在线书籍](http://pages.cs.wisc.edu/~remzi/OSTEP/)<br>
[源码](https://github.com/remzi-arpacidusseau/ostep-code)

# 同步
[Linux条件变量pthread_condition细节（为何先加锁，pthread_cond_wait为何先解锁，返回时又加锁）](https://blog.csdn.net/shichao1470/article/details/89856443) <br>
[多线程同步与锁的本质](https://steemit.com/cn-programming/@cifer/7t9mdm) <br>
[有了互斥量，为什么还需要条件变量](https://www.cnblogs.com/liuchengchuxiao/p/4332197.html)  防止不停查询，浪费CPU <br>
## 算法

### Leecode

一个比较好的的github: [地址](https://github.com/azl397985856/leetcode) <br>
对应的个人网站 (https://leetcode-solution.cn)

# 数学

## 线性代数
https://github.com/liuguoyou/Introduction-to-Linear-Algebra-5th-Edition---EE16A
# 英语

## 单词本

单词

