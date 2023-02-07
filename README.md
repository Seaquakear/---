# **基于Winform开发的强势股池筛选工具:**
### 1、工具说明：
该工具的数据获取是基于站点：MCNB金融数据库 获取的，可访问:[http://www.mycodenobug.com](http://www.mycodenobug.com) 了解更多股票数据的接口。
程序目前可以实现交易日开盘20分钟后的较为强势的股票池的获取，数据每隔10分钟会刷新一次，但是当前版本还需要用户在界面上点击“获取实时数据”按钮进行刷新。
![images](https://github.com/Seaquakear/DW2/blob/main/image/1.png)

### 2、licence说明：
由于本程序使用的是收费的接口和部分免费的数据接口，为了能吃得起饭，当前版本仅提供5个免费的licence供大家使用（每个licence每日可使用50次），后续升级版本后，这些key都还可以继续使用，请大家放心。用户也可以自行在微信公众号“小建数码”中购买收费的licence，这类licence将在后续所有的软件升级中，都可以使用。
```
5个免费licence：
g77wamtefpkybdrincve
im5tzzycd3hwlpl1cqij
1cvfwdmj4lqgdze6hy9o
9t8kb4mfrx14jgoe56fv
4hjds4p5hlagi3uwqoyi
```
### 3、程序目录说明：
程序接口非常简单，第一次使用时只需要在App.Config配置文件中配好licence信息，即可使用，简单方便。
Frm_Main为主程序窗体，默认运行的时候就会打开。
