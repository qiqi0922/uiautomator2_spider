# 通过uiautomator2实现的滴滴外卖app数据抓取

### 1、需要登录滴滴外卖app
### 2、需要使用位置修改app修改当前所在位置，如滴滴外卖仅开通了无锡，南京，郑州，泰州，成都5个城市，因此需要使用位置修改器定位到这5个城市。
### 3、使用uiautomator2启动滴滴外卖app，并实现模拟点击滑动等操作
### 4、通过使用手机代理，使用mitmdump进行数据解析并实现数据入库
####   mitmdump -s handle_decode.py -p 8889

### bug：dazhuang_python@sina.com
