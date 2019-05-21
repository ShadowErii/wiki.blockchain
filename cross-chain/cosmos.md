# Awesome Cosmos
**Cosmos 开发资源整理收集， 为 Cosmos 开发者导航**。

## Cosmos 简介

Cosmos（准确来讲应该是 Cosmos Hub）是 Tendermint 团队推出的一个支持跨链交互的异构网络，目标是创建一个区块链互联网，允许大量自主且易开发的区块链互相扩展和交互。

Cosmos Hub 基于 Cosmos SDK 开发，用户也可以基于 Cosmos SDK  快速定制开发自己的链。 Cosmos SDK 则是构建在 **tendermint** core (采用拜占庭共识算法+pos）及 ABCI（Application Blockchain Interface）协议 之上，其实现了ABCI协议，同时把一些通用模块标准化，如staking（抵押机制）、slashing（惩罚机制）、IBC（跨链功能），账户accounts、治理、奖励&手续费等。

## Cosmos & Tendermint

- [Cosmos 白皮书](https://cosmos.network/whitepaper) [github](https://cosmos.network/whitepaper)
- [Cosmos 官网](https://cosmos.network) 
- [Cosmos GitHub 地址](https://github.com/cosmos)
- [Tendermint 官网](https://tendermint.com)
- [Tendermint GitHub](https://github.com/tendermint/tendermint)

## 开发教程

- [Cosmos SDK 文档](https://cosmos.network/docs/)
- [Cosmos SDK 中文文档](https://github.com/cosmos/cosmos-sdk/tree/master/docs/translations/cn)
- [Tendermint 文档 - 英文](https://tendermint.com/docs/)
- [基于Cosmos 构建区块链及应用教程](https://github.com/cosmos/sdk-application-tutorial/blob/master/tutorial/cn/README.md) [教程目录](https://github.com/cosmos/sdk-application-tutorial/tree/master/tutorial/cn)
- [Cosmos IBC 说明](https://github.com/cosmos/ibc/blob/master/CosmosIBCSpecification.pdf)


## Cosmos 生态项目

基于 Cosmos 的项目，目前已经有近百个，这里列举几个代表：

- [IRISnet](https://www.irisnet.org/) - 为下一代分布式商业应用提供基础设施，[区块浏览器](https://www.irisplorer.io/#/home)。

  IRISnet（IRIS Hub ）是早期使用 Cosmos SDK 的项目（还贡献了部分代码），也是Cosmos在中国的技术和运营合作伙伴，IRIS Hub（类似Cosmos Hub）是 Cosmos网络中的第一个重要的区域性枢纽，Cosmos Hub 和 IRIS Hub 将直接连接。
- [币安链](https://docs.binance.org/index.html) - 去中心化交易所
- [Loom PlasmaChain](https://loomx.io) 以太坊Layer2 解决方案 

