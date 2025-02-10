# Solidity 高级程序设计

**前置说明**：

这个教程的目标读者是那些已经熟悉 Solidity 语言基本用法的人，他们可能已经编写过一些简单的智能合约，并对 Solidity 的核心概念和语法有一定的了解。如果您已经掌握了 Solidity 的基本用法，这个教程可以帮助您填补一些知识的空白，并深入学习更高级的概念和技术。

对于更好地阅读和理解这个教程，确实需要具备一定的 Solidity 基础知识，并且最好具备其他语言的生产级项目编码水平。

对于完全零基础的 Solidity 小白来说，这个教程可能并不适合作为他们初次接触。

如果您是一个初学者，我建议您首先学习 Solidity 的基础知识。您可以通过阅读 Solidity 的官方文档和教程来入门，掌握 Solidity 的基本语法、数据类型、控制流程等。一旦您对 Solidity 有了一定的了解，您可以尝试编写简单的智能合约，以加深对 Solidity 的理解。

在学习 Solidity 的过程中，如果您遇到任何问题，都可以随时向我提问。我将尽力帮助您理解和解决问题。


❌❌❌ 注意：

这个前置条件非常重要，对于没有编程基础的人来说，阅读这个教程可能会非常困难。如果您没有掌握 Solidity 的基本用法或其他编程语言的经验，确实建议您先学习编程的基础知识和其他语言，然后再尝试深入学习 Solidity。

如果您在学习 Solidity 的过程中遇到困难，可以随时向我提问。我会尽力为您提供帮助和解答。同时，使用搜索引擎和参考其他教程和资源也是一个很好的学习策略，因为这样可以获取更多的知识和解决问题的方法。

