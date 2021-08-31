---
description: '本文以weibo的数据为例，为什么以weibo为例呢？因为数据开源，我们爬得安安心心:-)。'
---

# 爬虫的正确食用方法✅

其实是Miss.why曾经做了很久的weibo小编，每日大量的数据让她头疼欲裂，学了Python以后就在想：

“（~~怎么才能偷这个懒呢~~）如何减少人力成本更新数据，实现数据可视化地自动更新呢？”

于是，**爬虫**+**自动化**+**数据可视化**的实践构想由此诞生。

### 孵化一只爬虫🕷需要做些什么

首先要打开世界的代码库**GitHub**，找一只**Weibo Spider**。

#### 安装

我们可以使用**源码安装**和**pip安装**两种方法。

**源码安装**

```text
git clone https://github.com/dataabc/weiboSpider.git
cd weiboSpider
pip install -r requirements.txt
```

**pip安装**

```text
python3 -m pip install weibo-spider
```

以上内容都是在**终端**中完成。



PS.千万不要忘记程序设置

安装后

```text
 python3 -m weibo_spider
```

当你第一次运行会生成**config.json**文件，请打开**config.json**文件，你会看到如下内容：

