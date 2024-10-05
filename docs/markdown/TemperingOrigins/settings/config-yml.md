## 开启非玩家实体套装粒子特效(默认值: false)

该配置开启后可能会导致服务器严重卡顿

```yaml line-numbers
OtherEntitySuitEffect: false
```

## 保护符lore行识别符号(默认值: §a§l保护符: )

该配置用于插件识别物品的lore哪行为保护符判断\
如果判断到了则会尝试获取其保护符的相关配置\
该项配置不可为空也不可以跟其他识别符号相同

```yaml line-numbers
PROTECT_RUNE_JUDGE: "§a§l保护符: "
```

如果觉得不好看可以这样修改

```yaml line-numbers
PROTECT_RUNE_JUDGE: "§a§b§c§d§m§r"
```

这样子即可做到不影响判断又可以高自定义度的去达到自己想要的效果

## 属性lore行识别符号(默认值: §e§l淬炼属性: )

该配置用于插件识别物品的lore哪行为淬炼添加\
如果判断到了则会在淬炼的时候清理掉然后在添加淬炼结果\
该项配置不可为空也不可以跟其他识别符号相同

```yaml line-numbers
LEVEL_JUDGE: "§e§l淬炼属性: "
```

如果觉得不好看可以这样修改

```yaml line-numbers
LEVEL_JUDGE: "§c§b§c§d§m§r"
```

这样子即可做到不影响判断又可以高自定义度的去达到自己想要的效果

## 移星界面标题(默认值: 淬炼移星)

该项不可为空且建议不要过于简单越复杂越好

```yaml line-numbers
MoveLevelInvTitle: "淬炼移星"
```

如果觉得黑的好看也就是默认效果建议改为这样子的

```yaml line-numbers
MoveLevelInvTitle: "§d§b§c§d§m§r§0淬炼移星"
```

这样子可以避免在一些还没更新1.1.1的服务器出现的bug