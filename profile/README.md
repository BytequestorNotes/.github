> 现在要学的是“攻击者思维”。

------

# 你的最终路线（2026版）

## 第一阶段（0~2个月）

目标：把开发思维切换成漏洞思维

### 学习内容

#### HTTP

必须掌握：

- Cookie
- Session
- JWT
- Authorization
- Origin
- Referer

#### Burp Suite

重点：

- Proxy
- Repeater

做到：

```text
抓包
改包
重放
```

#### PortSwigger

顺序：

```text
Access Control
↓
Authentication
↓
API Testing
```

重点关注：

```text
IDOR(BOLA)
Broken Access Control
JWT
API权限
```

------

## 第二阶段（2~4个月）

目标：

```text
建立现代Web安全认知
```

学习：

### OAuth2

理解：

```text
用户
客户端
授权服务器
资源服务器
```

### GraphQL

理解：

```text
Schema
Introspection
Query
Mutation
```

### API Security

重点：

```text
权限
对象归属
批量接口
```

------

## 第三阶段（4~6个月）

目标：

```text
开始研究真实漏洞
```

每天：

1篇公开报告。

来源：

[HackerOne Hacktivity](https://hackerone.com/hacktivity?utm_source=chatgpt.com)

只看：

```text
IDOR
API
OAuth
Access Control
```

------

开始问自己：

```text
为什么想到测这里？
```

而不是：

```text
payload是什么？
```

------

## 第四阶段（6~9个月）

目标：

```text
学会找攻击面
```

学习：

### Recon

重点：

- 子域名发现
- API发现
- Swagger发现
- GraphQL发现

工具：

[ProjectDiscovery Blog](https://projectdiscovery.io/blog?utm_source=chatgpt.com)

------

这一步非常关键。

因为：

```text
漏洞猎人
≠
漏洞利用者
```

真正赚钱的是：

```text
发现别人没发现的地方
```

------

## 第五阶段（9~12个月）

目标：

```text
开始稳定实战
```

注册：

- [HackerOne](https://hackerone.com/?utm_source=chatgpt.com)
- [Bugcrowd](https://www.bugcrowd.com/?utm_source=chatgpt.com)
- [Intigriti](https://www.intigriti.com/?utm_source=chatgpt.com)

优先：

```text
VDP
中小项目
```

不要一开始冲 Google。

------

# 什么时候开始看 BruteCat？

### 现在

可以关注：

- [BruteCat Blog](https://brutecat.com/?utm_source=chatgpt.com)
- [BruteCat X](https://x.com/brutecat?utm_source=chatgpt.com)

但是：

```text
收藏
关注
```

即可。

------

### 2~3个月后

学完：

```text
Access Control
Authentication
API Testing
OAuth基础
GraphQL基础
```

再开始认真看。

这时候收获会翻倍。

------

# 只允许选一个长期跟踪的大佬

如果只能选一个。

我会选：

**BruteCat**

原因：

他的研究方向和你未来最匹配：

```text
API
OAuth
GraphQL
攻击面发现
```

而不是：

```text
浏览器0day
内核漏洞
逆向工程
```

------

# 关于国内SRC培训

这是我最想认真回答你的部分。

我的看法：

### 可以看

但是：

```text
把它当案例库
不要当路线图
```

------

很多培训老师分享的漏洞：

```text
Swagger泄露
测试环境
越权
信息泄露
```

这些都有学习价值。

因为：

```text
能帮你认识漏洞长什么样
```

------

但是不要陷入：

```text
学一个漏洞
找一个漏洞
```

模式。

否则会出现：

```text
老师没教过
不会测
```

------

你真正要学的是：

```text
老师为什么想到测这里
```

------

所以：

### 国内培训

看

### 盲目跟洞

不看

------

# 最后说说心态

这是所有赏金猎人都会经历的。

很多新人以为：

```text
学3个月
↓
拿赏金
```

实际上真实情况往往是：

```text
学3个月
↓
没洞

学6个月
↓
没洞

学9个月
↓
还是没洞

突然某一天
第一个有效报告
```

------

因为挖洞是一个特别反直觉的领域。

你学Java：

```text
今天学
明天会
```

比较明显。

------

挖洞往往是：

```text
积累100个失败案例
↓
形成思维
↓
第101次发现问题
```

------

所以我送你一句最重要的话：

> **不要用“挖到多少洞”衡量成长，要用“今天比昨天多理解了一个系统为什么会出错”来衡量成长。**

因为赏金猎人最值钱的资产从来不是某个漏洞，而是：

```text
看到一个系统
↓
迅速建立权限模型
↓
找到信任边界
↓
发现异常点
```

的能力。

而从我们这几天的交流来看，你最大的优势其实不是安全，而是：

> 你懂开发、懂数据库、懂云计算、懂系统是怎么搭起来的。

这种背景的人，一旦补上安全思维，往往比单纯背漏洞的人走得更远。

所以接下来一年，你的任务不是追热点，不是买课程，不是疯狂收集漏洞技巧。

而是：

```text
Access Control
↓
Authentication
↓
API Security
↓
OAuth
↓
GraphQL
↓
Recon
```

把这条主线走通。

走通以后，再回头看 BruteCat、CTBB、Google VRP，你会发现自己已经从“听故事的人”，慢慢变成了“能看懂他们为什么这么做的人”。这时候，真正的成长才开始。