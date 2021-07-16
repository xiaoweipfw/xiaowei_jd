# 个人学习目的，请下载后24小时内删除下载的代码

不要直接Fork!!!
请建立完仓库在Fork！！！！
以上所有脚本均来自其他大佬开发，此类脚本为整合脚本
本人非大佬，定时更新各类整合脚本，失效脚本会及时删除
拥有此库等于拥有所有！！！

## 交流群
### 1群 681030097
### 2群 681030097

# 拉取仓库
##### 名称

```
【脚本技术交流群】
```
##### 命令

```
ql repo https://ghproxy.com/https://github.com/JDWXX/JD.git "jd_|jx_|getJDCookie" "activity|backUp" "^jd[^_]|USER"

```
##### 定时规则

```
0 10 0 * * *
```

### 任务执行缺少文件 
##### sendNotify.js，手动从本库里下至 /QL/scripts 目录下，其他文件同理


## 安装依赖
#### 【图形验证】

```
docker exec -it QL bash -c "cd scripts && npm i -S png-js"
```

#### 【canvas】

```
docker exec -it QL bash -c "apk add --no-cache build-base g++ cairo-dev pango-dev giflib-dev && cd scripts && npm install canvas --build-from-source"
```

# python 脚本

## 入会 【jd_rh.py】
##### 退会,会有黑号风险

## 刷微信、支付宝步数 【jd_bs.py】
##### 下载小米运动软件，注册账号密码，绑定微信支付宝，通过宝塔在 jd_bs.py 文件里添加账号密码即可


# 助力配置
## 青龙面板-配置文件里添加 

## 签到领现金配置
### 自行添加变量设置邀请码 格式如下 默认10个

```
export cashinviteCode=""
export cashinviteCode2=""
export cashinviteCode3=""
```

## jd_cashHelp.py【签到领现金】

```
jd_cashHelp.py 文件里设置  cash_zlzh = ['', '', '', '', '', '', '', ''] 对应pin
```

## 柠檬推一推
#### 五元无门槛红包大概需要50 ck
##### 每天会变，软件手动分享至QQ复制

```
export tytpacketId=""
```

## 柠檬是兄弟就砍我

##### packetId 你要参加砍价的邀请码
##### actId 你要参加砍价的商品ID
```
export actId=""
export packetId="" 
```

## 邀请有礼
#### zdtx 设置为true自动抢提现100
```
export yqm="UtYmOqFJrh4Sl45d4mqg6Q%3D%3D"
export zdtx=false
```



## 店铺签到
#### 店铺签到 各类店铺签到，有新的店铺直接添加token即可
#### 活动地址:
#### 活动时间：长期
#### 更新时间：2021-07-13 12:00
#### 脚本兼容: QuantumultX, Surge,Loon, JSBox, Node.js
#### 搬运cui521大佬脚本

### 方式一

```
export MyShopToken1='30DE3F2E8B4278A120007C8CD0D4F835'
export MyShopToken2='3C0B9CE1F01623C77ADE9F90AFA0FD5F'
export MyShopToken3='4A02128626C3691B6A98341C3F8CD27E'
export MyShopToken4='81F530105DFF92EF55FF36F1E2097066'
export MyShopToken5='9B45653CFEFE49045C2748E8AA9E37B4'
export MyShopToken6='B8157420EE77DDA819C2B3BAF991797B'
export MyShopToken7='BB80E573A5329D6AD511900955F6E12C'
export MyShopToken8='DCD2E2F3BECE2344E21ABB33D071BFAE'
export MyShopToken9='F9C7E6B7E724B7DB0CE232508C97490D'

export SHOP_TOKENS="${MyShopToken1}&${MyShopToken2}&${MyShopToken3}&${MyShopToken4}&${MyShopToken5}&${MyShopToken6}&${MyShopToken7}&${MyShopToken8}&${MyShopToken9}"

```

### 方式二

```
export SHOP_TOKENS="30DE3F2E8B4278A120007C8CD0D4F835&3C0B9CE1F01623C77ADE9F90AFA0FD5F&4A02128626C3691B6A98341C3F8CD27E&81F530105DFF92EF55FF36F1E2097066&9B45653CFEFE49045C2748E8AA9E37B4&B8157420EE77DDA819C2B3BAF991797B&BB80E573A5329D6AD511900955F6E12C&DCD2E2F3BECE2344E21ABB33D071BFAE&F9C7E6B7E724B7DB0CE232508C97490D"
```

## 愤怒的锦鲤

### 填写 pt_pin
```
export kois=""
```

## 发财翻翻乐 每天0.3现金

## 柠檬发财大赢家
##### 先执行 柠檬发财大赢家获取邀请码，查看日志，从日志里获取 redEnvelopeId 和 inviter，添加至配置文件

```
export redEnvelopeId="a45166e259694002a32cb978fc188fae64711626364924409"
export inviter="gL9wXhsUV10DVlTsq_ND9A"
```

## 送豆得豆
### 脚本jd_senbeans.js
### 脚本会根据你总CK数量计算出共能助力几个账号，然后默认给前几名的账号助力【所以自己的号要放前面】
#### 例如有75个CK，通过计算大致可以助力7个号，那只有几个账号能拿到助力奖励


## 种豆得豆
#### 先运行 【获取互助码】 拿到助力码
#### 同一个京东账号的好友互助码用@符号隔开,不同京东账号之间用&符号或者换行隔开,下面给一个示例
#### 如: 京东账号1的shareCode1@京东账号1的shareCode2&京东账号2的shareCode1@京东账号2的shareCode2

```
export PlantBeanShareCodes = [
'4npkonnsy7xi22wlv5uh6flmp7i5q4kdxohvhba@26s3haczpmd7g7uxiegiyu5pvy@olmijoxgmjutziswjsb5yxftpa3vsecfd7ek23a@ta4sxnqpkjahbsy2e4wajgkhke@e7lhibzb3zek2cwflxxsmq2rjtbejb2mhvdkxra@giv74teqyhpdab5jcziie6harq@adubibkuqx7mxkqyhnlsdht3bq3h7wlwy7o5jii@xzyoc2ytoasw4zpuoti4idcshgnpxumxqb3jjji',//账号一的好友shareCode,不同好友中间用@符号隔开
'4npkonnsy7xi22wlv5uh6flmp7i5q4kdxohvhba@26s3haczpmd7g7uxiegiyu5pvy@olmijoxgmjutziswjsb5yxftpa3vsecfd7ek23a@ta4sxnqpkjahbsy2e4wajgkhke@e7lhibzb3zek2cwflxxsmq2rjtbejb2mhvdkxra@giv74teqyhpdab5jcziie6harq@adubibkuqx7mxkqyhnlsdht3bq3h7wlwy7o5jii@xzyoc2ytoasw4zpuoti4idcshgnpxumxqb3jjji',//账号二的好友shareCode，不同好友中间用@符号隔开
]
```