另外，关于Solidity学习资源的地址，一下是一些常用的学习资源，供大家参考：
- [Solidity 官方文档](https://blog.soliditylang.org/)
- [Solidity Github存储库](https://github.com/ethereum/solidity)
- [Solidity 在线编译器](https://remix.ethereum.org/)

<!-- ## 关于作者&加入我们[![Twitter](https://img.shields.io/badge/-1DA1F2?style=flat-square&logo=twitter&logoColor=white)](https://twitter.com/anbang_account) [![Discord](https://img.shields.io/badge/-7289DA?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/AZmEtpmAjx) -->

**朱安邦**

一位热衷于区块链技术和 Solidity 的开发者。

<!-- 他具有丰富的经验和知识，并致力于推广和教育 Solidity 的使用。他的目标是帮助更多的人学习和了解 Solidity，并在区块链领域做出贡献。 -->


您可以通过以下方式与作者互动和获取更多信息：

<!-- - 推特：
[![Twitter](https://img.shields.io/badge/@anbang_account-1DA1F2?style=flat-square&logo=twitter&logoColor=white)](https://twitter.com/anbang_account) （欢迎关注）
- 交流群：[![Discord](https://img.shields.io/badge/Solidity%20智能合约交流群-7289DA?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/AZmEtpmAjx) （Discord） -->


## 运行配置 & 环境说明
**运行环境**：

为了方便演示，本教程内所有的操作，均在 [Solidity 在线编译器 Remix](https://remix.ethereum.org/) 中进行，它可以直观快捷的做合约部署+测试+生成界面。

学习的时候建议使用 Solidity 最新版本进行编码，最新版本可以在官方博客 [blog.soliditylang.org](https://blog.soliditylang.org/) 查看。

**额外说明**：

本教程的所有知识点都不会拿别的语言进行类比。很多写作者写 solidity 教程的时候，喜欢在介绍某个知识点时，拿自己之前熟悉的语言和 solidity 类比介绍（比如 C++，Python，Java，Javascript 等），初心是让读者可以更容易理解；但是事与愿违，很多时候读者可能并不了解写作者熟悉的那门语言，导致不举例还好，对比举例更迷糊了。学习编程是一件很严肃的事情，本教程尽量避免无聊的调侃，类比和啰嗦的废话。

<!-- ## 感想

为了促进更多人的参与和了解，《Solidity 高级程序设计》教程力争成为中文区域领先的教程之一。为此，我为教程准备了一系列配套资料，以便读者更好地学习和掌握相关内容。

- Github 源文件：开放，让读者最低成本的参与优化和修复
- 在线文档：方便随时阅读（会墙内+墙外两套文档作为配套）
- PDF 文件：方便本地断网浏览
- 实体书籍：方便有读书习惯的人阅读。


如果你喜欢这个项目，请给它点一个[![GitHub stars](https://img.shields.io/github/stars/anbang/professional-solidity.svg?style=social)](https://github.com/你的GitHub用户名/你的项目仓库名)（GitHub上的点赞按钮）。 -->

## 贡献

我们欢迎并鼓励您对所有文档、源代码以及相关视频的开放与免费访问。此外，我们还提供了配套的PDF文件，同样也是免费提供的。我们欢迎您在GitHub仓库上提交您的改动，以帮助我们不断优化内容。如果您对参与教程的修改和改进感兴趣，修改GitHub源文件是最简单的方式。


## 在线阅读

- **文字版在线阅读**:
  - <a target="_blank" rel="noopener noreferrer" href="https://professional-solidity.readthedocs.io/zh_CN/latest/">Read The Docs</a>
- **视频版**:
  - [在线视频观看: Youtube](https://www.youtube.com/watch?v=ao5nkAgx7kU&list=PLdXBX6Eqe4Net43OWIZychHW0n6CX_8Ih)
  - [在线视频观看: Bilibili](https://www.bilibili.com/video/BV1HR4y197Ag)
<!-- 
## TODO

下面是给这本书做的 TODO List

1. ✅ 最迟不晚于 2022 年 11 月提供前 3 章的内容用来做市场测试，如果有必要的话，提供配套的视频版
2. ✅ 最迟不晚于 2023 年 1 月提供 V0.0.1 版本，并在 V0.0.1 版本完成初步架构
3. ❌ 最迟不晚于 2023 年 3 月提供 V0.0.2 版本，并在 V0.0.2 开始提供完整的 PDF 版电子书籍
4. ❌ 最迟不晚于 2023 年 6 月提供 V0.0.3 版本，并在 V0.0.3 开始将 PDF 电子书籍印刷 30 本供自己和身边的朋友阅读和矫正。
5. ❌ 最迟不晚于 2023 年 9 月提供 V0.0.4 版本，并在 V0.0.4 印刷 100 本免费提供给网络上的陌生人阅读和矫正。
6. ❌ 如果一切顺利的话，联系出版社给印刷出来。
7. ❌ 重新录制完整的视频配套教程

7 个步骤，目前完成了 2 个。一切都按照计划进行中。

最开始写了前面 3 章内容，并在 2022 年 10 月下旬录制了配套视频教程，并分享在 Bilibili 上，有赞的有吐槽的；但是后台数据上来看这类资料在 Solidity 这个垂直语言内还是很受欢迎的。目前在 B 站搜索常见的 Solidity 关键字，我分享的视频教程几乎都是系统默认推荐的第 1 名。总播放量也在 12 月份进了前 10。并在 2022 年 12 月下旬完成了 V0.0.1 版本内容，初步完成了这本书的架构。 -->

## 目录

第一部分：语言基础

- [01.初识](./docs/source/01.hello.md)
  - [1️⃣ 区块链基础](./docs/source/01.hello.md#1%EF%B8%8F⃣-区块链基础)
  - [2️⃣ Hello World](./docs/source/01.hello.md#2%EF%B8%8F⃣-hello-world)
  - [3️⃣ 合约代码中的三种注释](./docs/source/01.hello.md#3%EF%B8%8F⃣-合约代码中的三种注释)
  - [4️⃣ 合约结构介绍](./docs/source/01.hello.md#4%EF%B8%8F⃣-合约结构介绍)
  - [5️⃣ 全局的以太币单位](./docs/source/01.hello.md#5%EF%B8%8F⃣-全局的以太币单位)
  - [6️⃣ 接收 ETH](./docs/source/01.hello.md#6%EF%B8%8F⃣-接收-eth)
  - [7️⃣ selfdestruct:合约自毁](./docs/source/01.hello.md#7%EF%B8%8F⃣-selfdestruct合约自毁)
  - [🆗 实战 1: 同志们好](./docs/source/01.hello.md#-实战-1-同志们好)
  - [🆗 实战 2: 存钱罐合约](./docs/source/01.hello.md#-实战-2-存钱罐合约)
  - [🆗 实战 3: WETH 合约](./docs/source/01.hello.md#-实战-3-weth-合约)
  - [#️⃣ 问答题](./docs/source/01.hello.md#%EF%B8%8F⃣-问答题)
- [02.数据](./docs/source/02.type-of-data.md)
  - [1️⃣ 数据与变量](./docs/source/02.type-of-data.md#1%EF%B8%8F⃣-数据与变量)
  - [2️⃣ 两种类型的数据](./docs/source/02.type-of-data.md#2%EF%B8%8F⃣-两种类型的数据)
  - [3️⃣ 值类型](./docs/source/02.type-of-data.md#3%EF%B8%8F⃣-值类型)
  - [4️⃣ 值类型:地址类型](./docs/source/02.type-of-data.md#4%EF%B8%8F⃣-值类型地址类型)
  - [5️⃣ 值类型:合约类型](./docs/source/02.type-of-data.md#5%EF%B8%8F⃣-值类型合约类型)
  - [6️⃣ 引用类型的额外注解:数据位置](./docs/source/02.type-of-data.md#6%EF%B8%8F⃣-引用类型的额外注解数据位置)
  - [7️⃣ 引用类型](./docs/source/02.type-of-data.md#7%EF%B8%8F⃣-引用类型)
  - [8️⃣ 类型转换](./docs/source/02.type-of-data.md#8%EF%B8%8F⃣-类型转换)
  - [9️⃣ 字面常量与基本类型的转换](./docs/source/02.type-of-data.md#9%EF%B8%8F⃣-字面常量与基本类型的转换)
  - [🆗 实战 1: Todo List](./docs/source/02.type-of-data.md#-实战-1-todo-list)
  - [🆗 实战 2: 众筹合约](./docs/source/02.type-of-data.md#-实战-2-众筹合约)
  - [🆗 实战 3: 同志们好增加提示](./docs/source/02.type-of-data.md#-实战-3-同志们好增加提示)
  - [🆗 实战 4: ETH 钱包](./docs/source/02.type-of-data.md#-实战-4-eth-钱包)
  - [🆗 实战 5: 多签钱包](./docs/source/02.type-of-data.md#-实战-5-多签钱包)
  - [#️⃣ 问答题](./docs/source/02.type-of-data.md#%EF%B8%8F⃣-问答题)
- [03.变量](./docs/source/03.variable.md)
  - [1️⃣ 变量基础知识](./docs/source/03.variable.md#1%EF%B8%8F⃣-变量基础知识)
  - [2️⃣ Constant (恒) 常量](./docs/source/03.variable.md#2%EF%B8%8F⃣-constant-常量)
  - [3️⃣ Immutable 不可变量](./docs/source/03.variable.md#3%EF%B8%8F⃣-immutable-不可变量)
  - [4️⃣ 变量名的命名规则](./docs/source/03.variable.md#4%EF%B8%8F⃣-变量名的命名规则)
  - [5️⃣ 变量的可见性](./docs/source/03.variable.md#5%EF%B8%8F⃣-变量的可见性)
  - [6️⃣ 全局：时间单位](./docs/source/03.variable.md#6%EF%B8%8F⃣-全局时间单位)
  - [7️⃣ 全局：区块和交易属性](./docs/source/03.variable.md#7%EF%B8%8F⃣-全局区块和交易属性)
  - [#️⃣ 问答题](./docs/source/03.variable.md#%EF%B8%8F⃣-问答题)
- [04.函数](./docs/source/04.function.md)
  - [1️⃣ 函数的定义](./docs/source/04.function.md#1%EF%B8%8F⃣-函数的定义)
  - [2️⃣ 函数的调用](./docs/source/04.function.md#2%EF%B8%8F⃣-函数的调用)
  - [3️⃣ 构造函数](./docs/source/04.function.md#3%EF%B8%8F⃣-构造函数)
  - [4️⃣ visibility:可见性](./docs/source/04.function.md#4%EF%B8%8F⃣-visibility可见性)
  - [5️⃣ mutability:状态可变性](./docs/source/04.function.md#5%EF%B8%8F⃣-mutability状态可变性)
  - [6️⃣ 函数的返回值 returns/return](./docs/source/04.function.md#6%EF%B8%8F⃣-函数的返回值-returnsreturn)
  - [7️⃣ 函数的签名/函数标识符](./docs/source/04.function.md#7%EF%B8%8F⃣-函数的签名函数标识符)
  - [8️⃣ 函数的重载](./docs/source/04.function.md#8%EF%B8%8F⃣-函数的重载)
  - [9️⃣ modifier:函数修改器](./docs/source/04.function.md#9%EF%B8%8F⃣-modifier函数修改器)
  - [🔟 全局：数学和密码学函数](./docs/source/04.function.md#-全局数学和密码学函数)
  - [1️⃣ 全局：ABI 编码及解码函数](./docs/source/04.function.md#1%EF%B8%8F⃣-全局abi-编码及解码函数)
  - [2️⃣ 补充:函数赋值给变量 & 函数作为参数 & 函数中返回函数](./docs/source/04.function.md#2%EF%B8%8F⃣-补充函数赋值给变量--函数作为参数--函数中返回函数)
  - [🆗 实战应用](./docs/source/04.function.md#-实战应用)
  - [#️⃣ 问答题](./docs/source/04.function.md#%EF%B8%8F⃣-问答题)
- [05.运算操作符](./docs/source/05.operator.md)
  - [1️⃣ 算术运算符](./docs/source/05.operator.md#1%EF%B8%8F⃣-算术运算符)
  - [2️⃣ 关系运算符](./docs/source/05.operator.md#2%EF%B8%8F⃣-关系运算符)
  - [3️⃣ 逻辑运算符](./docs/source/05.operator.md#3%EF%B8%8F⃣-逻辑运算符)
  - [4️⃣ 三元运算符](./docs/source/05.operator.md#4%EF%B8%8F⃣-三元运算符)
  - [5️⃣ 位运算符](./docs/source/05.operator.md#5%EF%B8%8F⃣-位运算符)
  - [6️⃣ delete (删除)](./docs/source/05.operator.md#6%EF%B8%8F⃣-delete)
  - [7️⃣ 操作符的优先级](./docs/source/05.operator.md#7%EF%B8%8F⃣-操作符的优先级)
  - [8️⃣ 不同数据类型的总结](./docs/source/05.operator.md#8%EF%B8%8F⃣-不同数据类型的总结)
  - [#️⃣ 问答题](./docs/source/05.operator.md#%EF%B8%8F⃣-问答题)
- [06.错误处理](./docs/source/06.error.md)
  - [1️⃣ require (需要)](./docs/source/06.error.md#1%EF%B8%8F⃣-require)
  - [2️⃣ assert (断言)](./docs/source/06.error.md#2%EF%B8%8F⃣-assert)
  - [3️⃣ revert](./docs/source/06.error.md#3%EF%B8%8F⃣-revert)
  - [4️⃣ 三种方式的总结](./docs/source/06.error.md#4%EF%B8%8F⃣-三种方式的总结)
  - [5️⃣ 自定义 Error (误差)](./docs/source/06.error.md#5%EF%B8%8F⃣-自定义-error)
  - [6️⃣ Natspec Error (误差)](./docs/source/06.error.md#6%EF%B8%8F⃣-natspec-error)
  - [7️⃣ try catch](./docs/source/06.error.md#7%EF%B8%8F⃣-try-catch)
- [07.流程控制](./docs/source/07.control-flow.md)
  - [1️⃣ if else](./docs/source/07.control-flow.md#1%EF%B8%8F⃣-if-else)
  - [2️⃣ 三元运算符](./docs/source/07.control-flow.md#2%EF%B8%8F⃣-三元运算符)
- [08.循环与迭代](./docs/source/08.loops-and-iteration.md)
  - [1️⃣ for 语句](./docs/source/08.loops-and-iteration.md#1%EF%B8%8F⃣-for-语句)
  - [2️⃣ while 语句](./docs/source/08.loops-and-iteration.md#2%EF%B8%8F⃣-while-语句)
  - [3️⃣ do…while](./docs/source/08.loops-and-iteration.md#3%EF%B8%8F⃣-dowhile)
- [09.事件](./docs/source/09.event.md)
  - [1️⃣ Event (事件) 语法](./docs/source/09.event.md#1%EF%B8%8F⃣-event-语法)
  - [2️⃣ 四种事件定义方式](./docs/source/09.event.md#2%EF%B8%8F⃣-四种事件定义方式)
  - [3️⃣ indexed (指数) 的作用](./docs/source/09.event.md#3%EF%B8%8F⃣-indexed-的作用)
  - [4️⃣ log (日志) 的使用](./docs/source/09.event.md#4%EF%B8%8F⃣-log-的使用)
  - [5️⃣ Log (日志) 重载](./docs/source/09.event.md#5%EF%B8%8F⃣-log-重载)
  - [🆗 实战: 众筹合约](./docs/source/09.event.md#-实战-众筹合约)
- [10.合约继承](./docs/source/10.inheritance.md)
  - [1️⃣ 使用 `is` 实现继承](./docs/source/10.inheritance.md#1%EF%B8%8F⃣-使用-is-实现继承)
  - [2️⃣ 子类可以继承父类哪些数据？](./docs/source/10.inheritance.md#2%EF%B8%8F⃣-子类可以继承父类哪些数据)
  - [3️⃣ 多重继承中的重名](./docs/source/10.inheritance.md#3%EF%B8%8F⃣-多重继承中的重名)
  - [4️⃣ 重写函数](./docs/source/10.inheritance.md#4%EF%B8%8F⃣-重写函数)
  - [5️⃣ 多级继承的代码书写顺序（线性化）](./docs/source/10.inheritance.md#5%EF%B8%8F⃣-多级继承的代码书写顺序线性化)
  - [6️⃣ 继承中两种构造函数传参方式](./docs/source/10.inheritance.md#6%EF%B8%8F⃣-继承中两种构造函数传参方式)
  - [7️⃣ 继承中构造函数的执行顺序](./docs/source/10.inheritance.md#7%EF%B8%8F⃣-继承中构造函数的执行顺序)
  - [8️⃣ 两种子合约调用父合约的方法](./docs/source/10.inheritance.md#8%EF%B8%8F⃣-两种子合约调用父合约的方法)
  - [9️⃣ 多重继承合约不要使用 supper](./docs/source/10.inheritance.md#9%EF%B8%8F⃣-多重继承合约不要使用-supper)
  - [🆗 实战应用](./docs/source/10.inheritance.md#-实战应用)
  - [#️⃣ 问答题](./docs/source/10.inheritance.md#%EF%B8%8F⃣-问答题)
- [11.合约调用合约](./docs/source/11.call-other.md)
  - [1️⃣ 调用内部合约](./docs/source/11.call-other.md#1%EF%B8%8F⃣-调用内部合约)
  - [2️⃣ 调用外部合约](./docs/source/11.call-other.md#2%EF%B8%8F⃣-调用外部合约)
  - [3️⃣ MultiCall/多次调用](./docs/source/11.call-other.md#3%EF%B8%8F⃣-multicall多次调用)
  - [4️⃣ MultiDelegatecall / 多次委托调用](./docs/source/11.call-other.md#4%EF%B8%8F⃣-multidelegatecall--多次委托调用)
  - [🆗 实战应用](./docs/source/11.call-other.md#-实战应用)
  - [#️⃣ 问答题](./docs/source/11.call-other.md#%EF%B8%8F⃣-问答题)
- [12.合约部署合约](./docs/source/12.deploy.md)
  - [1️⃣ 通过 `new` 创建合约 / `create`](./docs/source/12.deploy.md#1%EF%B8%8F⃣-通过-new-创建合约--create)
  - [2️⃣ 通过 `salt` 创建合约 / `create2`](./docs/source/12.deploy.md#2%EF%B8%8F⃣-通过-salt-创建合约--create2)
  - [3️⃣ 用 assembly (装配) 做 create (创建)](./docs/source/12.deploy.md#3%EF%B8%8F⃣-用-assembly-做-create)
  - [4️⃣ 用 assembly (装配) 做 create2](./docs/source/12.deploy.md#4%EF%B8%8F⃣-用-assembly-做-create2)
  - [5️⃣ 创建合约的扩展](./docs/source/12.deploy.md#5%EF%B8%8F⃣-创建合约的扩展)
  - [#️⃣ 问答题](./docs/source/12.deploy.md#%EF%B8%8F⃣-问答题)
- [13.interface:接口](./docs/source/13.interface.md)
  - [1️⃣ 限制](./docs/source/13.interface.md#1%EF%B8%8F⃣-限制)
  - [2️⃣ 定义和使用](./docs/source/13.interface.md#2%EF%B8%8F⃣-定义和使用)
  - [3️⃣ 全局属性 `type(I).interfaceId`](./docs/source/13.interface.md#3%EF%B8%8F⃣-全局属性-typeiinterfaceid)
  - [4️⃣ ERC20 标准](./docs/source/13.interface.md#4%EF%B8%8F⃣-erc20-标准)
  - [5️⃣ ERC721 标准](./docs/source/13.interface.md#5%EF%B8%8F⃣-erc721-标准)
  - [6️⃣ ERC1155 标准](./docs/source/13.interface.md#6%EF%B8%8F⃣-erc1155-标准)
  - [7️⃣ ERC3525 标准](./docs/source/13.interface.md#7%EF%B8%8F⃣-erc3525-标准)
  - [8️⃣ 四种代币标准的对比](./docs/source/13.interface.md#8%EF%B8%8F⃣-四种代币标准的对比)
  - [🆗 实战:荷兰拍卖](./docs/source/13.interface.md#-实战荷兰拍卖)
  - [🆗 实战:英式拍卖](./docs/source/13.interface.md#-实战英式拍卖)
  - [#️⃣ 问答题](./docs/source/13.interface.md#%EF%B8%8F⃣-问答题)
- [14.Library:库](./docs/source/14.library.md)
  - [1️⃣ 库合约与普通智能合约区别](./docs/source/14.library.md#1%EF%B8%8F⃣-库合约与普通智能合约区别)
  - [2️⃣ 直接调用库合约方法](./docs/source/14.library.md#2%EF%B8%8F⃣-直接调用库合约方法)
  - [3️⃣ `using...for...` 使用库合约](./docs/source/14.library.md#3%EF%B8%8F⃣-usingfor-使用库合约)
  - [4️⃣ 直接调用 和 using (使用) for 对比](./docs/source/14.library.md#4%EF%B8%8F⃣-直接调用-和-using-for-对比)
  - [5️⃣ 销毁合约库](./docs/source/14.library.md#5%EF%B8%8F⃣-销毁合约库)
  - [6️⃣ 扩展:库的调用保护](./docs/source/14.library.md#6%EF%B8%8F⃣-扩展库的调用保护)
  - [🆗 实战应用](./docs/source/14.library.md#-实战应用)
  - [#️⃣ 问答题](./docs/source/14.library.md#%EF%B8%8F⃣-问答题)
- [15.算法](./docs/source/15.algorithm.md)
  - [1️⃣ 插入排序](./docs/source/15.algorithm.md#1%EF%B8%8F⃣-插入排序)
  - [2️⃣ 冒泡排序](./docs/source/15.algorithm.md#2%EF%B8%8F⃣-冒泡排序)
  - [🆗 实战应用](./docs/source/15.algorithm.md#-实战应用)
  - [#️⃣ 问答题](./docs/source/15.algorithm.md#%EF%B8%8F⃣-问答题)
- [16.Assembly (装配) :内联汇编](./docs/source/16.assembly.md)
  - [1️⃣ 基本格式](./docs/source/16.assembly.md#1%EF%B8%8F⃣-基本格式)
  - [2️⃣ 语言基础](./docs/source/16.assembly.md#2%EF%B8%8F⃣-语言基础)
  - [3️⃣ 条件判断](./docs/source/16.assembly.md#3%EF%B8%8F⃣-条件判断)
  - [4️⃣ for 循环](./docs/source/16.assembly.md#4%EF%B8%8F⃣-for-循环)
  - [5️⃣ 函数的定义和使用](./docs/source/16.assembly.md#5%EF%B8%8F⃣-函数的定义和使用)
  - [6️⃣ EVM 内置函数/内置操作码](./docs/source/16.assembly.md#6%EF%B8%8F⃣-evm-内置函数内置操作码)
  - [🆗 实战应用](./docs/source/16.assembly.md#-实战应用)
  - [#️⃣ 问答题](./docs/source/16.assembly.md#%EF%B8%8F⃣-问答题)
- [17.metadata:元数据](./docs/source/17.metadata.md)
  - [1️⃣ metadata 包含信息](./docs/source/17.metadata.md#1%EF%B8%8F⃣-metadata-包含信息)
  - [2️⃣ 字节码中元数据哈希的编码](./docs/source/17.metadata.md#2%EF%B8%8F⃣-字节码中元数据哈希的编码)
  - [3️⃣ 自动化接口生成和 natspec 使用](./docs/source/17.metadata.md#3%EF%B8%8F⃣-自动化接口生成和-natspec-使用)
  - [4️⃣ 源代码如何验证？](./docs/source/17.metadata.md#4%EF%B8%8F⃣-源代码如何验证)
  - [🆗 实战应用](./docs/source/17.metadata.md#-实战应用)
  - [#️⃣ 问答题](./docs/source/17.metadata.md#%EF%B8%8F⃣-问答题)
- [18.ABI 编码](./docs/source/18.abi.md)
  - [1️⃣ ABI 类型编码](./docs/source/18.abi.md#1%EF%B8%8F⃣-abi类型编码)
  - [2️⃣ ABI 编码的设计准则](./docs/source/18.abi.md#2%EF%B8%8F⃣-abi编码的设计准则)
  - [3️⃣ 编码的形式化说明](./docs/source/18.abi.md#3%EF%B8%8F⃣-编码的形式化说明)
  - [4️⃣ 函数选择器和参数编码](./docs/source/18.abi.md#4%EF%B8%8F⃣-函数选择器和参数编码)
  - [5️⃣ 动态类型的使用](./docs/source/18.abi.md#5%EF%B8%8F⃣-动态类型的使用)
  - [6️⃣ 事件](./docs/source/18.abi.md#6%EF%B8%8F⃣-事件)
  - [7️⃣ 错误编码](./docs/source/18.abi.md#7%EF%B8%8F⃣-错误编码)
  - [8️⃣ JSON](./docs/source/18.abi.md#8%EF%B8%8F⃣-json)
  - [9️⃣ 严格编码模式](./docs/source/18.abi.md#9%EF%B8%8F⃣-严格编码模式)
  - [🔟 非标准打包模式](./docs/source/18.abi.md#-非标准打包模式)
  - [🆗 实战应用](./docs/source/18.abi.md#-实战应用)
  - [#️⃣ 问答题](./docs/source/18.abi.md#%EF%B8%8F⃣-问答题)
- [19.变量的布局](./docs/source/19.layout.md)
  - [1️⃣ 状态变量在 storge 中的布局](./docs/source/19.layout.md#1%EF%B8%8F⃣-状态变量在-storge-中的布局)
  - [2️⃣ 变量在 memory 布局](./docs/source/19.layout.md#2%EF%B8%8F⃣-变量在-memory-布局)
  - [3️⃣ Call Data 布局](./docs/source/19.layout.md#3%EF%B8%8F⃣-call-data-布局)
  - [4️⃣ 清理变量](./docs/source/19.layout.md#4%EF%B8%8F⃣-清理变量)
  - [#️⃣ 问答题](./docs/source/19.layout.md#%EF%B8%8F⃣-问答题)

第二部分：合约优化

*   [20.合约安全](./docs/forever/20.safe.md)
    *   [1️⃣ 时间锁合约](./docs/forever/20.safe.md#1%EF%B8%8F⃣-时间锁合约)
    *   [2️⃣ 重入攻击](./docs/forever/20.safe.md#2%EF%B8%8F⃣-重入攻击)
    *   [3️⃣ 数学溢出攻击](./docs/forever/20.safe.md#3%EF%B8%8F⃣-数学溢出攻击)
    *   [🆗 推荐做法](./docs/forever/20.safe.md#-推荐做法)
    *   [🆗 扩展阅读](./docs/forever/20.safe.md#-扩展阅读)
*   [21.Gas 优化](./docs/forever/21.gas.md)
    *   [1️⃣ 省钱总结](./docs/forever/21.gas.md#1%EF%B8%8F⃣-省钱总结)
    *   [2️⃣ 使用短路模式来排序操作](./docs/forever/21.gas.md#2%EF%B8%8F⃣-使用短路模式来排序操作)
    *   [3️⃣ 函数使用`external` + `calldata`](./docs/forever/21.gas.md#3%EF%B8%8F⃣-函数使用external--calldata)
    *   [4️⃣ 使用正确的数据类型](./docs/forever/21.gas.md#4%EF%B8%8F⃣-使用正确的数据类型)
    *   [5️⃣ 循环中不操作 `storage` 变量](./docs/forever/21.gas.md#5%EF%B8%8F⃣-循环中不操作-storage-变量)
    *   [6️⃣ 循环中的不重复计算数据](./docs/forever/21.gas.md#6%EF%B8%8F⃣-循环中的不重复计算数据)
    *   [7️⃣ 尽量少用循环](./docs/forever/21.gas.md#7%EF%B8%8F⃣-尽量少用循环)
    *   [8️⃣ 可预测的结果,不通过代码计算。](./docs/forever/21.gas.md#8%EF%B8%8F⃣-可预测的结果不通过代码计算)
    *   [9️⃣ 避免死代码](./docs/forever/21.gas.md#9%EF%B8%8F⃣-避免死代码)
    *   [🔟 避免不必要的判断](./docs/forever/21.gas.md#-避免不必要的判断)
    *   [1️⃣ 删除不必要的库](./docs/forever/21.gas.md#1%EF%B8%8F⃣-删除不必要的库)
    *   [🆗 优化案例](./docs/forever/21.gas.md#-优化案例)
*   [22.合约编码规范](./docs/forever/22.styleguide.md)
    *   [1️⃣ 代码布局](./docs/forever/22.styleguide.md#1%EF%B8%8F⃣-代码布局)
    *   [2️⃣ 代码中各部分的顺序](./docs/forever/22.styleguide.md#2%EF%B8%8F⃣-代码中各部分的顺序)
    *   [3️⃣ 文件结构分享](./docs/forever/22.styleguide.md#3%EF%B8%8F⃣-文件结构分享)
    *   [4️⃣ 命名约定](./docs/forever/22.styleguide.md#4%EF%B8%8F⃣-命名约定)
    *   [5️⃣ 更多内容](./docs/forever/22.styleguide.md#5%EF%B8%8F⃣-更多内容)
    

本来是做了 24 章的内容，但是为了以后方便印刷成纸质，所以删除了**真实案例分析**和**合约常见错误分析**这两个含有大量代码演示的章节。（比如案例分析里，光 uniswap V2/V3 和 Compound 这 3 个合约，每个印出来都是几十页的内容，太浪费篇幅了，以后单独放出来）

## 本地运行文档

克隆本仓库到你的电脑

```
git clone git@github.com:anbang/professional-solidity.git
```

**安装 Sphinx**：

```
yum -y install git make python3 python3-pip
pip3 install sphinx
pip3 install sphinx-autobuild
pip3 install sphinx_rtd_theme
pip3 install recommonmark
pip3 install sphinx_markdown_tables
```

**本地运行**：根目录执行如下命令

```
# 第一种
sphinx-autobuild docs build/html

# 第二种
./start.sh
```
