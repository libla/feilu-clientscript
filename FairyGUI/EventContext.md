# EventContext

事件关联上下文，基本只用于事件回调函数中

## 成员
* input 输入事件相关参数
* stop() 停止事件继续传递
* prevent() 停止处理事件
* capture() 捕捉触摸/鼠标
* uncapture() 释放触摸/鼠标
* prevented 事件是否已被停止