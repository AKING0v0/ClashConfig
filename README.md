# Clash 及订阅转换配置文件

## 自定义 Mihomo 配置文件
https://raw.githubusercontent.com/AKING0v0/ClashConfig/refs/heads/main/Clash_Config.yaml  
配置文件修改自 [Aethersailor](https://raw.githubusercontent.com/Aethersailor/Custom_OpenClash_Rules/refs/heads/main/cfg/yaml/Custom_Clash.yaml)

核心分流规则基于 [Loyalsoldier](https://github.com/loyalsoldier/v2ray-rules-dat) 的 geosite 和 geoip 数据库，并采用 ⁠.mrs⁠ 二进制格式。这种方式摒弃了传统的 ⁠classical⁠ 匹配模式，有效降低了系统的解析开销，显著提升了路由分流的运行速度与整体性能。

如果想用传统方式分流可参考下面的覆写配置文件。

## 自定义 Mihomo 覆写配置文件
https://raw.githubusercontent.com/AKING0v0/ClashConfig/refs/heads/main/Override_Config.yaml

## 自定义 订阅转换 配置转换 规则转换 的远程配置
https://raw.githubusercontent.com/AKING0v0/ClashConfig/refs/heads/main/SubConv_Config.ini  
订阅转换配置修改自 [ACL4SSR](https://git.moezx.cc/mashiro/ACL4SSR/raw/branch/master/Clash/config/ACL4SSR_Online_Full.ini) 与 [zsokami](https://raw.githubusercontent.com/zsokami/ACL4SSR/main/ACL4SSR_Online_Full_Mannix.ini)
### 补充说明
由于ACL4SSR规则停更，所以替换了一部分 [ios_rule_script](https://github.com/blackmatrix7/ios_rule_script) 规则。

移除
- 🛑 广告拦截
- 🍃 应用净化
- 📢 谷歌FCM
- Ⓜ️ 微软Bing
- Ⓜ️ 微软云盘
- 🎶 网易音乐
- 🎮 游戏平台
- 📺 巴哈姆特
- 🌏 国内媒体
- 🌍 国外媒体

重命名
- Ⓜ️ 微软服务 -> 🪟 微软服务
- 🚀 节点选择 -> ✈️ 起飞选择
- 🚀 手动切换 -> 👆🏻 手动切换
- ♻️ 自动选择 -> ⚡ 最低延迟

新增
- 🎓 学术平台
- 🧊 冷门国家

url-test                                  
- 间隔时间 300秒 -> 120秒
- 容差 50/150毫秒 -> 60毫秒

## 📈 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=AKING0v0/ClashConfig&&type=Date)](https://www.star-history.com/#AKING0v0/ClashConfig&Date)

---
**如果这个项目对你有帮助，请给个 Star ⭐️ 吧！**
