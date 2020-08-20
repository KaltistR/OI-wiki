GUIDE（GAIT Universal IDE）是由北航 GAIT 研究组开发的、专门为 NOI 选手设计的、支持 C/C++/Pascal 三种程序设计语言的小型集成开发环境。

NOI Linux 系统自带 GUIDE，因此 GUIDE 也成为了选手在 NOI 系列比赛中可用的一种集成开发环境。

## 编辑文件

点击页面上方工具栏的“新文件”按钮（或者使用<kbd>Ctrl</kbd>+<kbd>N</kbd>快捷键）来创建一个新文件。

在默认情况下，GUIDE 的代码字体并非等宽字体，看上去非常不美观，因此需要在设置中更改字体。

在 编辑 -> 选项 -> 语法高亮设置 中，点击“全部字体”按钮，即可切换编辑器字体。

需要注意的是，对于未保存的新文件，字体仍然是默认字体。因此建议在开始编辑前先保存文件（点击工具栏的“保存”按钮，或按下<kbd>Ctrl</kbd>+<kbd>S</kbd>快捷键），再进行编辑。

## 编译与运行

在编辑完源代码后，点击工具栏的“编译”按钮（或<kbd>F7</kbd>快捷键）进行编译。

???+note "更改编译选项"
    GUIDE 没有设置默认编译选项的功能，用户只能更改对某个文件的编译选项。
    
    右键点击想要更改编译选项的文件的标签，选择 **设置编译命令** 选项，即可更改该文件的编译选项。

如果源代码正常编译，点击工具栏的“运行”按钮（或<kbd>Ctrl</kbd>+<kbd>F5</kbd>快捷键）即可运行程序。

## 调试

GUIDE 自带的调试功能存在很多 bug（如程序中途发生崩溃等），因此不推荐直接使用 GUIDE 的调试功能。

建议直接在 [终端](../cmd.md) 下使用 gdb 来进行调试。