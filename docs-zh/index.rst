Solidity
========

Solidity 是一个面向合约的高级语言，语法类似于 JavaScript，它被设计用在运行在以太坊虚拟机（EVM）上。

Solidity 是静态类型的语言，支持继承，拥有自己类库，并且支持复杂的用户定义类型。

在后续的内容中你将会发现，它可以用来创建投票、众筹、封闭拍卖、多重签名钱包等多种合约。

.. note::
    目前尝试 Solidity 最佳的方式是使用
    `基于浏览器的编译器 <https://ethereum.github.io/browser-solidity/>`_
    （加载可能有点缓慢，请耐心等待）。

有用的链接
------------

* `Ethereum <https://ethereum.org>`_

* `Changelog <https://github.com/ethereum/solidity/blob/develop/Changelog.md>`_

* `Story Backlog <https://www.pivotaltracker.com/n/projects/1189488>`_

* `Source Code <https://github.com/ethereum/solidity/>`_

* `Ethereum Stackexchange <https://ethereum.stackexchange.com/>`_

* `Gitter Chat <https://gitter.im/ethereum/solidity/>`_

Solidity 可用的集成环境
-------------------------------

* `Browser-Based Compiler <https://ethereum.github.io/browser-solidity/>`_
    基于浏览器的 IDE 整合了编译器和 Solidity 运行时，不包含服务器端组件。

* `Ethereum Studio <https://live.ether.camp/>`_
    特定的 web IDE，提供了通过 shell 访问整个以太坊开发环境的能力。

* `IntelliJ IDEA plugin <https://plugins.jetbrains.com/plugin/9475-intellij-solidity>`_
    IntelliJ IDEA 的 Solidity 插件（其他 JetBrains IDE 也都可以使用）。

* `Visual Studio Extension <https://visualstudiogallery.msdn.microsoft.com/96221853-33c4-4531-bdd5-d2ea5acc4799/>`_
    微软 Visual Studio 的 Solidity 插件，包含了 Solidity 的编译器。

* `Package for SublimeText — Solidity language syntax <https://packagecontrol.io/packages/Ethereum/>`_
    SublimeText 的 Solidity 语法高亮插件。

* `Atom Ethereum interface <https://github.com/gmtDevs/atom-ethereum-interface>`_
    Atom 编辑器的 Solidity 插件，包含了语法高亮、编译器、运行时（要求有后台节点支持）。

* `Atom Solidity Linter <https://atom.io/packages/linter-solidity>`_
    Atom 编辑器的 Solidity 插件提供了 Solidity linting 功能。
    
* `Solium <https://github.com/duaraghav8/Solium/>`_
    一个命令行 linter 工具，严格遵从 `Solidity 代码风格指南 <http://solidity.readthedocs.io/en/latest/style-guide.html>`_ 中描述的规则。

* `Visual Studio Code extension <http://juan.blanco.ws/solidity-contracts-in-visual-studio-code/>`_
    Visual Studio Code 的 Solidity 插件，包含了语法高亮和 Solidity 编译器。

* `Emacs Solidity <https://github.com/ethereum/emacs-solidity/>`_
    Emacs 的 Solidity 插件，提供了语法高亮和编译期错误报告的支持。

* `Vim Solidity <https://github.com/tomlion/vim-solidity/>`_
    Vim 的 Solidity 插件，提供了语法高亮的支持。

* `Vim Syntastic <https://github.com/scrooloose/syntastic>`_
    Vim 的 Solidity 插件，提供了语法检查的支持。

已停止更新:

* `Mix IDE <https://github.com/ethereum/mix/>`_
    基于 Qt 开发的一款 IDE，支持设计、调试、测试 Solidity 智能合约。


Solidity 工具
--------------

* `Dapple <https://github.com/nexusdev/dapple>`_
    Solidity 包管理器。

* `Solidity REPL <https://github.com/raineorshine/solidity-repl>`_
    通过交互命令行快速尝试 Solidity 。

* `solgraph <https://github.com/raineorshine/solgraph>`_
    可视化 Solidity 控制流程和高亮潜在安全漏洞。

* `evmdis <https://github.com/Arachnid/evmdis>`_
    EVM 的反汇编程序，利用对字节码的静态分析，提供了比原生 EVM 操作更高级的抽象能力。

第三方 Solidity 解析器
-----------------------------------------

* `solidity-parser <https://github.com/ConsenSys/solidity-parser>`_
    JavaScript 版本的 Solidity 语法解析器

* `Solidity Grammar for ANTLR 4 <https://github.com/federicobond/solidity-antlr4>`_
    用于 ANTLR 4 语法生成器的 Solidity 文法规则

语言文档
----------------------

在接下来的文章中，我们先来看一个用 solidity 写的 :ref:`简单智能合约 <simple-smart-contract>` 。
紧接着我们会介绍 :ref:`区块链 <blockchain-basics>`
和 :ref:`以太坊虚拟机 <the-ethereum-virtual-machine>` 的基础知识。

之后的章节会通过一些实用的 :ref:`合约示例 <voting>` 来解释 Solidity 的各种特性。
记住，你可以在
`你的浏览器中 <https://ethereum.github.io/browser-solidity>`_ 尝试这些合约示例！

最后，我们会深入探讨 Solidity 的方方面面。

如果你仍然有疑问，你可以试着在
`Ethereum Stackexchange <https://ethereum.stackexchange.com/>`_
网站上进行搜索或者提问，也可以加入我们的 `gitter 频道 <https://gitter.im/ethereum/solidity/>`_ 。
我们非常欢迎对 Solidity 本身或者是文档有建设性意义的想法！


`俄语版本 (русский перевод) <https://github.com/ethereum/wiki/wiki/%D0%A0%D1%83%D0%BA%D0%BE%D0%B2%D0%BE%D0%B4%D1%81%D1%82%D0%B2%D0%BE-%D0%BF%D0%BE-Solidity>`_。

目录
========

:ref:`关键词索引 <genindex>`, :ref:`搜索页 <search>`

.. toctree::
   :maxdepth: 2

   introduction-to-smart-contracts.rst
   installing-solidity.rst
   solidity-by-example.rst
   solidity-in-depth.rst
   security-considerations.rst
   using-the-compiler.rst
   style-guide.rst
   common-patterns.rst
   contributing.rst
   frequently-asked-questions.rst
