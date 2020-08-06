## 简介
爱奇艺自动签到。

## 功能
爱奇艺签到、做任务、抽奖等（仅支持VIP），签7天奖1天，14天奖2天，28天奖7天；日常任务；随机成长值；抽奖

## 使用
* 1.登录爱奇艺（IQIYI）官网https://www.iqiyi.com/，按F12开发者工具，加载主页面，在Network-Doc中找到cookies，获取P00001，P00003参数
![爱奇艺 参数抓取](https://i.loli.net/2020/07/30/WIEJzHQYTAs7jcR.jpg)
* 2.Server酱推送提醒，需要填写sckey，官网：https://sc.ftqq.com/3.version
* 3.上传至scf云函数  
  *注：超时时间设置为900*
* 4.添加定时触发器  
