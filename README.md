---
title: Python练习册
date: 2016-12-31 11:35:04
tags: [Python,Python_camp]
---
> [参考代码](https://github.com/mmmwhy/python-camp)一同附上，分析过程见[李飞阳](http://feiyang.li/tags/Python-camp/)，请多指教。

---


# 一、基础问题

**题目1.1：**[图片加水印](http://feiyang.li/2016/12/31/python_camp1/)，类似于微信未读信息数量那种提示效果

![头像](http://cdn.mmmxcc.cn/blog/20161216/115246388.jpg?imageMogr2/thumbnail/!80p)


**题目1.2：**[使用 Python 如何生成 200 个激活码（或者优惠券）](http://feiyang.li/2017/02/07/python_camp2/)

**题目1.3**：[将 0002 题生成的 200 个激活码（或者优惠券）保存到 **MySQL** 关系型数据库中。 ](http://feiyang.li/2017/02/10/python_camp3/)


**题目1.4：**[任一个英文的纯文本文件，统计其中的单词出现的个数。](http://feiyang.li/2017/02/11/python_camp4/)

**题目1.5：**[你有一个目录，装了很多照片，把它们的尺寸变成都不大于 iPhone5 分辨率的大小。](http://feiyang.li/2017/02/13/python-camp5/)

**题目1.6：**[使用 Python 生成类似于下图中的**字母验证码图片**](http://feiyang.li/2017/02/13/python-camp6/)

![字母验证码](http://cdn.mmmxcc.cn/blog/20170210/164221438.png)

- [阅读资料](http://stackoverflow.com/questions/2823316/generate-a-random-letter-in-python) 

**题目1.7：**[ 敏感词文本文件 filtered_words.txt，里面的内容为以下内容，当用户输入敏感词语时，则打印出 Freedom，否则打印出 Human Rights。](http://feiyang.li/2017/02/15/python-camp7/)

    北京
    程序员
    公务员
    领导
    牛比
    牛逼
    你娘
    你妈
    love
    sex
    jiangge

**题目1.8：** [纯文本文件 student.txt为学生信息, 里面的内容（包括花括号）如下所示：](http://feiyang.li/2017/02/15/python-camp8/)

    {
        "1":["张三",150,120,100],
        "2":["李四",90,99,95],
        "3":["王五",60,66,68]
    }

请将上述内容写到 student.xls 文件中，如下图所示：

![student.xls](http://cdn.mmmxcc.cn/blog/20170210/164341562.png)

- [阅读资料](http://www.cnblogs.com/skynet/archive/2013/05/06/3063245.html) 腾讯游戏开发 XML 和 Excel 内容相互转换

**题目1.9：** [通常，登陆某个网站或者 APP，需要使用用户名和密码。密码是如何加密后存储起来的呢？请使用 Python 对密码加密。](http://feiyang.li/2017/02/16/python-camp9/)

- 阅读资料 [用户密码的存储与 Python 示例](http://zhuoqiang.me/password-storage-and-python-example.html)

- 阅读资料 [Hashing Strings with Python](http://www.pythoncentral.io/hashing-strings-with-python/)

- 阅读资料 [Python's safest method to store and retrieve passwords from a database](http://stackoverflow.com/questions/2572099/pythons-safest-method-to-store-and-retrieve-passwords-from-a-database)

**题目1.10：** [python输入二维数组](http://feiyang.li/2017/03/10/python-input/)

---
# 二、数据分析

**题目2.1：**[你有一个目录，放了你一个月的日记，都是 txt，为了避免分词的问题，假设内容都是英文，请统计出你认为每篇日记最重要的词。](http://feiyang.li/2017/02/17/python-camp2-1/)

**题目2.2：**有个目录，里面是你自己写过的程序，统计一下你写过多少行代码。包括空行和注释，但是要分别列出来。

**题目2.3：** [登陆中国联通网上营业厅](http://iservice.10010.com/index_.html) 后选择「自助服务」 --> 「详单查询」，然后选择你要查询的时间段，点击「查询」按钮，查询结果页面的最下方，点击「导出」，就会生成类似于 2014年10月01日～2014年10月31日通话详单.xls 文件。写代码，对每月通话时间做个统计。

---
# 三、爬虫方面

**题目3.1：**一个HTML文件，找出里面的**正文**。

**题目3.2：**[一个HTML文件，找出里面的**链接**。](http://feiyang.li/2016/12/13/get_html/)

**题目3.3：** 用 Python 写一个爬图片的程序，可以参考[Python爬取图片（使用urllib2）](http://feiyang.li/2016/12/15/Python_use_urllib2/)，如果出现问题，可以尝试[selenium自动化测试工具](http://feiyang.li/2016/12/29/Python-selenium/)



---
#  四、Web问题

**题目4.1：** 使用 Python 的 Web 框架，做一个 Web 版本 留言簿 应用。

[阅读资料：Python 有哪些 Web 框架](http://v2ex.com/t/151643#reply53)

- ![留言簿参考](http://cdn.mmmxcc.cn/blog/20170210/164432170.png)


**题目4.2：** 使用 Python 的 Web 框架，做一个 Web 版本 TodoList 应用。

- ![SpringSide 版TodoList](http://cdn.mmmxcc.cn/blog/20170210/164451954.png)



**题目来自 [易枭寒的Github](https://github.com/Yixiaohan)**
