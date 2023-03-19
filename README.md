# BlockChain 区块链 - 中文学习资料
------

# 1. 新手入门
- 北大肖臻老师的视频。B站可以直接搜到，讲的很好。主要分为两部分，一部分是比特币，一部分是以太坊的内容
- [课程笔记](https://github.com/gk0d/Demo6/blob/main/Books/%E5%8C%97%E5%A4%A7%E8%82%96%E8%87%BB%E7%AC%94%E8%AE%B0%E7%AC%94%E8%AE%B0.docx)

## 书籍
* [易懂的比特币工作机理详解](https://github.com/gk0d/Demo6/blob/main/Books/%E6%98%93%E6%87%82%E7%9A%84%E6%AF%94%E7%89%B9%E5%B8%81%E5%B7%A5%E4%BD%9C%E6%9C%BA%E7%90%86%E8%AF%A6%E8%A7%A3.pdf)
* [精通比特币](https://github.com/gk0d/Demo6/blob/main/Books/master_bitcoins.pdf)
* [区块链技术指南pdf](https://github.com/gk0d/Demo6/blob/main/Books/blockchain_guide.pdf)

## 官方文档
* [比特币白皮书：一种点对点的电子现金系统](https://github.com/gk0d/Demo6/blob/main/Books/%E6%AF%94%E7%89%B9%E5%B8%81%E7%99%BD%E7%9A%AE%E4%B9%A6-%E4%B8%AD%E6%96%87%E7%89%88.pdf)

------

# 2. 以太坊
还是看了北大肖臻老师的视频，接下来看白皮书与黄皮书，
>不要被各种数学问题所迷惑，如拜占庭问题，双花问题等。我的建议是一开始先抛开这些问题，对区块链的原理有一个基本的全局的了解，然后再回过头来思考这些问题。

## 官方文档
* [白皮书](https://ethereum.org/zh/whitepaper/)：概要性地介绍了以太坊
* [黄皮书](https://github.com/gk0d/Demo6/blob/main/Books/%E4%BB%A5%E5%A4%AA%E5%9D%8A%E9%BB%84%E7%9A%AE%E4%B9%A6%E4%B8%AD%E6%96%87%E7%89%88.pdf)：通过大量的定义和公式详细地描述了以太坊的技术实现。



# 3. 智能合约与DApp()
智能合约（smart-contract）实际上就是运行在以太坊网络中的一段代码。其最大的特点就是：自动执行、一旦部署就不可更改。智能合约这一特点，确保了写在合约里的全部功能，都能够按照逻辑执行。在以太坊部署智能合约之后，就意味着拥有了一段永不消失、自动执行的程度，随时能够与网络合约进行交互。智能合约类似于互联网里的TCP/IP协议，网络的传输运行完全按照协议标准执行.

DApp是Decentralized Application的缩写，译为:分散式的应用程序

## Solidity
Solidity 是一门面向合约的、为实现智能合约而创建的`高级编程语言`,是一种针对Ethereum虚拟机（EVM）设计的语言。

* [Remix](http://remix.ethereum.org/):以太坊官方推出的一个 Solidity 的在线集成开发环境。提供了文件浏览器，带高亮支持的代码编辑器，调试工具，甚至有编译功能.
* [Solidity 中文文档](https://learnblockchain.cn/docs/solidity/):Solidity语言非常详细的文档
* [cryptozombies](https://cryptozombies.io/):第三方的在线智能合约学习环境，目标是教会大家实现 DApp 游戏。这个网站的特点是自作非常精良，各种辅助学习材料丰富，并且是对 Solidity 小白友好的


# 4.优质社区
- [以太坊社区网络](https://www.ethereum.cn/)，他们的文章整理的不错，[文档](https://www.ethereum.cn/develop/)也很好。
- [以太坊基金会博客](https://ethereum.org/en/)，可以得到很多前沿信息。
- [登链社区](https://learnblockchain.cn/)，许多翻译的文章质量很高，并且有一些文档翻译。
- [以太坊知识库](https://learnblockchain.cn/eth/):虽然停更了，但之前的一些文章写的很好。


# 5.区块链安全
- [慢雾科技的安全技术探究](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzU4ODQ3NTM2OA==&action=getalbum&album_id=1378653641065857025&scene=173&from_msgid=2247494336&from_itemidx=1&count=3&nolastread=1#wechat_redirect): 里面会分享漏洞分析的报告。
- [合约漏洞赏金平台 immunefi](https://immunefi.com/)，在上面提交漏洞报告，不仅可以得到丰厚的回报，也会收获行业声誉.
- [EIP-1470 提出的漏洞分类](https://swcregistry.io/)
- [CTF 竞赛中合约安全方面的题目](https://github.com/blockthreat/blocksec-ctfs)

## 安全审计
- [Mythril](https://github.com/ConsenSys/mythril) 是 EVM 字节码的安全分析工具。它使用符号执行、SMT 解决和污点分析来检测各种安全漏洞
- [Slither](https://github.com/crytic/slither) 是一个用 Python 3 编写的 Solidity 静态分析框架
- [Manticore](https://github.com/trailofbits/manticore) 是用于分析智能合约和二进制文件的符号执行工具
- [Echidna](https://github.com/crytic/echidna) 是一个 Haskell 程序，旨在对以太坊智能合约进行模糊测试/基于属性的测试。



