
不要直接Fork!!!
请建立完仓库在Fork！！！！
以上所有脚本均来自其他大佬开发，此类脚本为整合脚本
本人非大佬，定时更新各类整合脚本，失效脚本会及时删除
拥有此库等于拥有所有！！！

拉取代码

ql repo https://ghproxy.com/https://github.com/zll2317463866/tiger.git "jd_|jx_|getJDCookie|.js" "activity|backUp" "^jd[^_]|USER"


安装依赖
【图形验证】
docker exec -it QL bash -c "cd scripts && npm i -S png-js"
【canvas】
docker exec -it QL bash -c "apk add --no-cache build-base g++ cairo-dev pango-dev giflib-dev && cd scripts && npm install canvas --build-from-source"

## 签到领现金配置
### 自行添加变量设置邀请码 格式如下 默认10个
export cashinviteCode=""
export cashinviteCode2=""
export cashinviteCode3=""


## 签到领现金-助力 
jd_cashHelp.py 文件里设置  cash_zlzh = ['', '', '', '', '', '', '', ''] 对应pin






