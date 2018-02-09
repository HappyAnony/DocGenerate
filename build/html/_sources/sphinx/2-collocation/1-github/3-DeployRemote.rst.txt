远程仓库部署
=============

参考文档

- `如何解决failed to push some refs to git <https://www.jianshu.com/p/835e0a48c825>`_
- `fatal Could not read from remote repository的解决办法 <http://blog.csdn.net/huahua78/article/details/52330792>`_

配置remote url
----------------
- 可使用\ ``git remote  -v``\ 命令查看当前配置的remote仓库
- 点击github仓库页面的\ ``clone and download``\ ;然后点击\ ``Use SSH``\ ，找到ssh的clone地址，复制该地址

.. figure:: ../images/1-github/23.png

- 如果\ ``git remote  -v``\ 命令结果为空，则使用\ ``git remote add origin <url>``\ 命令将刚才复制的\ ``remote ssh url``\ 新添加到git中
	- \ ``origin``\ 为remote远程仓库的默认名称
	- 注意url中的\ ``github.com``\ 需替换成config文件中Host别名\ ``DocGenerate``\ 或\ ``GnuToolchain``\ 

.. figure:: ../images/1-github/24.png

- 如果\ ``git remote  -v``\ 命令结果不为空，则使用\ ``git remote set-url origin <url>``\ 命令将\ ``remote url``\ 重置成刚才复制的\ ``remote ssh url``\ 
	- 注意url中的\ ``github.com``\ 需替换成config文件中Host别名\ ``DocGenerate``\ 或\ ``GnuToolchain``\

.. figure:: ../images/1-github/25.png

- 使用\ ``git push -u origin master``\ 命令将本地仓库push同步到刚才配置的remote远程仓库中

.. figure:: ../images/1-github/26.png

- 此时可能会报错误\ ``fatal: Could not read from remote repository.``\ ，出现错误的主要原因是github中的\ ``README.md``\ 文件不在本地代码目录中，可使用\ ``git pull --rebase origin master``\ 命令解决
	- 此时需要确保当前working暂存区的所有文件都已经commit提交到本地仓库中
	- 该项也提醒我们以后凡是\ ``git push``\ 之前最后先使用\ ``git pull``\ 将remote远程仓库内容拉到本地和本地仓库合并，然后再push到远程仓库，避免push时出现错误

.. figure:: ../images/1-github/27.png

- 然后使用\ ``git push -u origin master``\ 命令再次将本地仓库push同步到刚才配置的remote远程仓库中，此时就会push成功

.. figure:: ../images/1-github/28.png


