|  |  |
| --- | --- |
| **BEP编号:** | 0 |
| **标题:** | BitTorrent增强提案索引 |
| **版本:** | cc019ba660805f441593d565cd930a4d1f4ae471 |
| **最后修改时间:** | `2018年7月20日 星期五 09:34:18 -0700` |
| **作者:** | David Harrison <dave@bittorrent.com> |
| **状态:** | 活跃 |
| **类型:** | 流程类 |
| **创建日期:** | 2008年1月10日 |
| **修订历史:** | 2012年10月13日: 更新文档仓库链接 |


BitTorrent社区论坛负责协调BitTorrent协议族及其参考实现的开发工作。Bram Cohen的愿景是保持BitTorrent主线Python实现的开源性，并借鉴Python增强提案（PEP）流程来设计协议开发机制[^1]。

本文档索引所有BitTorrent增强提案（BEP）。当新提案提交时，BitTorrent.org的编辑之一将为其分配一个BEP编号并适时更新本索引。每个文档拥有永久不变的编号，其历史变更记录通过git进行维护[^2]。

# 已定稿及现行流程类BEP

| 编号 | 标题 |
| --- | --- |
| [0](/已定稿及现行流程类BEP/bep_0000_cn.md) | [BitTorrent增强提案索引](/已定稿及现行流程类BEP/bep_0000_cn.md) |
| [1](/已定稿及现行流程类BEP/bep_0001_cn.md) | [BEP流程规范](/已定稿及现行流程类BEP/bep_0001_cn.md) |
| [2](/已定稿及现行流程类BEP/bep_0002_cn.md) | [reStructuredText 格式的 BEP 模板范例](/已定稿及现行流程类BEP/bep_0002_cn.md) |
| [3](/已定稿及现行流程类BEP/bep_0003_cn.md) | [BitTorrent协议规范](/已定稿及现行流程类BEP/bep_0003_cn.md) |
| [4](/已定稿及现行流程类BEP/bep_0004_cn.md) | [已知编号分配](/已定稿及现行流程类BEP/bep_0004_cn.md) |
| [20](/已定稿及现行流程类BEP/bep_0020_cn.md) | [Peer ID命名惯例](/已定稿及现行流程类BEP/bep_0020_cn.md) |
| [1000](/已定稿及现行流程类BEP/bep_1000_cn.md) | [待定标准追踪文档](/已定稿及现行流程类BEP/bep_1000_cn.md) |

# 已接受的BEP

