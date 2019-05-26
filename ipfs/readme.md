# Awesome IPFS [![Awesome](/image/badge.svg)](https://github.com/lbc-team/wiki.blockchain)

IPFS 相关开发资源汇总

- [ipfs 官网](http://ipfs.io/)
- [IPFS](https://github.com/ipfs/go-ipfs) IPFS的GO语言实现
- [IPFS 原理](https://github.com/ipfs/ipfs)


## 文章

- [站在 Web3.0 理解 IPFS 是什么](https://learnblockchain.cn/2018/12/12/what-is-ipfs/)
- [IPFS 使用入门](https://learnblockchain.cn/2018/12/25/use-ipfs/)
-  [理解 IPFS 白皮书第2部分](https://decentralized.blog/understanding-the-ipfs-white-paper-part-2.html) 
-  [理解 IPFS 白皮书第1部分](https://decentralized.blog/understanding-the-ipfs-white-paper-part-1.html) 
- [Ipfs 中的内容标识符](https://pascalprecht.github.io/posts/content-identifiers-in-ipfs/) 
- [IPFS: 互联网民主化](https://medium.com/@tonywillenberg/web-3-0-a-truly-democratised-internet-f4b06cb4077b) 

## 工具源码

- [Blockwatch](https://ipfs.io/ipfs/QmdikpwcyeBuGaVzWzSzPuqvBfTGD8jPAVydcCjYHsBUxo/index.html) - 监测当前块链的块数，并设置警报(存储在您的浏览器中使用 PouchDB 的本地)时，某些块高度传递. [源码](https://github.com/MidnightLightning/ethereum-blockwatch)
- [cachewarmer](https://github.com/BrendanBenshoof/cachewarmer) - 捐赠 ipfs 网关以缓存其他人的内容
- [dillo-ipfs](https://ipfs.io/ipns/12D3KooWBG1fsFRF4ykpidXVNVnbon5KLfv67pkkGeFstrwftVVb/) -  用于 Dillo 网络浏览器的 IPFS 集成. [源码](https://git.scuttlebot.io/%25C35b%2BMlZ%2Fy5TT1e7SG66eNKEIdX5DRl9PRUxbhvO89k%3D.sha256)
- [gatsby-plugin-ipfs](https://github.com/moxystudio/gatsby-plugin-ipfs) - 通过确保资产是相对的，增加了对将盖茨比网站部署到 IPFS 的支持.
- [git-remote-ipfs](https://github.com/cryptix/git-remote-ipfs) - 从 IPFS push/pull 项目
- [http2ipfs](https://github.com/jbenet/http2ipfs-web) - 这是一个向 IPFS 节点添加 url 的简单网络工具.
- [ipcat](https://github.com/noffle/ipcat) - 检索 IPFS 对象数据并将其发送到 stdout.
- [ipfs-add-from-encrypted](https://github.com/TroyWilson1/ipfs-add-from-encrypted) - 用 AES256加密文件或目录，然后添加到 IPFS
- [ipfs-add-from-url](https://github.com/maxlath/ipfs-add-from-url) - 从 URL 而不是文件路径向 IPFS 添加文件
- [ipfs-chrome-extension](https://github.com/dylanPowers/ipfs-chrome-extension) - Chrome扩展程序将ipfs.io流量重定向到本地网关
- [ipfs-chrome-station](https://github.com/fbaiodias/ipfs-chrome-station) - Chrome扩展程序将ipfs.io流量重定向到本地网关
- [ipfs-common](https://github.com/arsyun/ipfs-common) - 一些常用的工具。 人类可读的 CID: 2。 Cid 和 block name 转换，3。 读一下 leveldb 的工具, [源码](https://github.com/arsyun/ipfs-common) 。
- [ipfs-companion](https://github.com/ipfs/ipfs-companion) - 浏览器扩展，简化对 IPFS 资源的访问.
- [ipfs-deploy](https://github.com/agentofuser/ipfs-deploy) - 部署静态网站的零配置 cd my-static-website && npx @agentofuser/ipfs-deploy
- [ipfs-gui](https://github.com/marcin212/ipfs-gui) -  Windows UI 集成和 IPFS 安装程序
- [ipfs-linux-service](https://github.com/dylanPowers/ipfs-linux-service) - IPFS Linux 初始化节点
- [ipfs-mount](https://github.com/richardschneider/net-ipfs-mount) - 在 Windows 上以映射驱动器的形式安装 IPFS
- [ipfs-paste](https://github.com/jbenet/ipfs-paste) - 将 stdin 和剪贴板粘贴到 IPFS
- [ipfs-screencap](https://github.com/jbenet/ipfs-screencap) - 捕捉截图，将它们发布到 IPFS，并将链接复制到剪贴板.
- [ipfscrape](https://github.com/victorbjelkholm/ipfscrape) - 搜集所有资产的网页，然后放到IPFS
- [ipfsecret](https://github.com/c2fo-lab/ipfsecret) - 使用秘密口令对 IPFS 文件进行加密和解密
- [mahuta](https://github.com/ConsenSys/Mahuta) - 为微服务体系结构提供的即插即用服务, 允许收集、存储 ipfs 上的数据并对其进行索引, 并提供搜索功能 (全文、查询)。
- [ipget](https://github.com/ipfs/ipget) - :satellite: 通过 IPFS 检索文件并在本地保存它们.
- [IPLD Explorer](https://explore.ipld.io) - 在浏览器中探索默克尔森林 [源码](https://github.com/ipfs-shipyard/ipld-explorer)
- [IPRedirect](https://github.com/JayBrown/IPRedirect) -  将 ipfs / ipns 地址重定向到本地网关的浏览器用户脚本。 这应该可以在任何还没有为它编写扩展，并且支持用户脚本的浏览器上工作.
- [ipscend](https://github.com/diasdavid/ipscend) - 在 IPFS 中托管网络应用程序和静态网站的工具
- [pinbot](https://github.com/whyrusleeping/pinbot) - Pin content via IRC
- [Public gateway status checker](https://ipfs.fooock.com) - 用于检查 IPFS 网关的公共状态 (包括延迟和网关可写状态) 的 web 应用 [源码](https://github.com/fooock/ipfs-gateway-checker)
- [Siderus Orion](https://orion.siderus.io) - 易于使用的 IPFS 桌面客户端， 支持macOS，Windows 和 Linux [源码](https://github.com/Siderus/Orion)
- [Sweet IPFS](https://github.com/hazae41/sweet-ipfs) - 一个Android应用

## 视频

- [Distributed Apps with IPFS - Juan Benet at Fullstack Fest 2016](https://www.youtube.com/watch?v=jONZtXMu03w) - 本演讲将详细介绍如何使用 CRDTs、 pub / sub 和灵巧 ui 构建一个基于 IPFS 的动态应用程序。 它还深入研究了分布式计算的新模型，以及分布网络的伦理重要性.
- [IPFS Alpha - 为什么我们必须重新分配网络](https://www.youtube.com/watch?v=skMTdSEaCtA) 
- [IPFS 简单解释](https://www.youtube.com/watch?v=5Uj6uR3fp-U) -  让我们来看看 IPFS 是如何工作的，它是如何解决像审查制度这样的问题的，以及它是否真的能在多个星球上工作
- [Juan Benet at Stanford 2015](https://www.youtube.com/watch?v=HUVmypx9HGI) - 演讲内容包括对 IPFS 项目的广泛了解，以及关于通过开放源码协议 R & D 发展网络栈的讨论.
- [Textile Build Series - 一个在线免费工作室](https://www.youtube.com/playlist?list=PLC8CEtJ9shDznO1tpvGe--BVEWmCKY9_Z) -教授开发者如何建立分散式网络的完整培训方案。 该系列涵盖了大量的内容，触摸 IPFS 栈的多个部分，并通过构建一个简单的 DApp 引导开发者.

## IPFS 应用

- [2read](https://2read.net) - 浏览器插件，将当前选项卡中的文章转换为可读形式（也支持上传）。 [源码](https://github.com/meehow/2read)
- [InterPlanetary Wayback](https://github.com/oduwsdl/ipwb) -Web 存档(WARC)使用 IPFS 进行索引和重播.
- [Interplanetary Wiki](https://github.com/jamescarlyle/ipfs-wiki) - 建立在 IPFS 之上的 Wiki
- [IPFessay](https://gitlab.com/stavros/IPFessay) - 以简单方式发表不受审查的文章在ipfs上.
- [IPFS Desktop](https://github.com/ipfs-shipyard/ipfs-desktop) - 在机器上运行 IPFS 节点，无需使用命令行工具。 管理您的节点，添加您的文件，轻松地更改设置... 只需一个界面.
- [IPFS Drive](http://ipfs-drive.ydns.eu) - IPFS 的浏览器文件管理器. [源码](https://github.com/fazo96/ipfs-drive)
- [IPFS Event Drop](https://github.com/travisperson/ipfs-event-drops) - 一个应用程序，可以改善可视化的 ipfs 事件.
- [3Box](https://3box.io) - 建立及管理你的个人档案及个人资料。 使用3box-js 库将配置文件集成到 dapp 中 [源码](https://github.com/uport-project/3box)
- [a js video player](https://github.com/ipfs/website/tree/master/content/docs/examples/webapps/play) - [Demo](https://ipfs.io/ipfs/QmVc6zuAneKJzicnJpfrqCH9gSy6bz54JhcypfJYhGUFQu/play#/ipfs/QmTKZgRNwDNZwHtJSjCp6r5FYefzpULfy37JvMt9DwvXs)
- [a markdown renderer](https://github.com/ipfs/website/tree/master/content/docs/examples/webapps/markdown-viewer) - [Demo](https://ipfs.io/ipfs/QmSrCRJmzE4zE1nAfWPbzVfanKQNBhp7ZWmMnEdbiLvYNh/mdown#/ipfs/QmfQ75DjAxYzxMP2hdm6o4wFwZS5t7uorEZ2pX9AKXEg2u)
- [a qr-code renderer](https://github.com/ipfs/website/tree/master/content/docs/examples/webapps/qr-render) - [Demo](https://ipfs.io/ipfs/QmccqhJg5wm5kNjAP4k4HrYxoqaXUGNuotDUqfvYBx8jrR/qr#enter%20text%20here)
- [akasha](http://akasha.world/) - 下一代社交媒体网络，使用 Ethereum 并嵌入 IPFS.
- [Alexandria](http://www.alexandria.io/learn/#integrated-technologies) - 分布式的内容发布/盈利平台
- [Arbore](http://arbo.re) - 一个基于 IPFS 的好友到好友文件共享应用程序.
- [Arpadyne](https://arpadyne.computes.com) - 全新的互联网-使用 orbitz 软件的 DNS。 通过 IPFS 传送的内容.
- [Autonomica "IPFS Social Proof"](https://github.com/IBM/ipfs-social-proof) - Autonomica 一个基于Dapp，通过发布的社交媒体和网络证明创造身份和证明身份.
- [beets](https://github.com/beetbox/beets) - Beets 提供了一个使用 IPFS 分享音乐库的插件
- [Blokaly](https://github.com/blokaly) -基于 IPFS 的图标发布、共享和显示平台.
- [Boards](https://ipfs.io/ipns/boards.ydns.eu) - 在浏览器中运行的分布式社交平台. [源码](https://github.com/fazo96/ipfs-boards)
- [brig](https://brig.readthedocs.io/en/latest) - 档案同步具有 git 样式接口和 FUSE 文件系统. [源码](https://github.com/sahib/brig)
- [Cohort](https://github.com/zignig/cohort) - 一个 golang 应用程序预设一个 threejs 界面，并获得其所有资产的 IPFS.
- [Computes](https://computes.io) - Computes.io 是一个基于ipfs的分布式计算平台.
- [dapple](https://github.com/nexusdev/dapple) -  Dapple 是一个坚实的开发者多工具，旨在管理日益复杂的相互联系的智能合同系统.
- [digx](https://www.dgx.io/) -  Digix 是一个建立在Ethereum 和IPFS的知识产权服务的资产分类平台 .
- [dtube](https://d.tube) -  使用ipfs进行后端存储的分布式视频与steem.it集成共享.
- [enzypt.io](https://enzypt.io/) - 通过以太坊和 IPFS 购买和出售文件的网站. [源码](https://github.com/flex-dapps/enzypt)
- [Ethlance](http://ethlance.com) - 第一次在以太坊和综合就业服务方案上建立完全分散的就业市场平台. [源码](https://github.com/madvas/ethlance)
- [FileNation](https://filenation.io/) - 使用 IPFS 将文件送往世界各地的最简单方法.
- [git-ipfs-rehost](https://github.com/whyrusleeping/git-ipfs-rehost) - 在 ipfs 中重新托管 git repos 的脚本.
- [Global Upload](https://globalupload.io/) - 为 IPFS 提供文件传输服务，将文件上传到分布式网络.
- [gogo.tattoo](http://gogo.tattoo) - Gogo Tattoo 项目使用 IPFS、 DLTs 和其他现代技术，为纹身艺术家和佩戴者提供一个牢不可破的终生记录的投资组合。 纹身应用程序已经有了一个可以直接向 IPFS 分享作品的特性.
- [Gorilla REPL viewer](https://github.com/keorn/ipfs-gorilla-repl) - . Gorilla 是一款丰富的 REPL 笔记本Demo 演示. [Demo](https://ipfs.io/ipfs/QmRNUauWDvZFkAp1Bw3kAode3jT8aH2vx7LYzbS7H6R3Mg/view.html?path=/ipfs/QmbRdyLXiFWrKc5hW1NbvpUxF9tLovWCPgiz4BDhjD9k3j)
- [Hardbin](https://github.com/jes/hardbin) - Hardbin 是一个加密的 pastebin，其中的解密密钥在 URL 片段中传递
- [hasteIPFS](https://ipfs.io/ipns/bin.ipfs.ovh/) - 基于 IPFS 的代码箱. (Read only for now)
- [HydrusNetwork](https://github.com/hydrusnetwork/hydrus) - 一个 booru 风格的媒体标签应用程序，具有众多功能，最近增加了基本的 ipfs 支持.
- [infura.io](https://infura.io) - 使用 API 和开发人员工具提供安全、可靠和可伸缩的访问到 ethereum 和 IPFS，帮助更容易地构建分布式的应用程序.

- [IPFS ID and Public Key QR Codes Demo](https://ipfs.io/ipfs/zdj7Whr8X3zah99TSuyPjENaERcBW9C7B36EaCb1DEZ5pbbL9/) - 一个演示应用程序，它使用windows.ipfs向您显示IPNS链接和公钥的QR码. [源码](https://github.com/ipfs-shipyard/demo-ipfs-id-qr-codes)
- [ipfs-md-wiki](https://github.com/daijiale/ipfs-md-wiki) - 建立基于 ipfs 和 markdown 的 wiki 系统.
- [ipfs-search](http://ipfs-search.com) - IPFS 上文件和目录的搜索引擎.
- [ipfs-share](https://github.com/rameshvarun/ipfs-share) - Pastebin / Image主机/文件共享应用程序
- [ipfs.ink](https://ipfs.ink) - 在 ipfs 中发表文章并加以删减. [源码](https://github.com/kpcyrd/ipfs.ink)
- [ipfs.pics](https://github.com/ipfspics/ipfspics-server) - 上载及分享照片.
- [IPFSBin](https://github.com/victorbjelkholm/ipfsbin) - Pastebin clone build.
- [IPFSStore](https://ipfsstore.it) - Pinning paid with Steem
- [killcord](https://killcord.io/) - 一个抗审查制度的死亡开关 [源码](https://github.com/nomasters/killcord)
- [markup.rocks](https://ipfs.io/ipfs/QmWPgJnUGLB1LPh9KMG9LEN4LVu5e17TwkEtcmTWdNn9V6/#/ipfs/QmfQ75DjAxYzxMP2hdm6o4wFwZS5t7uorEZ2pX9AKXEg2u) - 基于 pandoc 的标记编辑器 / 预览器 / 转换器，移植到 IPFS. [源码](https://github.com/davidar/markup.rocks)
- [NodeFort.io](https://www.nodefort.io) - 基于网络的 IPFS 节点托管服务.
- [OpenBazaar](https://www.openbazaar.org/) - 这个新版本(v2.0)是基于 IPFS 构建的，Openbazaar 商店现在可以供购买者访问，即使他们已经离线.
- [Orbit](https://orbit.chat) - IPFS 上分布式对等聊天应用. [源码](https://github.com/haadcode/orbit)
- [Origin Protocol](https://demo.originprotocol.com/) - 分布式共享经济市场，包括存储在 IPFS 上的图像、元数据和 erc725数据. [源码](https://github.com/OriginProtocol/demo-dapp)
- [Partyshare](https://partysha.re) -一个简单的文件共享应用程序.
- [Pathephone](https://pathephone.github.io) - 分布式音乐流媒体应用程序.
- [Peer Bandwidth Demo](https://ipfs.io/ipfs/QmVaVXbLdw4R5NqAiiQoTWtitxo5g7FS31PQmCLbH9p8Fu/) - 使用window.ipfs的演示应用程序，由IPFS Companion Web扩展提供，用于获取和绘制IPFS节点的带宽信息[源码](https://github.com/tableflip/ipfs-peer-bw-example)
- [Peer Map Demo](https://ipfs.io/ipfs/QmRPGCmLKH2dQmNiPRsiuYS9EhhJL1Gmkz5F75gKY1K4Bm/) - 使用window.ipfs的IPv4映射 [源码](https://github.com/tableflip/ipfs-peer-map-example)
- [Philes](https://philes.co) - 一个简单的基于浏览器的 IPFS 记事本应用程序. [源码](https://github.com/chrismatthieu/philes)
- [Pinata](https://pinata.cloud) - 通过 Pinata 的 REST API 和 IPFS 工具包构建和管理您的 dapp.
- [Playback](https://mafintosh.github.io/playback/) - IPFS 回放支持。 这允许在 IPFS 中将视频转换为 Chromecast.
- [PubSub Chat Demo](https://ipfs.io/ipfs/QmWZ3u5S7RjFXKfW6dSZhj7CozcvpqJxm48RYMmKkWcmNQ/) - 一个~76KB的演示聊天应用程序，它使用由IPFS Companion Web扩展提供的window.ipfs [源码](https://github.com/tableflip/ipfs-pubsub-chat-example)
- [PushToTalk](http://timothy.hobbs.cz/push-to-talk/index.html) - Push to Talk 允许您编辑音频文章，并通过 IPFS 发布.
- [qri](https://qri.io) - 在分布式网络上创建、协作和发现数据集. [源码](https://github.com/qri-io/qri)
- [TallyLab](https://tallylab.com/) - 本地优先，端到端加密日记应用程序捕获，分析和共享数据的任何和一切  .
- [Temporal](https://github.com/RTradeLtd/Temporal) - Temporal 是一个易于使用的 API 和平台，用于将 IPFS 和其他分布式 / 分散存储技术集成到企业应用中
- [Textile Photos](https://www.textile.photos) - Textile Photos是一个安全移动照片的数码钱包. [源码](https://github.com/textileio/textile-mobile)
- [ToDo List Demo](https://ipfs.io/ipfs/QmfFaH6dGibQ5JwEdsujeHBzsmHUsFRB5kU9P8nzPyzMv2/) - 使用windows.ipfs的ToDo List演示应用程序. [源码](https://github.com/ipfs-shipyard/demo-ipfs-todo)
- [ujo](http://ujomusic.com/) -  音乐家的区块链市场.
- [uport](https://uport.me/#home) - Uport 一个建立在以太坊区块链上的移动、自主身份和密钥管理系统.
- [xfce-screenshooter-ipfs-support](https://github.com/amar-laksh/xfce-screenshooter-ipfs-support) - 支持 IPFS 的屏幕截图分支

## 数据集

- [haveibeenpwnd.com 密码](https://ipfs.io/ipfs/QmSRBDMksX7c5dfheGsYDdWrLdve5hBvXDQm7Yrov7KMJv)  [源码](https://github.com/ipfs/archives/issues/157)
- [IETF RFC 档案](https://ipfs.io/ipfs/QmNvTjdqEPjZVWCvRWsFJA1vK7TTw1g9JP6we1WBJTRADM)  [源码](https://github.com/ipfs/archives/issues/18)
- [MDSConnect](https://ipfs.io/ipfs/QmcvfB6pAqUfTnuAK8zFKVxbdhopnBPveJrDcy1JAA7HX5)  [源码](https://github.com/ipfs/archives/issues/152)
- [旧互联网文件](https://ipfs.io/ipfs/QmbsZEvJE8EU51HCUHQg2aem9JNFmFHdva3tGVYutdCXHp)  [源码](https://github.com/ipfs/archives/issues/176)
- [每日总统简报](https://ipfs.io/ipfs/Qme6epvZDj3vzHcFKdF1nZhbixjw8Bn4imGcKnbUyBJL89)  [源码](https://github.com/ipfs/archives/issues/23)
- [万维网历史项目](https://ipfs.io/ipfs/QmRTSA1UFHSx3z7taNRwUVM8AjB2EQwKvyZu3BfJg9QRtZ)  [源码](https://github.com/ipfs/archives/issues/159)
- [XKCD](https://ipfs.io/ipfs/Qmb8wsGZNXt5VXZh1pEmYynjB6Euqpq3HYyeAdw2vScTkQ)  [源码](https://github.com/ipfs/archives/issues/21)
- [yarchive.net](https://ipfs.io/ipfs/QmdA5WkDNALetBn4iFeSepHjdLGJdxPBwZyY47ir1bZGAK)  [源码](https://github.com/ipfs/archives/issues/76)



参考自： https://github.com/ipfs/awesome-ipfs