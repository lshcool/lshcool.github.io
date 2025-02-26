# 时间戳命名


## 微软拼音自定义时间戳

![微软拼音如何快速打出日期和时间](https://oss.sssmoe.com/wp-content/uploads/2024/09/20240907041735472.png)



**右键 – 用户自定义短语 – 添加**

![微软拼音如何快速打出日期和时间](https://oss.sssmoe.com/wp-content/uploads/2024/09/20240907041842583.png)

**输入代码**

```
%yyyy% 年 %MM% 月 %dd% 日 %HH%:%mm%:%ss%
我想要的是一串日期和时间数字，用来作静态文章的文件名，方便管理。所以，把多余的空格和符号汉字去掉即可。
%yyyy%%MM%%dd%%HH%%mm%%ss%
```

## 搜狗拼音自定义时间戳

顺便把搜狗拼音医生版的也设置一下， 咦，按照上面的方法不行呀。

一查才知道，原来代码不一样。

![微软拼音如何快速打出日期和时间](https://oss.sssmoe.com/wp-content/uploads/2024/09/20240907044545908.png)

搜狗拼音用英文单词作代码

```
$year$month_mm$day_dd$fullhour_hh$minute$second
值得注意的，如上图，前面必须加一个 # 
```