此类BEP描述已在一种或多种BitTorrent实现中部署并验证有效的技术机制。它们可能需进行细微修订，在获得[终身仁慈独裁者（BDFL）](https://zh.wikipedia.org/wiki/%E7%BB%88%E8%BA%AB%E4%BB%81%E6%85%88%E7%8B%AC%E8%A3%81%E8%80%85)的最终批准后方可转为定稿状态。

| 编号 | 标题 |
| --- | --- |
| [5](/已接受的BEP/bep_0005_cn.md) | [DHT协议](/已接受的BEP/bep_0005_cn.md) |
| [6](/已接受的BEP/bep_0006_cn.md) | [快速扩展](/已接受的BEP/bep_0006_cn.md) |
| [9](/已接受的BEP/bep_0009_cn.md) | [Peer间元数据文件传输扩展](/已接受的BEP/bep_0009_cn.md) |
| [10](/已接受的BEP/bep_0010_cn.md) | [扩展协议](/已接受的BEP/bep_0010_cn.md) |
| [11](/已接受的BEP/bep_0011_cn.md) | [Peer交换（PEX）](/已接受的BEP/bep_0011_cn.md) |
| [12](/已接受的BEP/bep_0012_cn.md) | [多追踪器元数据扩展](/已接受的BEP/bep_0012_cn.md) |
| [14](/已接受的BEP/bep_0014_cn.md) | [本地服务发现](/已接受的BEP/bep_0014_cn.md) |
| [15](/已接受的BEP/bep_0015_cn.md) | [UDP追踪器协议](/已接受的BEP/bep_0015_cn.md) |
| [19](/已接受的BEP/bep_0019_cn.md) | [HTTP/FTP做种（GetRight风格）](/已接受的BEP/bep_0019_cn.md) |
| [23](/已接受的BEP/bep_0023_cn.md) | [追踪器返回紧凑Peer列表](/已接受的BEP/bep_0023_cn.md) |
| [27](/已接受的BEP/bep_0027_cn.md) | [私有种子](/已接受的BEP/bep_0027_cn.md) |
| [29](/已接受的BEP/bep_0029_cn.md) | [uTorrent传输协议](/已接受的BEP/bep_0029_cn.md) |
| [55](/已接受的BEP/bep_0055_cn.md) | [打洞扩展](/已接受的BEP/bep_0055_cn.md) |

# 草案阶段的BEP

以下BEP正处于标准化审议阶段。

| 编号 | 标题 |
| --- | --- |
| [7](/草案阶段的BEP/bep_0007_cn.md) | [IPv6追踪器扩展](/草案阶段的BEP/bep_0007_cn.md) |
| [16](/草案阶段的BEP/bep_0016_cn.md) | [超级做种](/草案阶段的BEP/bep_0016_cn.md) |
| [17](/草案阶段的BEP/bep_0017_cn.md) | [HTTP做种（Hoffman风格）](/草案阶段的BEP/bep_0017_cn.md) |
| [21](/草案阶段的BEP/bep_0021_cn.md) | [部分做种扩展](/草案阶段的BEP/bep_0021_cn.md) |
| [24](/草案阶段的BEP/bep_0024_cn.md) | [追踪器返回外部IP](/草案阶段的BEP/bep_0024_cn.md) |
| [30](/草案阶段的BEP/bep_0030_cn.md) | [Merkle树种子扩展](/草案阶段的BEP/bep_0030_cn.md) |
| [31](/草案阶段的BEP/bep_0031_cn.md) | [追踪器故障重试扩展](/草案阶段的BEP/bep_0031_cn.md) |
| [32](/草案阶段的BEP/bep_0032_cn.md) | [DHT的IPv6扩展](/草案阶段的BEP/bep_0032_cn.md) |
| [33](/草案阶段的BEP/bep_0033_cn.md) | [DHT刮擦](/草案阶段的BEP/bep_0033_cn.md) |
| [34](/草案阶段的BEP/bep_0034_cn.md) | [DNS追踪器偏好设置](/草案阶段的BEP/bep_0034_cn.md) |
| [35](/草案阶段的BEP/bep_0035_cn.md) | [种子签名](/草案阶段的BEP/bep_0035_cn.md) |
| [36](/草案阶段的BEP/bep_0036_cn.md) | [种子RSS订阅源](/草案阶段的BEP/bep_0036_cn.md) |
| [38](/草案阶段的BEP/bep_0038_cn.md) | [通过种子文件提示定位本地数据](/草案阶段的BEP/bep_0038_cn.md) |
| [39](/草案阶段的BEP/bep_0039_cn.md) | [通过订阅URL更新种子](/草案阶段的BEP/bep_0039_cn.md) |
| [40](/草案阶段的BEP/bep_0040_cn.md) | [规范Peer优先级](/草案阶段的BEP/bep_0040_cn.md) |
| [41](/草案阶段的BEP/bep_0041_cn.md) | [UDP追踪器协议扩展](/草案阶段的BEP/bep_0041_cn.md) |
| [42](/草案阶段的BEP/bep_0042_cn.md) | [DHT安全扩展](/草案阶段的BEP/bep_0042_cn.md) |
| [43](/草案阶段的BEP/bep_0043_cn.md) | [只读DHT节点](/草案阶段的BEP/bep_0043_cn.md) |
| [44](/草案阶段的BEP/bep_0044_cn.md) | [在DHT中存储任意数据](/草案阶段的BEP/bep_0044_cn.md) |
| [45](/草案阶段的BEP/bep_0045_cn.md) | [BitTorrent DHT的多地址操作](/草案阶段的BEP/bep_0045_cn.md) |
| [46](/草案阶段的BEP/bep_0046_cn.md) | [通过DHT可变项更新种子](/草案阶段的BEP/bep_0046_cn.md) |
| [47](/草案阶段的BEP/bep_0047_cn.md) | [填充文件及扩展文件属性](/草案阶段的BEP/bep_0047_cn.md) |
| [48](/草案阶段的BEP/bep_0048_cn.md) | [追踪器协议扩展：刮擦](/草案阶段的BEP/bep_0048_cn.md) |
| [49](/草案阶段的BEP/bep_0049_cn.md) | [分布式种子订阅源](/草案阶段的BEP/bep_0049_cn.md) |
| [50](/草案阶段的BEP/bep_0050_cn.md) | [发布/订阅协议](/草案阶段的BEP/bep_0050_cn.md) |
| [51](/草案阶段的BEP/bep_0051_cn.md) | [DHT Infohash索引](/草案阶段的BEP/bep_0051_cn.md) |
| [52](/草案阶段的BEP/bep_0052_cn.md) | [BitTorrent协议规范v2](/草案阶段的BEP/bep_0052_cn.md) |
| [53](/草案阶段的BEP/bep_0053_cn.md) | [Magnet URI扩展 - 选择特定文件索引下载](/草案阶段的BEP/bep_0053_cn.md) |
| [54](/草案阶段的BEP/bep_0054_cn.md) | [lt_donthave扩展](/草案阶段的BEP/bep_0054_cn.md) |

# 已延期的BEP

编辑认为下列BEP目前未向标准化推进，但尚未正式撤回。

| 编号 | 标题 |
| --- | --- |
| [8](/已延期的BEP/bep_0008_cn.md) | [追踪器Peer混淆](/已延期的BEP/bep_0008_cn.md) |
| [18](/已延期的BEP/bep_0018_cn.md) | [搜索引擎规范](/已延期的BEP/bep_0018_cn.md) |
| [22](/已延期的BEP/bep_0022_cn.md) | [BitTorrent本地追踪器发现协议](/已延期的BEP/bep_0022_cn.md) |
| [26](/已延期的BEP/bep_0026_cn.md) | [Zeroconf Peer通告与发现](/已延期的BEP/bep_0026_cn.md) |
| [28](/已延期的BEP/bep_0028_cn.md) | [追踪器交换](/已延期的BEP/bep_0028_cn.md) |

# 已撤回BEP

当前无已撤回的BEP。

# 已否决BEP

当前无已否决的BEP。

[^1]: http://www.python.org/dev/peps/
[^2]: https://github.com/bittorrent/bittorrent.org