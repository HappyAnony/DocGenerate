文档编辑
============

文档编辑的核心在于 ``文本编辑器`` 和 ``reStructuredText语法``

text编辑器
-----------
支持 ``reStructuredText语法`` 的文本编辑器有
	- `Sublime <https://www.sublimetext.com/>`_ 

rst基本语法
---------------------
参考文档
~~~~~~~~~~
	- `官方文档 <http://www.sphinx-doc.org/en/stable/contents.html>`_
	- `轻量级标记语言 <http://www.worldhello.net/gotgithub/appendix/markups.html>`_

标题
~~~~~~
- 一级标题：``========``
- 二级标题：``--------``
- 三级标题：``~~~~~~~~``
- 四级标题：``^^^^^^^^``
- 五级标题：``++++++++``
- 六级标题：````````````


段落
~~~~~~~~~
- 空行分段

.. csv-table::
	:header: 代码示例, 输出示例
	:widths: 30, 30

	.. figure:: ../images/8-rst/1.png, .. figure:: ../images/8-rst/2.png

- 回车自动续行

.. csv-table::
	:header: 代码示例, 输出示例
	:widths: 30, 30

	.. figure:: ../images/8-rst/3.png, .. figure:: ../images/8-rst/4.png

- 不留白续行

.. csv-table::
	:header: 代码示例, 输出示例
	:widths: 30, 30

	.. figure:: ../images/8-rst/5.png, .. figure:: ../images/8-rst/6.png

- 插入换行

.. csv-table::
	:header: 代码示例, 输出示例
	:widths: 30, 30

	.. figure:: ../images/8-rst/7.png, .. figure:: ../images/8-rst/8.png
	.. figure:: ../images/8-rst/9.png, .. figure:: ../images/8-rst/10.png

- 段落缩进

.. csv-table::
	:header: 代码示例, 输出示例
	:widths: 30, 30

	.. figure:: ../images/8-rst/11.png, .. figure:: ../images/8-rst/12.png
	.. figure:: ../images/8-rst/13.png, .. figure:: ../images/8-rst/14.png

代码块
~~~~~~~~~

.. csv-table::
	:header: 代码示例, 输出示例
	:widths: 30, 30

	.. figure:: ../images/8-rst/15.png, .. figure:: ../images/8-rst/16.png


列表
~~~~~~~
- 无序列表

.. csv-table::
	:header: 代码示例, 输出示例
	:widths: 30, 30

	.. figure:: ../images/8-rst/17.png, .. figure:: ../images/8-rst/18.png

- 有序列表

.. csv-table::
	:header: 代码示例, 输出示例
	:widths: 30, 30

	.. figure:: ../images/8-rst/19.png, .. figure:: ../images/8-rst/20.png

- 列表续行、段落和代码块

.. csv-table::
	:header: 代码示例, 输出示例
	:widths: 30, 30

	.. figure:: ../images/8-rst/21.png, .. figure:: ../images/8-rst/22.png

定义
~~~~~~~~~~

.. csv-table::
	:header: 代码示例, 输出示例
	:widths: 30, 30

	.. figure:: ../images/8-rst/23.png, .. figure:: ../images/8-rst/24.png

字体
~~~~~~~~
- 粗体和斜体

.. csv-table::
	:header: 代码示例, 输出示例
	:widths: 30, 30

	.. figure:: ../images/8-rst/25.png, .. figure:: ../images/8-rst/26.png

- 删除线

.. csv-table::
	:header: 代码示例, 输出示例
	:widths: 30, 30

	.. figure:: ../images/8-rst/27.png, .. figure:: ../images/8-rst/28.png

- 下划线

.. csv-table::
	:header: 代码示例, 输出示例
	:widths: 30, 30

	.. figure:: ../images/8-rst/29.png, .. figure:: ../images/8-rst/30.png

- 上标、下标

.. csv-table::
	:header: 代码示例, 输出示例
	:widths: 30, 30

	.. figure:: ../images/8-rst/31.png, .. figure:: ../images/8-rst/32.png

- 等宽字体

.. csv-table::
	:header: 代码示例, 输出示例
	:widths: 30, 30

	.. figure:: ../images/8-rst/33.png, .. figure:: ../images/8-rst/34.png

- 引言

.. csv-table::
	:header: 代码示例, 输出示例
	:widths: 30, 30

	.. figure:: ../images/8-rst/35.png, .. figure:: ../images/8-rst/36.png

- 清除标记空白

.. csv-table::
	:header: 代码示例, 输出示例
	:widths: 30, 30

	.. figure:: ../images/8-rst/37.png, .. figure:: ../images/8-rst/38.png

链接
~~~~~~~
- URL自动链接

.. csv-table::
	:header: 代码示例, 输出示例
	:widths: 30, 30

	.. figure:: ../images/8-rst/39.png, .. figure:: ../images/8-rst/40.png

- 文字链接

.. csv-table::
	:header: 代码示例, 输出示例
	:widths: 30, 30

	.. figure:: ../images/8-rst/41.png, .. figure:: ../images/8-rst/42.png

- 内部跳转

.. csv-table::
	:header: 代码示例, 输出示例
	:widths: 30, 30

	.. figure:: ../images/8-rst/43.png, .. figure:: ../images/8-rst/44.png

- 脚注

.. csv-table::
	:header: 代码示例, 输出示例
	:widths: 30, 30

	.. figure:: ../images/8-rst/45.png, .. figure:: ../images/8-rst/46.png

图片
~~~~~~

.. csv-table::
	:header: 代码示例, 输出示例
	:widths: 30, 30

	.. figure:: ../images/8-rst/47.png, .. figure:: ../images/8-rst/48.png

表格
~~~~~~~

.. csv-table::
	:header: 代码示例, 输出示例
	:widths: 30, 30

	.. figure:: ../images/8-rst/49.png, .. figure:: ../images/8-rst/50.png

其它
~~~~~~~
- 转义

.. csv-table::
	:header: 代码示例, 输出示例
	:widths: 30, 30

	.. figure:: ../images/8-rst/51.png, .. figure:: ../images/8-rst/52.png


注意
-----
- 各种标记字符与其它文本内容之间最好留一个空格，否则会报语法警告