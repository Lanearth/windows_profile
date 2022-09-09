# windows优化指北
本项目具有如下宗旨：
1. 尽可能避免日常使用过程中双手离开键盘核心区，减少鼠标操作
2. 维护一份个人的软件安装脚本，降低重装系统的成本
*但需注意，过度优化并不能提高效率*

为达成上述目标，本项目将会包含如下内容：
1. jetbrains系列编程软件和vs code的vim插件配置
2. 用于安装常用软件的脚本

## .ideavimrc
ideavimrc配置文件（spacevim的简化版本，并增加了部分具有个人风格的配置）
- 在插入模式下
    - 模拟了部分emacs的快捷键，比如C-a，C-e，A-b，A-f等
    - 同时使用C-h, C-j, C-k, C-l模拟上下左右键
    - 使用C-b, C-d模拟Backspace, Delete键
- 在普通模式下
    - 基本保持vim的原生键位，但加入了部分个人习惯的快捷键
    - 推荐使用ace-jump插件快速跳转光标

## .auto_install_softwares.ps1
自动安装软件的脚本，大部分软件使用scoop管理，少量软件通过winget获取，主要包括
- 开发软件，开发环境
- 一些windows下的终端工具

## 部分需要手动配置的软件
通过如下软件，实现键盘映射以及模拟鼠标行为
- powertoys
- quicker
*上述软件也可以用autohotkey作为代替*