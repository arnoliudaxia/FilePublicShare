## Clash 教程收集
- https://docs.cfw.lbyczf.com/
- https://yattazen.com/tutorial/clash-custom-config.html

## Clash全局配置文件

https://github.com/ACL4SSR/ACL4SSR/blob/master/Clash/GeneralClashConfig.yml


## 分流碎片规则 list文件说明

```
# 表示包含xxx.com域名后缀下的所有网站链接
DOMAIN-SUFFIX,xxx.com

# 表示包含这个xxxx域名关键词的所有网站链接
DOMAIN-KEYWORD,xxxx
```

更多：https://docs.cfw.lbyczf.com/contents/ui/profiles/rules.html


## 分流策略组 ini文件

```
custom_proxy_group=🇭🇰 香港节点`url-test`(港|HK|Hong Kong)`http://www.gstatic.com/generate_204`300,,50
custom_proxy_group=🇯🇵 日本节点`url-test`(日本|川日|东京|大阪|泉日|埼玉|沪日|深日|[^-]日|JP|Japan)`http://www.gstatic.com/generate_204`300,,50
custom_proxy_group=🇺🇲 美国节点`url-test`(美|波特兰|达拉斯|俄勒冈|凤凰城|费利蒙|硅谷|拉斯维加斯|洛杉矶|圣何塞|圣克拉拉|西雅图|芝加哥|US|United States)`http://www.gstatic.com/generate_204`300,,150
custom_proxy_group=🇨🇳 台湾节点`url-test`(台|新北|彰化|TW|Taiwan)`http://www.gstatic.com/generate_204`300,,50
custom_proxy_group=🇸🇬 狮城节点`url-test`(新加坡|坡|狮城|SG|Singapore)`http://www.gstatic.com/generate_204`300,,50
custom_proxy_group=🇰🇷 韩国节点`url-test`(KR|Korea|KOR|首尔|韩|韓)`http://www.gstatic.com/generate_204`300,,50
custom_proxy_group=🎥 奈飞节点`select`(NF|奈飞|解锁|Netflix|NETFLIX|Media)
```