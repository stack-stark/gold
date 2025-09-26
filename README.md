# 金价雷达  

## 功能特色

- 每5分钟（可配置）更新获取当前国际金价和国内金价，展示在状态栏，方便随时查看当前黄金价格情况。

- 根据配置的预警价格规则进行预警提醒。

- 点击StatusBar展示黄金价格走势图表

- 右键或者ALT+5快捷键可以手动刷新黄金价格

- 收盘提醒功能，14:50,14:55两次提醒收盘。

- 价格类型配置项，支持选择显示AU9999或XAU国际金价

## 配置 ⚙️

在 vscode 设置中搜索`GoldPriceRadar`,根据提示配置即可。

| ID| 说明 | 默认值 |
|-|-|-|
| goldPriceRadar.updateInterval | 数据更新间隔（分钟）| 5
| goldPriceRadar.earlyWarningInterval | 预警间隔（分钟） | 30 |
| goldPriceRadar.earlyWarningMAx | 高于这个价格将会提醒 | 800
| goldPriceRadar.earlyWarningMin | 低于这个价格将会提醒 | 700
| goldPriceRadar.closingReminder | 收盘提醒 | true
| goldPriceRadar.priceType | 价格类型，Au9999国内金价，XAU国际金价 | Au9999


