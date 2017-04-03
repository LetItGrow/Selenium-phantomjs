# Selenium-Phantomjs

* 多线程并发抓取 天眼通 js动态页面 
* 自动创建mysql数据库、数据表
* 解析字段随意添加，程序会自动帮创建数据表字段
* 加入了随机伪装头headers，代理ip
* 采用lxml xpath解析处理响应信息
* 实现主页面跳转到分页面，垂直深度抓取

# todo:

* 正在写一个代理ip系统，随后接到本程序上。主要实现：
   1. 抓取网络上各大免费代理ip网站ip数据
   2. 保存到sqlite中
   3. 验证代理ip有效性
   4. 对有效性进行标记，以便清理无效ip
 * 加入重试参数（主要为大范围抓取防止遗漏）
 
 # selenium 滑动验证码破解:
 
![Crack Geetest](./huadongpojie/huadongpojie1.gif)
---
![Crack Geetest](./huadongpojie/huadongpojie2.gif)
---
![Crack Geetest](./huadongpojie/huadongpojie3.gif)
