# 其他

## 密码破解

### 方法

- 试错
  - 穷举：尝试所有的候选密码
  - 字典攻击：通过事先收集好的候选密码进行尝试
- 破解 (已获得加密或者散列处理后的密码数据的情况)
  - 通过穷举，字典攻击进行类推：采用试错相同的方法，现对候选密码进行加密，再进行比对
  - 彩虹表：使用一张由明文密码和其散列值对应的数据表来进行查找
  - 拿到密钥：拿到共享密钥
  - 加密算法漏洞

## 点击劫持

利用透明的链接覆盖在页面之上，诱使用户在不知情的情况下点击来达到攻击的目的

## DoS攻击

拒绝服务攻击（英语：denial-of-service attack，缩写：DoS attack、DoS）亦称洪水攻击，是一种网络攻击手法，其目的在于**使目标电脑的网络或系统资源耗尽，使服务暂时中断或停止，导致其正常用户无法访问**。当黑客使用网络上两个或以上被攻陷的电脑作为“僵尸”向特定的目标发动“拒绝服务”式攻击时，其称为分布式拒绝服务攻击（distributed denial-of-service attack，缩写：DDoS attack、DDoS）。据2014年统计，被确认为大规模DDoS的攻击已达平均每小时28次。攻击发起者一般针对重要服务进行攻击，如银行，信用卡支付网关，甚至根域名服务器。

## 后门

指开发时设置的隐藏入口，可以使用原本受限制的功能