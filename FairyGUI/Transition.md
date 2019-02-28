# Transition

动效

## 成员
* owner 所属组件
* playing 是否正在播放
* pause(bool) 暂停/恢复播放
* hook(string, callback) 监听事件
* clear() 清除所有监听
* timeScale 时间缩放
* play()/play(callback) 开始播放，callback在播放完成时回调
* play(bool)/play(bool, callback) 指定是否反向播放，callback在播放完成时回调
* stop() 停止播放