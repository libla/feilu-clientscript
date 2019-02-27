# 说明

## 脚本根目录
脚本工程的Resources\Script目录

## 脚本封装

### 引用系统库
要使用math/string等系统库，需要在脚本中先进行导出，如
```
local math = require "math"
```
之后就可以使用math库了

### 引用其他文件
要使用脚本目录下的其他文件，需要在脚本中先进行导出，如
```
local test = require "test"
```
之后test就指向test.lua的全局环境表，可以直接读取变量，调用函数等