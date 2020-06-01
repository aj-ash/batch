# Batch

![License-MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Docs-Passing](https://img.shields.io/badge/Docs-Passing-green.svg)

中文 | [English](../README.md)

一份 Batch 帮助文档。

## 生成

打开 CMD 程序并执行下面的命令。

```Batch
help > temp_File

grep -o -E "^[A-Z]*" temp_File > filter_File

for /f %i in (filter_File) do cmd /c %i /? > Command\%i

del /q temp_File && del /q filter_File
```

## 引索

|     命令     |     描述     |
| :----------- | :----------- |
| [ASSOC](Command/ASSOC) |  显示或修改文件扩展名关联。 |
| [ATTRIB](Command/ATTRIB) |  显示或更改文件属性。 |
| [BREAK](Command/BREAK) |  设置或清除扩展式 CTRL+C 检查。 |
| [BCDEDIT](Command/BCDEDIT) |  设置启动数据库中的属性以控制启动加载。 |
| [CACLS](Command/CACLS) |  显示或修改文件的访问控制列表(ACL)。 |
| [CALL](Command/CALL) |  从另一个批处理程序调用这一个。 |
| [CD](Command/CD) |  显示当前目录的名称或将其更改。 |
| [CHCP](Command/CHCP) |  显示或设置活动代码页数。 |
| [CHDIR](Command/CHDIR) |  显示当前目录的名称或将其更改。 |
| [CHKDSK](Command/CHKDSK) |  检查磁盘并显示状态报告。 |
| [CHKNTFS](Command/CHKNTFS) |  显示或修改启动时间磁盘检查。 |
| [CLS](Command/CLS) |  清除屏幕。 |
| [CMD](Command/CMD) |  打开另一个 Windows 命令解释程序窗口。 |
| [COLOR](Command/COLOR) |  设置默认控制台前景和背景颜色。 |
| [COMP](Command/COMP) |  比较两个或两套文件的内容。 |
| [COMPACT](Command/COMPACT) |  显示或更改 NTFS 分区上文件的压缩。 |
| [CONVERT](Command/CONVERT) |  将 FAT 卷转换成 NTFS。你不能转换当前驱动器。 |
| [COPY](Command/COPY) |  将至少一个文件复制到另一个位置。 |
| [DATE](Command/DATE) |  显示或设置日期。 |
| [DEL](Command/DEL) |  删除至少一个文件。 |
| [DIR](Command/DIR) |  显示一个目录中的文件和子目录。 |
| [DISKPART](Command/DISKPART) |  显示或配置磁盘分区属性。 |
| [DOSKEY](Command/DOSKEY) |  编辑命令行、撤回 Windows 命令并创建宏。 |
| [DRIVERQUERY](Command/DRIVERQUERY) |  显示当前设备驱动程序状态和属性。 |
| [ECHO](Command/ECHO) |  显示消息，或将命令回显打开或关闭。 |
| [ENDLOCAL](Command/ENDLOCAL) |  结束批文件中环境更改的本地化。 |
| [ERASE](Command/ERASE) |  删除一个或多个文件。 |
| [EXIT](Command/EXIT) |  退出 CMD.EXE 程序(命令解释程序)。 |
| [FC](Command/FC) |  比较两个文件或两个文件集并显示它们之间的不同。 |
| [FIND](Command/FIND) |  在一个或多个文件中搜索一个文本字符串。 |
| [FINDSTR](Command/FINDSTR) |  在多个文件中搜索字符串。 |
| [FOR](Command/FOR) |  为一组文件中的每个文件运行一个指定的命令。 |
| [FORMAT](Command/FORMAT) |  格式化磁盘，以便用于 Windows。 |
| [FSUTIL](Command/FSUTIL) |  显示或配置文件系统属性。 |
| [FTYPE](Command/FTYPE) |  显示或修改在文件扩展名关联中使用的文件类型。 |
| [GOTO](Command/GOTO) |  将 Windows 命令解释程序定向到批处理程序中某个带标签的行。 |
| [GPRESULT](Command/GPRESULT) |  显示计算机或用户的组策略信息。 |
| [GRAFTABL](Command/GRAFTABL) |  使 Windows 在图形模式下显示扩展字符集。 |
| [HELP](Command/HELP) |  提供 Windows 命令的帮助信息。 |
| [ICACLS](Command/ICACLS) |  显示、修改、备份或还原文件和目录的 ACL。 |
| [IF](Command/IF) |  在批处理程序中执行有条件的处理操作。 |
| [LABEL](Command/LABEL) |  创建、更改或删除磁盘的卷标。 |
| [MD](Command/MD) |  创建一个目录。 |
| [MKDIR](Command/MKDIR) |  创建一个目录。 |
| [MKLINK](Command/MKLINK) |  创建符号链接和硬链接 |
| [MODE](Command/MODE) |  配置系统设备。 |
| [MORE](Command/MORE) |  逐屏显示输出。 |
| [MOVE](Command/MOVE) |  将一个或多个文件从一个目录移动到另一个目录。 |
| [OPENFILES](Command/OPENFILES) |  显示远程用户为了文件共享而打开的文件。 |
| [PATH](Command/PATH) |  为可执行文件显示或设置搜索路径。 |
| [PAUSE](Command/PAUSE) |  暂停批处理文件的处理并显示消息。 |
| [POPD](Command/POPD) |  还原通过 PUSHD 保存的当前目录的上一个值。 |
| [PRINT](Command/PRINT) |  打印一个文本文件。 |
| [PROMPT](Command/PROMPT) |  更改 Windows 命令提示。 |
| [PUSHD](Command/PUSHD) |  保存当前目录，然后对其进行更改。 |
| [RD](Command/RD) |  删除目录。 |
| [RECOVER](Command/RECOVER) |  从损坏的或有缺陷的磁盘中恢复可读信息。 |
| [REM](Command/REM) |  记录批处理文件或 CONFIG.SYS 中的注释(批注)。 |
| [REN](Command/REN) |  重命名文件。 |
| [RENAME](Command/RENAME) |  重命名文件。 |
| [REPLACE](Command/REPLACE) |  替换文件。 |
| [RMDIR](Command/RMDIR) |  删除目录。 |
| [ROBOCOPY](Command/ROBOCOPY) |  复制文件和目录树的高级实用工具 |
| [SET](Command/SET) |  显示、设置或删除 Windows 环境变量。 |
| [SETLOCAL](Command/SETLOCAL) |  开始本地化批处理文件中的环境更改。 |
| [SC](Command/SC) |  显示或配置服务(后台进程)。 |
| [SCHTASKS](Command/SCHTASKS) |  安排在一台计算机上运行命令和程序。 |
| [SHIFT](Command/SHIFT) |  调整批处理文件中可替换参数的位置。 |
| [SHUTDOWN](Command/SHUTDOWN) |  允许通过本地或远程方式正确关闭计算机。 |
| [SORT](Command/SORT) |  对输入排序。 |
| [START](Command/START) |  启动单独的窗口以运行指定的程序或命令。 |
| [SUBST](Command/SUBST) |  将路径与驱动器号关联。 |
| [SYSTEMINFO](Command/SYSTEMINFO) |  显示计算机的特定属性和配置。 |
| [TASKLIST](Command/TASKLIST) |  显示包括服务在内的所有当前运行的任务。 |
| [TASKKILL](Command/TASKKILL) |  中止或停止正在运行的进程或应用程序。 |
| [TIME](Command/TIME) |  显示或设置系统时间。 |
| [TITLE](Command/TITLE) |  设置 CMD.EXE 会话的窗口标题。 |
| [TREE](Command/TREE) |  以图形方式显示驱动程序或路径的目录结构。 |
| [TYPE](Command/TYPE) |  显示文本文件的内容。 |
| [VER](Command/VER) |  显示 Windows 的版本。 |
| [VERIFY](Command/VERIFY) |  告诉 Windows 是否进行验证，以确保文件正确写入磁盘。 |
| [VOL](Command/VOL) |  显示磁盘卷标和序列号。 |
| [XCOPY](Command/XCOPY) |  复制文件和目录树。 |
| [WMIC](Command/WMIC) |  在交互式命令 shell 中显示 WMI 信息。 |

## 许可证

[MIT](../LICENSE)
