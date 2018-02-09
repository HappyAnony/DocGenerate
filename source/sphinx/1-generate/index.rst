文档生成
==========


概述
------

	Sphinx是一个由Python编写的基于 `reStructuredText <http://docutils.sourceforge.net/rst.html>`_ 【 `轻量级标记语言 <https://en.wikipedia.org/wiki/Lightweight_markup_language>`_ 的一种 】标记语言的文档生成工具。最早是用来生成Python官方文档，随着工具的完善，它已经成为Python项目首选的文档工具，同时它对C/C++项目也有很好的支持，并计划对其它开发语言添加特殊支持；下面列出了其良好的特性，这些特性在Pytho官方文档中均有体现：

		* 丰富的输出格式: 支持 HTML (包括 Windows 帮助文档), LaTeX (可以打印PDF版本), manual pages（man 文档）, 纯文本
		* 完备的交叉引用: 语义化的标签,并可以自动化链接函数,类,引文,术语及相似的片段信息
		* 明晰的分层结构: 可以轻松的定义文档树,并自动化链接同级/父级/下级文章
		* 美观的自动索引: 可自动生成美观的模块索引
		* 精确的语法高亮: 基于 `Pygments <http://pygments.org/>`_ 自动生成语法高亮
		* 开放的扩展: 支持代码块的自动测试,并包含Python模块的自述文档(API docs)等

	Sphinx使用\ `reStructuredText <http://docutils.sf.net/rst.html>`_\ 作为标记语言, 可以享有\ `Docutils <http://docutils.sf.net/>`_\ 为\ ``reStructuredText``\ 提供的分析，转换等多种工具.


	Sphinx的具体使用可参考：\ `Sphinx官方文档 <http://www.sphinx-doc.org/en/stable/contents.html>`_\ 以及\ `Sphinx中文文档 <https://zh-sphinx-doc.readthedocs.io/en/latest/contents.html>`_\

	以下关于Sphinx的使用介绍也是参考上述文档。


目录
------

.. toctree::
   :titlesonly: 
   :glob:

   1-introduction
   2-install
   3-project
   4-edit
   5-build
   6-markup

