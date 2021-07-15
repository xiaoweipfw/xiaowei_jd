
不要直接Fork!!!
请建立完仓库在Fork！！！！
以上所有脚本均来自其他大佬开发，此类脚本为整合脚本
本人非大佬，定时更新各类整合脚本，失效脚本会及时删除
拥有此库等于拥有所有！！！



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
export yqm="UtYmOqFJrh4Sl45d4mqg6Q%3D%3D"






