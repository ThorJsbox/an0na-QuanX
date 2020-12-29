![an0na’s github stats](https://github-readme-stats.vercel.app/api?username=an0na&show_icons=true&theme=merko)

# 分流Filter
1. AdBlock.list
2. Apple.list
3. CMedia.list
4. GMedia.list
5. Mainland.list
6. Microsoft.list
7. NeteaseMusic.list
8. Netflix.list
9. Outside.list
10. PayPal.list
11. Speedtest.list
12. Telegram.list
13. YouTube.list
14. IOS_OTA.list

# 分流Ext
网易云音乐灰色音乐解锁服务器(一共五个)

# 复写Rewrite
1. Rewrite.conf 

# 参考
1. [Qure](https://github.com/Koolson/Qure)
2. [sve1r](https://github.com/sve1r/Rules-For-Quantumult-X)
3. [blackmatrix7](https://github.com/blackmatrix7/ios_rule_script)
4. [bigdargon](https://github.com/bigdargon/hostsVN)

# 笔记
`` 
https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/script/bilibili/bilibili_plus.qxrewrite, tag=Bilibili, update-interval=86400, opt-parser=false, enabled=true

^https?:\/\/weixin110\.qq\.com\/cgi-bin\/mmspamsupport-bin\/newredirectconfirmcgi url script-response-body https://raw.githubusercontent.com/HotKids/Rules/master/Script/weixin110.js 

hostname = weixin110.qq.com

^https?:\/\/weixin110\.qq\.com\/cgi-bin\/mmspamsupport-bin\/newredirectconfirmcgi url script-response-body https://raw.githubusercontent.com/HotKids/Rules/master/Script/weixin110.js

# > Meituan-Dianping - img.meituan.net,p*.meituan.net,s3plus.meituan.net,flowplus.meituan.net
^https?:\/\/img\.meituan\.net\/(adunion|display|midas)\/\w+\.(gif|jpg|jpg\.webp)$ url reject
^https?:\/\/(s3plus|flowplus)\.meituan\.net\/v\d\/\w+\/linglong\/\w+\.(gif|jpg|mp4) url reject
^https?:\/\/p\d\.meituan\.net\/(bizad|wmbanner)\/\w+\.jpg url reject
^https?:\/\/p\d\.meituan\.net\/movie\/\w+\.jpg\?may_covertWebp url reject

img.meituan.net,p*.meituan.net,s3plus.meituan.net,flowplus.meituan.net

 ``



