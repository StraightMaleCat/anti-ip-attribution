# anti-ip-attribution
针对部分网站显示IP归属地的流量分流规则

任何工具的配置文件都欢迎提交。

项目作者无法保证配置文件一定能起到作用，有可能会触发账号风控。

## 使用之前
请在使用前详细阅读`rules.yaml`内容，内部注释包含部分可选规则，请酌情参考。

建议Fork自己的一份配置文件，不要直接使用最新的。

## 自动生成的配置文件
|                        文件                        |                             用途                             |
| :------------------------------------------------: | :----------------------------------------------------------: |
|        [parser.yaml](generated/parser.yaml)        | 适用于Clash for Windows的配置文件预处理功能，详见https://docs.cfw.lbyczf.com/contents/parser.html |
| [rule-provider.yaml](generated/rule-provider.yaml) | 适用于Clash的Rule Provider功能，详见https://lancellc.gitbook.io/clash/clash-config-file/rule-provider |
|         [surge.list](generated/surge.list)         |                        Surge分流规则                         |
|   [quantumultx.list](generated/quantumultx.list)   |                     QuantumultX分流规则                      |

## 其他版本
|                        文件                        |                             用途                             |
| :------------------------------------------------: | :----------------------------------------------------------: |
| [anti-ip-attribution.list](https://raw.githubusercontent.com/ddgksf2013/Cuttlefish/master/Filter/anti-ip-attribution.list)| QuantumultX分流（感谢@ddgksf2013）|

## 关于自动生成
本仓库使用GitHub Actions从`rules.yaml`中生成配置文件，详见`generate.py`。

## 配置文件（已弃用，不再更新）
**这些文件和链接将在v0.3.0版本后移除。**

建议在使用前详细阅读`cfw.yaml`内容，并验证其他配置文件是否与其保持更新。

| 文件                | 用途                                        |
| -------------------- | ------------------------------------------- |
| [cfw.yaml](cfw.yaml) | 适用于Clash for Windows的配置文件预处理功能 |
| [Anti_IP_Surge.list](Anti_IP_Surge.list)| Surge规则集（感谢@Vinetan）|
| TODO                 | TODO                                        |

## PR
仓库所有者和开发者的能力不能保证持续、高效维护地此仓库。如若发现改进或更好的方案，欢迎PR。

只需要修改`rules.yaml`，其余配置文件会自动生成。

## 使用提示
不建议使用手机客户端访问这些网站，应用可能会包含难以寻找的API地址或直接利用手机定位获取信息。

## 免责声明
本项目仅用于学习交流，请在遵守所在地法律法规的前提下使用。

本项目记录的API域名地址信息可以被任何人通过开发人员工具获取，没有经过逆向工程或网络攻击，不构成入侵计算机系统。

请不要在中华人民共和国境内使用此项目。

## Star History
[![Star History Chart](https://api.star-history.com/svg?repos=lwd-temp/anti-ip-attribution&type=Date)](https://star-history.com/#lwd-temp/anti-ip-attribution&Date)
