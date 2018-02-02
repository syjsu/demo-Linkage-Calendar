Linkage calendar
---
更新日志
---
- 解决了日期与月份的问题
![image](http://m.qpic.cn/psb?/V12ZEwXZ3XJLHy/V8UlAqMrGWG1117sZNN4KdH9PnHxS2hGWmB0YFWCVw0!/b/dJIAAAAAAAAA&bo=NwS1ATcEtQEDByI!&rf=viewer_4)


- 之前的月份与日期不对应截图
![image](http://m.qpic.cn/psb?/V12ZEwXZ3XJLHy/xIC9aYsi7q7WktA.D.6Hvrr7Hb2NO2ji8DIWdRb3nBQ!/b/dJEAAAAAAAAA&bo=CwRvAQAAAAADB0M!&rf=viewer_4)

项目简介
---
功能：
1. 左右边两边的日历关联
2. 显示当前日期（红色字体）当月过完的天（灰色字体）当月没过的天（蓝色字体）
3. 点击上方按钮动态切换月份

学到了什么？如何进一步改进？
---
1. Date.getMonth() 从0-11 注意一定要 +1 才是当前月份
2. 最好使用documentFragment来添加到dom里，这样可以提高性能
3. 两个月份如何可以按顺序显示
4. 熟练使用了date对象
5. 可以用取余的方法来代替月份在边界时的判断，简约代码
