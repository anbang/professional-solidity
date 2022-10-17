# Solidity 高级程序设计

**前置说明**：本教程的面向群体不是零基础 solidity 小白，不适合第一次接触Solidity的初学者；你需要掌握 solidity 语言的基本用法才能更好的继续阅读和理解，默认读者已经掌握了 Solidity 语言的基本用法，本教程供查漏补缺，深入学习使用。

**运行环境**：为了方便演示，本教程内所有的演示操作，均在 [Remix](https://remix.ethereum.org/) 中进行操作。学习的时候建议使用 Solidity 最新版本进行编码，最新版本可以在官方博客 [blog.soliditylang.org](https://blog.soliditylang.org/) 查看。

**额外说明**：本教程的所有知识点都不会拿别的语言进行类比。很多写作者写 solidity 教程的时候，喜欢在介绍某个知识点时，拿自己之前熟悉的语言和 solidity 类比介绍（比如 C++，Python，Java，Javascript 等），初心是让读者可以更容易理解；但是事与愿违，很多时候读者可能并不了解写作者熟悉的那门语言，导致不举例还好，对比举例更迷糊了。学习编程是一件很严肃的事情，本教程尽量避免无聊的调侃，类比和啰嗦的废话。

## 社交媒体信息

- 欢迎关注我的推特：[@anbang_account](https://twitter.com/anbang_account)
- 合约交流群：[Discord Solidity智能合约交流](https://discord.gg/AZmEtpmAjx)
- Youtube: [Anbang 的 Youtube 频道](https://www.youtube.com/c/anbang)
- Bilibili: [Anbang 的 Bilibili 频道](https://space.bilibili.com/59312814)

## 在线阅读文档



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