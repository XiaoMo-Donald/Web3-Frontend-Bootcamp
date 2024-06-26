# Task2 Blockchain Basic

本任务分为简答题、分析题和选择题，以此为模板，在下方填写你的答案即可。

选择题，请在你选中的项目中，将 `[ ]` 改为 `[x]` 即可

## [单选题] 如果你莫名奇妙收到了一个 NFT，那么

- [ ] 天上掉米，我应该马上点开他的链接
- [x] 这可能是在对我进行诈骗！

## [单选题] 群里大哥给我发的网站，说能赚大米，我应该

- [ ] 赶紧冲啊，待会米被人抢了
- [x] 谨慎判断，不在不信任的网站链接钱包

## [单选题] 下列说法正确的是

- [x] 一个私钥对应一个地址
- [ ] 一个私钥对应多个地址
- [ ] 多个私钥对应一个地址
- [x] 多个私钥对应多个地址

## [单选题] 下列哪个是以太坊虚拟机的简称

- [ ] CLR
- [x] EVM
- [ ] JVM

## [单选题] 以下哪个是以太坊上正确的地址格式？

- [ ] 1A4BHoT2sXFuHsyL6bnTcD1m6AP9C5uyT1
- [ ] TEEuMMSc6zPJD36gfjBAR2GmqT6Tu1Rcut
- [ ] 0x997fd71a4cf5d214009619808176b947aec122890a7fcee02e78e329596c94ba
- [x] 0xf39Fd6e51aad88F6F4ce6aB8827279cffFb92266

## [多选题] 有一天某个大哥说要按市场价的 80% 出油给你，有可能

- [x] 他在洗米
- [ ] 他良心发现
- [x] 要给我黒米
- [x] 给我下套呢

## [多选题] 以下哪些是以太坊的二层扩容方案？

- [ ] Lightning Network（闪电网络）
- [x] Optimsitic Rollup
- [x] Zk Rollup

## [简答题] 简述区块链的网络结构

```
区块链的网络结构是一种分布式的、去中心化的数据库系统，其核心特征包括以下几个方面：

分布式节点：
区块链网络由多个节点组成，这些节点分布在全球各地，每个节点都保存着完整的区块链数据副本。节点之间通过点对点（P2P）网络进行通信和数据同步。

去中心化：
在区块链网络中，没有中央控制机构。所有节点都具有相同的权限，任何节点都可以参与数据的验证和记录。这种结构提高了系统的容错性和安全性。

区块链数据结构：
区块链由一系列按时间顺序连接的区块组成，每个区块包含多个交易记录。每个区块通过加密哈希与前一个区块相连，形成一条不可篡改的链条。

共识机制：
为了确保区块链网络中所有节点的数据一致性，区块链采用了各种共识机制，如工作量证明（PoW）、权益证明（PoS）等。共识机制确保了只有经过验证的交易才能被添加到区块链中。

加密技术：
区块链使用公钥加密和私钥加密技术来确保交易的安全性和隐私性。每个用户都有一对公私钥，用于签名和验证交易。

智能合约：
一些区块链网络（如以太坊）支持智能合约，这是一种自动执行的代码，可以在满足特定条件时自动执行合同条款。

这种网络结构使得区块链具有高度的安全性、透明性和不可篡改性，适用于各种需要高信任度的数据存储和传输场景。
```

## [简答题] 智能合约是什么，有何作用？

```
智能合约是一种运行在区块链上的自动化协议，它能够在满足预定条件时自动执行合同条款。智能合约的代码和数据被存储在区块链上，因此具有透明性、不可篡改性和去中心化的特点。

智能合约的作用：
自动化执行：
智能合约可以在满足特定条件时自动执行预定义的操作，无需人工干预。这大大减少了人为错误和操作成本。

去中心化：
智能合约运行在去中心化的区块链网络上，没有中央控制机构。这意味着合约的执行不依赖于任何单一实体，从而提高了系统的安全性和可靠性。

透明性：
智能合约的代码和执行记录都存储在区块链上，任何人都可以查看。这种透明性有助于提高信任度和减少欺诈行为。

不可篡改性：
一旦智能合约部署到区块链上，其代码和数据就不能被篡改。这确保了合同条款的执行是公正和准确的。

成本效益：
由于智能合约自动执行并且不需要中介机构，交易成本和时间都可以大大减少
```

## [简答题] 怎么理解大家常说的 `EVM` 这个词汇？

```
EVM 是 Ethereum Virtual Machine，以太坊虚拟机的缩写。EVM 是以太坊区块链的核心组件之一，它负责执行智能合约和处理以太坊网络上的交易。EVM 提供了一个运行环境，使得开发者可以编写和部署智能合约。EVM 将智能合约的代码转换为机器可以理解的字节码，并在以太坊网络上执行这些代码。
```

## [分析题] 你对去中心化的理解

