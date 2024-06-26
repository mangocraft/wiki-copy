# 常用命令速查表

!> **查询前请注意**

- 本表格仅包含芒果方块粉丝服常见命令的介绍，具体的命令说明、操作方法等请查阅[插件帮助](plugins)。
- 如无特殊说明，如果需要手持物品，均为**主手持有**。
- 部分命令收费或征税，备注为 **“收费”**。收费明细请参考 [经济规则](economic.md)。

## 传送类

| 命令| 说明| 备注 |
| - | - | - |
| `/spawn` | 返回默认出生点 | 当前为三城主城 |
| `/back` | 返回上一次传送前所在位置<br/> |
| `/home` | 传送回家 | 基岩版可通过菜单操作
| `/home [家的名称]` | 传送回指定名称的家 |
| `/home bed` | 传送回你上一次使用过的床的位置 |
| `/sethome`  | 设置家 |
| `/sethome [家的名称]` | 设置一个家 | 基岩版可通过菜单操作
| `/delhome [家的名称]`| 删除一个家 |
| `/tpa [玩家 ID]` | 将自己传送到对方身边 | 传送前需经对方同意 |
| `/tpagui` | TPA菜单 | 传送前需经对方同意 |
| `/tpahere [玩家 ID]` | 邀请对方传送到自己身边 | 需经对方确认同意 |
| `/tpauto [玩家 ID]` | 自动同意TP请求 | 慎用 |
| `/rtp`  | 进行随机传送 | 十分钟一次 |
| `/warp zhucheng`  | 传送至当前主城 | 目前为三城主城 |
| `/warp mdzc`  | 传送至末地主城 | 非末地出生点 |
| `/warp dyzc`  | 传送至地狱交通中心点 | 目前为三城主城地狱门枢纽 |

## 经济 / 领地类


| 命令 | 说明 | 备注 |
| - | - | - |
| `/bal` | 查看现金余额 | |
| `/pay [玩家 ID] [金额]` | 转账给指定玩家 | 执行后**立即转账**，请慎用<br/>
| `/res create [领地 ID]` | 创建一个领地 | 付费<br/>
| `/res remove [领地 ID]` | 删除一个领地 | 删除领地不退钱，慎重操作<br/>
| `/res padd [领地 ID] [玩家 ID]` | 添加领地的信任玩家 | 基岩版可通过菜单操作<br/>
| `/res pdel [领地 ID] [玩家 ID]` | 删除领地的信任玩家 | 基岩版可通过菜单操作<br/>
| `/res set ` | 设置一个领地的都公共权限 | 基岩版可通过菜单操作<br/>
| `/res pset [领地 ID] [玩家 ID] [权限 ID] true/false` | 设置一个领地的玩家权限 | 基岩版可通过菜单操作<br/>
| `/res tp [领地 ID]` | 传送至某一领地 | 基岩版可通过菜单操作<br/>


## 服务器状态查询

| 命令| 说明 | 备注 |
| - | - | - |
| `/list`<br>`/plist` | 列出当前在主服务器的玩家 | 昵称可覆盖游戏 ID 显示 |
| `/co i` | 进入方块变更查询模式，左键点方块、右键点箱子以查询<br>再执行一次以退出该模式 | 仅在怀疑有失窃、破坏等情况时使用 |
