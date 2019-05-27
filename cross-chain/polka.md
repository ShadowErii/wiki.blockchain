# Awesome 波卡（Polkadot）

波卡（Polkadot）开发资源整理收集， 为 Substrate 开发者导航。

## 波卡 Polkadot 项目

### 项目官方及白皮书
* [polkadot.network](https://polkadot.network/)
* [web3 基金会](https://web3.foundation/)
* [Polkadot(波卡链)白皮书](https://polkadot.network/PolkaDotPaper.pdf)
* [Polkadot(波卡链)白皮书-中文版](https://learnblockchain.cn/2019/05/17/polkadot-whitepaper/)
* [Github](https://github.com/paritytech/polkadot)
* [Polkadot Wiki](http://wiki.polkadot.network/)
* [polkadot Medium 博客](https://medium.com/polkadot-network)
* [Web3 基金会博客](https://medium.com/web3foundation)

### 浏览器及钱包 等基础设施

* [polkascan](https://polkascan.io/) - 区块浏览器
* [Polka.io](http://polka.io/) – 区块浏览器
* [polkadot telemetry](https://telemetry.polkadot.io/#/Alexander) - Polkadot 波卡网络
* [Enzyme](https://getenzyme.dev) – 浏览器插件钱包
* [Polkawallet](https://polkawallet.io) – 移动端钱包
* [Polkabot](https://gitlab.com/Polkabot) – 网络监测和报告机器人
* Polkasource – ITSM for blockchain infrastructure ([announcement 5](https://medium.com/polkadot-network/deploying-substrate-polkadot-nodes-with-polkasource-5835a7bea1b3))
* [substraTEE](https://github.com/scs/substraTEE) - substrate runtime in Trusted Execution Environment
* [Validators 5](http://validators.com/) — Open Source Scalable Cluster ([GitHub](https://github.com/Validators))
* [Polkadash](http://polkadash.io/) – 验证人监测

## 开发

### Substrate 开发框架

Substrate 框架从 polkadot 的结构中抽取出来，使广大的开发者开发区块链时不用再被区块链复杂的底层设施如p2p，共识机制等所困扰，而可以专注全部的力量开发自己链上的功能

* [substrate](https://www.parity.io/substrate/)
* [substrate 开发者中心](https://docs.substrate.dev)
* [Substrate 教学](https://shawntabrizi.com/substrate-collectables-workshop/#/)

### 技术博客

* [Substrate 来了](https://www.parity.io/substrate-has-arrived/) - 英文博客介绍Substrate
* [什么是 Substrate](https://medium.com/paritytech/what-is-substrate-29af4231d7e0) 
* [在Substrate建立代币精选清单（TCR）](https://github.com/gautamdhameja/substrate-tcr)
* [在Substrate实现ERC721](https://github.com/parity-samples/substrate-erc721)
* [使用Substrate Events监听器构建和维护基于Substrate运行时事件的链下存储](https://github.com/parity-samples/substrate-events-listener)
* [如何在Polkadot测试网络部署Polkadot平行链](https://www.youtube.com/watch?v=pDqkzvA4C0E) - Youtube 视频
* [Polkadot共识的创新之路](https://mp.weixin.qq.com/s/183qRjjoVqCyK7zPfgH6HA) - 郭光华做的有关Polkadot共识相关的主题的分享
* [Substrate 概览和在ChainX系统中的应用](https://mp.weixin.qq.com/s/AjQ10yk-VsmS-HdREgjBTQ) - 金程鑫的分享

### 库

* [Polkadot 开发实例](http://wiki.polkadot.network/en/latest/polkadot/build/examples/)
* [polkadot-js](https://polkadot.js.org/api) [GitHub](https://github.com/polkadot-js) - polkadot 的 JavaScript 类库
* [substrate-ui](https://github.com/paritytech/substrate-ui) 通过[oo7 控件库](https://github.com/paritytech/oo7) 创建，[oo7 文档](https://paritytech.github.io/oo7/)
* [substrate](https://www.parity.io/substrate/)

### 开发工具

* Noise Explorer – Rust code generator for formally verified (Noise/ cryptographic) handshakes ([GitHub 1](https://github.com/SymbolicSoft/noiseexplorer))
* Clovyr – service to easily build a blockchain ([demo 33](https://twitter.com/web3jp/status/1024808350658093056))
* [Chainhammer 4](https://github.com/drandreaskrueger/chainhammer) — Multi-chain performance testing tool ([GitHub 4](https://github.com/drandreaskrueger/chainhammer))
* Agoric – secure smart contracts ([website 21](https://agoric.com/))

### Polkadot 实现

* [Parity Polkadot](https://github.com/paritytech/polkadot) – Parity 基于[Substrate](https://github.com/paritytech/substrate) 开发的Rust 客户端 。
* [Gossamer](https://github.com/ChainSafeSystems/gossamer) – A Go implementation being built by [ChainSafe Systems](https://github.com/ChainSafeSystems), which is also building an Eth 2.0 Serenity client. ([grant announcement 10](https://medium.com/web3foundation/w3f-grants-chainsafe-to-implement-polkadot-runtime-environment-in-go-ca4973c9edaf)).
* [Polkadot-JS 3](https://github.com/polkadot-js) – A JavaScript [client](https://github.com/polkadot-js/client) and tool set developed by [Polkadot JS](https://polkadot.js.org/).
* [Golkadot](https://github.com/opennetsys/golkadot) – [OpenNetSys](https://opennetsys.com/) 开发的  Polkadot Substrate GO 实现版本。
* [Kagome](https://github.com/soramitsu/kagome) – C++ implementation of the Polkadot Runtime Environment being built by [Soramitsu](https://github.com/soramitsu). As part of the process they are developing a libp2p networking layer in C++.


## [Polkadot 及 Substrate 生态项目](https://forum.web3.foundation/t/teams-building-on-polkadot/67)

* [ChainX](https://chainx.org/) - 跨链资产互通
* [Dothereum](https://twitter.com/dothereum?lang=en)
* [Edgeware](https://edgewa.re/) - 构建基于WASM的智能合约平台
* [ChainLink](https://chain.link) 打造去中心化的 oracle 预言机网络(链) ([合作声明](https://medium.com/web3foundation/web3-foundation-and-chainlink-announce-collaboration-df55ed462a3a))
* [LayerX ZeroChain](https://github.com/LayerXcom/zero-chain) – 基于 Substrate 的 zK-SNARKs 链
* [Asure Network](https://www.asure.network/) – 基于 Substrate 社交网络链
* [Plasm ](https://github.com/stakedtechnologies/Plasm)  – Substrate 上的 Plasma
* Speckle OS – 身份ID 链 ([声明](https://medium.com/polkadot-network/dots-and-speckle-paving-the-way-forward-for-the-new-web-691beed50f1a))
* [Blink Network](https://blink.network/) – 可快速支付交易链
* [MXC – IoT 链](https://www.mxc.org/)  - 为机器对机器通信设置IoT标准（MXC协议）
* [PACTCare Starlog](https://github.com/PACTCare/Starlog) – 基于Substrate的元数据区块链 
* 0x protocol – 去中心化交易所 ([Tweet](https://twitter.com/recmo/status/1081637877027549190?s=09))
* [Aragon](https://twitter.com/rzurrer/status/1090201496753504259) – 去中心化组织 DAOs
* [ Ocean Protocol](https://blog.oceanprotocol.com/decentralized-web-summit-2018-highlights-a6376edefb01)– 共享数据生态
* [Energy Web Foundation](https://www.parity.io/private-transactions-webassembly-and-permissioning-new-features-energy-web-foundation-blockchain-for-energy/) – 能源链
* [iExec](https://medium.com/iex-ec/dev-letter-24-sidechain-approach-7cab5de2e54a) – 去中心化云计算
* [Robonomics](https://twitter.com/AIRA_Robonomics/status/1079001376452210689) 网络物理系统
* [Katallassos](https://katallassos.com/) – 链上金融
* [Joystream](https://blog.joystream.org/sparta/) – 用户管理的视频平台 
* [Kilt Protocol ](https://kiltprotocol.com/)– 身份信托市场
* [Akropolis](https://medium.com/akropolis/hello-world-ae16b654ba71) - 全球养老金基础设施
* [Agora.Trade](https//agora.trade/) – 非托管交易的加密货币交换
