# 简介
Surge、Shadowrocket、Pepi(ShadowRay)、Kitsunebi、Postern 的配置规则

# 使用
- 规则不提供节点。
- 规则主推黑名单模式，被 ☭ 和速度极慢的网站才走代理。
- 连接公共 Wi-Fi 时可暂时关闭待连接成功后再开启，否则可能出现验证页面无法加载的情况。
- Surge 规则预设了4个无效节点方便修改在图形界面修改，修改时仅修改节点相关配置即可，**不要修改名称**。配置更多节点时建议在「在文本模式中编辑」进行修改，务必做到配置中的 [Proxy] 和 [Proxy Group] 段首名称信息一一对应才不会报错。
- Kitsunebi 每次规则导入不会清空以前的规则，所以需先「删除全部规则」再倒入，也不建议和其他规则叠压使用：[Kitsunebi 导入配置](https://diveng.io/import-profile-on-kitsunebi.html)

**关于特别版**

特别版主要针对屏蔽应用内的数据追踪、行为分析以及运营商劫持。

- 网页广告请使用 Safari 内容拦截器如 [ADGuard](https://itunes.apple.com/app/apple-store/id1047223162?pt=31050800&ct=web_18675&mt=8) （在「过滤器」中添加「ChinaList+EasyList」） 或自带去广告功能的浏览器。
- 对于 Surge 和 Shadowrocket 使用特别版建议安装 MitM 证书（如果介意需关闭 MitM 功能），具体方法：
  - [Surge 导入配置及安装证书](https://diveng.io/import-profile-and-install-certificate-on-surge.html)
  - [Shadowrocket 导入配置及安装证书](https://diveng.io/import-profile-and-install-certificate-on-shadowrocket.html)

# 规则

**标准版**

Surge / Kitsunebi / Postern

[https://raw.githubusercontent.com/ConnersHua/Profiles/master/Surge.conf](https://raw.githubusercontent.com/ConnersHua/Profiles/master/Surge.conf)

Shadowrocket / Pepi(ShadowRay)

[https://raw.githubusercontent.com/ConnersHua/Profiles/master/Shadow.conf](https://raw.githubusercontent.com/ConnersHua/Profiles/master/Shadow.conf)

**特别版**

Surge / Kitsunebi / Postern

[https://raw.githubusercontent.com/ConnersHua/Profiles/master/SurgeS.conf](https://raw.githubusercontent.com/ConnersHua/Profiles/master/SurgeS.conf)

Shadowrocket / Pepi(ShadowRay)

[https://raw.githubusercontent.com/ConnersHua/Profiles/master/ShadowS.conf](https://raw.githubusercontent.com/ConnersHua/Profiles/master/ShadowS.conf)

# 感谢

> [lhie1](https://github.com/lhie1) - 旧版特别版去广告基于其规则

> Lison Bin - 完善 Apple、WhatsApp、Line 相关规则

> [linjiacheng](https://github.com/linjiacheng) - 解决盯盯拍无法使用的问题

# 许可

转载需注明作者及项目地址
