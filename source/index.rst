.. 文档编排 documentation master file, created by
   sphinx-quickstart on Sat Dec 02 14:24:43 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.




文档编排
===========


概述
-------

::

	俗话说：不会写文档的程序员都是在耍流氓

文档的用途有很多：

* 知识框架梳理
* 项目帮助文档
* 项目API文档
* 电子书

现有的编写文档方式有很多：

.. csv-table::
	:header: 写作方式, `标记语言 <http://www.worldhello.net/gotgithub/appendix/markups.html>`_ , 应用场景
	:widths: 15, 15, 30

	`GitHub Wiki <https://help.github.com/categories/wiki/>`_ ,  `Markdown <https://daringfireball.net/projects/markdown/syntax>`_ , 知识框架梳理等
	`Gitbook <https://www.gitbook.com/explore>`_ , `Markdown <https://daringfireball.net/projects/markdown/syntax>`_, 知识框架梳理、电子书等
	`Sphinx <http://www.sphinx-doc.org/en/stable/contents.html>`_ , `reStructuredText <http://jwch.sdut.edu.cn/book/rst.html>`_ / `Markdown <https://daringfireball.net/projects/markdown/syntax>`_ , 项目帮助文档、项目API文档、电子书等

当然，还有其它的方式，比如： `CSDN博客` 、`博客园` 、`私有博客` 等；但是博客有一致命弱点：**编排杂乱，不便索引**

该系列文章将围绕上述3种主流的文档编排方式进行展开说明。

目录
------

.. toctree::
   :titlesonly:
   :glob:

   sphinx/index
   gitbook/index




........................\ *持续更新中*\ ......................





