# Solidity 高级程序设计

**前置说明**：本教程的面向群体不是零基础 solidity 小白，不适合第一次接触 Solidity 的初学者；你需要掌握 solidity 语言的基本用法才能更好的继续阅读和理解，默认读者已经掌握了 Solidity 语言的基本用法，本教程供查漏补缺，深入学习使用。

**运行环境**：为了方便演示，本教程内所有的演示操作，均在 [Remix](https://remix.ethereum.org/) 中进行操作。学习的时候建议使用 Solidity 最新版本进行编码，最新版本可以在官方博客 [blog.soliditylang.org](https://blog.soliditylang.org/) 查看。

**额外说明**：本教程的所有知识点都不会拿别的语言进行类比。很多写作者写 solidity 教程的时候，喜欢在介绍某个知识点时，拿自己之前熟悉的语言和 solidity 类比介绍（比如 C++，Python，Java，Javascript 等），初心是让读者可以更容易理解；但是事与愿违，很多时候读者可能并不了解写作者熟悉的那门语言，导致不举例还好，对比举例更迷糊了。学习编程是一件很严肃的事情，本教程尽量避免无聊的调侃，类比和啰嗦的废话。

## 感想

这套《Solidity 高级程序设计》肯定是 Solidity 中文区 TOP3 级别的教程，争取做中文区 TOP1 教程，为了让更多人参与和了解，我做了如下资料的配套。

- Github 源文件：开放，让读者最低成本的参与优化和修复
- 在线文档：方便随时阅读
- PDF 文件：方便本地断网浏览
- 实体书籍：方便有读书习惯的人阅读。

所有的文档和源码全部开放，所有的配套视频也全部免费开放，并配有配套的 PDF 文件，PDF 文件也是免费的。如果你发现有哪里可以优化的，可以直接在 Github 仓库上提交你的改动，如果你想参与教程的修改和优化，改 Github 源文件是最低门槛的方式。

## 在线阅读

- **文字版**:
  - <a target="_blank" rel="noopener noreferrer" href="https://professional-solidity.readthedocs.io/zh_CN/latest/">在线文档阅读: Read The Docs</a>（方便大陆地区以外的地方浏览）
  - <a target="_blank" rel="noopener noreferrer" href="https://www.axihe.com/solidity/professional-solidity.html">在线文档阅读: 阿西河网站</a>（国内可以直接浏览，方便大陆地区浏览）
- **视频版**:
  - [在线视频观看: Youtube](https://www.youtube.com/watch?v=ao5nkAgx7kU&list=PLdXBX6Eqe4Net43OWIZychHW0n6CX_8Ih)
  - [在线视频观看: Bilibili](https://www.bilibili.com/video/BV1HR4y197Ag)

## 社交媒体信息

- 关注我的推特：[@anbang_account](https://twitter.com/anbang_account) （👏欢迎关注）
- 加入合约交流群：[Solidity 智能合约交流群](https://discord.gg/AZmEtpmAjx) （Discord）

## 初步目录

- 01.初识
  - 1️⃣ 区块链基础
  - 2️⃣ Hello World
  - 3️⃣ 合约代码中的三种注释
  - 4️⃣ 合约结构介绍
  - 5️⃣ 全局的以太币单位
  - 6️⃣ 接收 ETH
  - 7️⃣ selfdestruct:合约自毁
  - 🆗 实战 1: 同志们好
  - 🆗 实战 2: 存钱罐合约
  - 🆗 实战 3: WETH 合约
  - #️⃣ 问答题
- 02.数据
  - 1️⃣ 数据与变量
  - 2️⃣ 两种类型的数据
  - 3️⃣ 值类型
  - 4️⃣ 值类型:地址类型
  - 5️⃣ 值类型:合约类型
  - 6️⃣ 引用类型的额外注解:数据位置
  - 7️⃣ 引用类型
  - 8️⃣ 类型转换
  - 9️⃣ 字面常量与基本类型的转换
  - 🆗 实战 1: Todo List
  - 🆗 实战 2: 众筹合约
  - 🆗 实战 3: 同志们好增加提示
  - 🆗 实战 4: ETH 钱包
  - 🆗 实战 5: 多签钱包
  - #️⃣ 问答题
- 03.变量
  - 1️⃣ 变量基础知识
  - 2️⃣ Constant 常量
  - 3️⃣ Immutable 不可变量
  - 4️⃣ 变量名的命名规则
  - 5️⃣ 变量的可见性
  - 6️⃣ 全局：时间单位
  - 7️⃣ 全局：区块和交易属性
  - #️⃣ 问答题
- 04.函数
  - 1️⃣ 函数的定义
  - 2️⃣ 函数的调用
  - 3️⃣ 构造函数
  - 4️⃣ visibility:可见性
  - 5️⃣ mutability:状态可变性
  - 6️⃣ 函数的返回值 returns/return
  - 7️⃣ 函数的签名/函数标识符
  - 8️⃣ 函数的重载
  - 9️⃣ modifier:修饰符/修改器
  - 🔟 全局：数学和密码学函数
  - 1️⃣ 全局：ABI 编码及解码函数
  - 2️⃣ 补充:函数赋值给变量 & 函数作为参数 & 函数种返回函数
  - 🆗 实战应用
  - #️⃣ 问答题
- 05.运算操作符
  - 1️⃣ 算术运算符
  - 2️⃣ 比较运算符
  - 3️⃣ 逻辑运算符/关系运算符
  - 4️⃣ 赋值运算符
  - 5️⃣ 条件运算符/三元运算符
  - 6️⃣ 位运算符
  - 7️⃣ delete
  - 8️⃣ 操作符的优先级
  - 总结
  - 🆗 实战应用
  - #️⃣ 问答题
- 06.错误处理
  - 1️⃣ require
  - 2️⃣ assert
  - 3️⃣ revert
  - 4️⃣ 三种方式的总结
  - 5️⃣ 自定义 Error
  - natspec Error
  - 6️⃣ try catch
  - 🆗 实战应用
  - #️⃣ 问答题
- 07.流程控制
  - 1️⃣ if else
  - 2️⃣ 三元运算符
  - 3️⃣ assembly:内联汇编:switch
  - 🆗 实战应用
  - #️⃣ 问答题
- 08.循环与迭代
  - 1️⃣ for 语句
  - 2️⃣ while 语句
  - 3️⃣ do…while
  - 🆗 实战应用
  - #️⃣ 问答题
- 09.事件
  - 1️⃣ Event 语法
  - 2️⃣ 四种事件定义方式
  - 3️⃣ indexed 的作用
  - 4️⃣ log 的使用
  - 5️⃣ Log 重载
  - 🆗 实战: 众筹合约
  - #️⃣ 问答题
- 10.继承
  - 1️⃣ 使用 is 实现继承
  - 2️⃣ 子类可以继承父类哪些数据？
  - 3️⃣ 多重继承中的重名
  - 4️⃣ 重写函数
  - 5️⃣ 多级继承的代码书写顺序（线性化）
  - 6️⃣ 继承中两种构造函数传参方式
  - 7️⃣ 继承中构造函数的执行顺序
  - 8️⃣ 两种子合约调用父合约的方法
  - 9️⃣ 继承合约执行顺序的疑问
  - 🆗 实战应用
  - #️⃣ 问答题
- 11.合约调用合约
  - 1️⃣ 调用内部合约
  - 2️⃣ 调用外部合约
  - 3️⃣ MultiCall/多次调用
  - 4️⃣ MultiDelegatecall / 多次委托调用
  - 🆗 实战应用
  - #️⃣ 问答题
- 12.合约部署合约
  - 1️⃣ 通过 new 创建合约 / create
  - 2️⃣ 通过 salt 创建合约 / create2
  - 3️⃣ 创建合约的扩展
  - 🆗 实战应用：使用 assembly 做 create
  - 🆗 实战应用：使用 assembly 做 create2
  - #️⃣ 问答题
- 13.interface:接口
  - 1️⃣ 限制
  - 2️⃣ 定义和使用
  - 3️⃣ 全局属性 type(I).interfaceId
  - 🆗 实战: 标准的 ERC20 接口
  - 🆗 实战: ERC721 合约
  - 🆗 实战: ERC1155 合约
  - 🆗 实战: ERC3525 合约
  - 🆗 实战:荷兰拍卖
  - 🆗 实战:英式拍卖
  - #️⃣ 问答题
- 14.Library:库
  - 1️⃣ 库合约与普通智能合约区别
  - 2️⃣ 直接调用库合约方法
  - 3️⃣ using...for... 使用库合约
  - 4️⃣ 直接调用 和 using for 对比
  - 5️⃣ 销毁合约库
  - 6️⃣ 扩展阅读
  - 🆗 实战应用
  - #️⃣ 问答题
- 15.算法
- 16.Assembly:内联汇编
- 17.metadata:元数据
- 18.ABI 编码
- 19.变量的布局
- 20.合约安全
- 21.Gas 优化
- 22.合约编码规范
- 23.错误提示的整理
- 24.已知 bug 列表

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
sphinx-autobuild docs build/html
```