```
去中心化（Decentralization）是指将权力、控制和决策从一个中央权威或单一实体转移到多个分布式节点或参与者的过程。在去中心化系统中，系统的运行和管理由多个独立的节点共同参与和协作完成。以下是对去中心化的详细理解：

1. 去中心化的基本概念
权力分散：在去中心化系统中，权力和控制不集中在一个单一实体手中，而是分散在多个节点或参与者之间。
共识机制：去中心化系统通常依赖共识机制来达成一致意见。共识机制确保系统的所有参与者对数据和操作的有效性达成共识。
透明性：去中心化系统通常具有高透明性，因为所有参与者都可以访问和验证系统中的数据和操作。
2. 去中心化的优势
抗审查性：由于没有单一的控制中心，去中心化系统更难被审查或关闭。
安全性：去中心化系统通过分布式节点来分散风险，即使部分节点受到攻击，系统仍能继续运行。
信任：去中心化系统减少了对单一实体的信任需求，通过透明和公开的操作建立信任。
弹性：去中心化系统通常具有更高的弹性，因为它们不依赖于单一节点或服务器。
3. 去中心化的应用
区块链和加密货币：区块链技术是去中心化的典型应用。比特币和以太坊等加密货币通过去中心化网络实现了点对点的价值传输和智能合约执行。
去中心化金融（DeFi）：DeFi 应用利用去中心化技术提供金融服务，如借贷、交易和保险，而无需传统金融机构的参与。
去中心化自治组织（DAO）：DAO 是一种基于区块链的组织形式，通过智能合约和投票机制实现去中心化的治理和决策。
去中心化应用（DApps）：DApps 是运行在去中心化网络上的应用程序，用户可以直接与应用交互，而无需中介。
4. 去中心化的挑战
可扩展性：去中心化系统通常面临可扩展性问题，因为分布式节点的协调和共识过程可能较慢。
治理：去中心化系统的治理可能复杂，需要设计合理的机制来确保公平和有效的决策。
用户体验：由于技术复杂性，去中心化系统的用户体验可能不如集中化系统直观和便捷。
安全性：虽然去中心化系统具有一定的安全优势，但仍然面临智能合约漏洞、共识攻击等安全挑战。
5. 去中心化的未来
随着技术的发展，去中心化系统有望在更多领域得到应用，如供应链管理、社交媒体、数据存储等。去中心化技术正在不断演进，旨在解决当前的挑战并提供更高效、更公平的解决方案。

总的来说，去中心化是一种通过分布式网络和共识机制实现权力和控制分散的系统架构。它在提高安全性、透明性和抗审查性方面具有显著优势，但也面临可扩展性和治理等挑战。
```

## [分析题] 比较区块链与传统数据库，你的看法？

```
区块链和传统数据库在架构、功能、应用场景等方面有显著的差异。以下是对二者的详细比较：

1. 架构和设计
区块链：

分布式账本：区块链是一个分布式账本，数据分布存储在多个节点上，每个节点都有完整的数据副本。
去中心化：没有单一的控制中心，所有节点通过共识机制共同维护数据的完整性和一致性。
不可篡改：一旦数据被写入区块链，就几乎无法篡改，确保了数据的不可变性和透明性。
链式结构：数据以区块的形式存储，每个区块包含前一个区块的哈希值，形成链式结构。
传统数据库：

集中式存储：数据通常存储在一个或多个集中式服务器上，由一个中央实体进行管理和维护。
可变性：数据可以被修改、删除，适用于需要频繁更新和修改的数据场景。
关系型和非关系型：传统数据库包括关系型数据库（如MySQL、PostgreSQL）和非关系型数据库（如MongoDB、Cassandra）。
高效查询：设计上注重高效的数据查询和处理，支持复杂的查询操作和事务处理。
2. 数据一致性和安全性
区块链：

共识机制：通过共识机制（如PoW、PoS）确保数据一致性，防止双花问题（double-spending）。
加密安全：数据通过加密技术保护，交易和数据的完整性和真实性通过数字签名和哈希算法验证。
透明性：所有节点都可以访问和验证区块链上的数据，确保透明性。
传统数据库：

事务处理：通过ACID（原子性、一致性、隔离性、持久性）特性保证数据一致性和可靠性。
访问控制：通过用户权限和访问控制机制保护数据安全，防止未经授权的访问和操作。
备份和恢复：通过定期备份和灾难恢复机制确保数据的安全和可用性。
3. 性能和扩展性
区块链：

性能：由于分布式共识机制和数据冗余，区块链的性能（如交易处理速度）通常较低，难以处理高频率的交易。
扩展性：扩展性是区块链面临的主要挑战，解决方案包括分片（sharding）、侧链（sidechain）等。
传统数据库：

性能：设计上注重高性能的数据处理和查询，适用于高频率的读写操作。
扩展性：通过垂直扩展（增加硬件资源）和水平扩展（增加更多服务器）来提升性能和容量。
4. 应用场景
区块链：

加密货币：如比特币、以太坊，用于点对点的价值传输和支付。
智能合约：自动化执行合约条款，如以太坊上的智能合约。
去中心化金融（DeFi）：提供金融服务，如借贷、交易、保险等。
供应链管理：追踪产品从生产到交付的全过程，确保透明和可追溯性。
传统数据库：

企业应用：如ERP、CRM系统，用于管理企业资源和客户关系。
电子商务：存储和管理商品信息、订单、用户数据等。
社交媒体：管理用户数据、帖子、评论等。
数据分析：用于大数据分析、商业智能（BI）等领域。
```

## 操作题

安装一个 WEB3 钱包，创建账户后与 [openbuild.xyz](https://openbuild.xyz/profile) 进行绑定，截图后文件命名为 `./bind-wallet.jpg`.
