# mineall

Go语言编写性能极高，升级算法，抽水平稳0算力损耗，Web后台实时查看实时算力和抽水算力，Web后台HTTPS访问，支持本地部署混淆加密客户端。

一键安装，一键备份还原，Web界面操作，简单易用，小白可以轻松上手。

支持开机自启动，进程守护运行，自动调整连接数限制。

目前已支持币种 Eth Etc Btc Ltc Ergo Rvn CFX ETF ETHW KAS  持续更新中。。。


# 一键安装升级命令

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/mineall/minerProxy/main/ssminer.sh)"
```

> 选择 `1`  安装程序；

> 选择 `2`  更新程序；

> 选择 `3`  查看服务状态；

> 选择 `4`  卸载程序。

# 更新日志

版本：v1.6.20

1.增加币种ETF ETHW KAS，已支持币种 Eth Etc Btc Ltc Ergo Rvn CFX ETF ETHW KAS。

2.BTC矿池，新增 BTC.COM ；LTC矿池，新增 鱼池F2POOL。

3.修复内存溢出问题，实测100台机器，仅占用60M内存。

4.优化算法，支持亚米、芯动等专业机。

版本：v1.6.15

1.优化抽水算法

2.增加币种CFX，已支持币种 Eth Etc Btc Ltc Ergo Rvn CFX。

3.优化BTC

版本：v1.6.14

增加币种Ergo，已支持币种 Eth Etc Btc Ltc Ergo Rvn。

版本：v1.6.13

强烈建议16.12版本升至16.13，修复了16.12的一个己知BUG。

版本：v1.6.12

增加币种 Ltc，已支持币种ETH ETC BTC  LTC。

版本：v1.5.6

1.增加芯片机亚米的支持。

2.矿池配置文件支持导入导出。

3.支持币种ETH ETC BTC，BTC增加鱼池 。
