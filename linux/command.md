# Linux命令

~~待整理归纳~~

1. 使用 `[命令] --help` 可以获取基本命令指南

1. 历史纪录 `history`

    - `history`   查看历史命令行
    - `history -c`  清空历史纪录  
    - `history -r history.file`  从文件中恢复历史纪录
    - `!100` 执行历史纪录里面的第 100 行命令
    - `!!`  执行上次使用指令  

1. 变量命令相关

    1. `set` 查看当前shell环境中的所有变量 包含全局，局部
    1. `env` 查看当前shell环境中的全局变量
    1. `export` 显示环境变量

1. 变量使用

    1. `$var` 使用变量的值
    1. `${var}` 使用变量的值
    1. `$()` 提取括号内的命令作为参数结果，如 `“当前时间是$(data)”`将输出`当前时间是 2024...`
    1. ` `` ` 功能同 `$()`
