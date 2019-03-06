# Object

继承自EventDispatcher

## 成员

* x 横坐标
* y 纵坐标
* width 宽
* height 高
* scaleX 横向缩放
* scaleY 纵向缩放
* scale(x, y) 设置缩放
* gray 是否灰色
* visible 是否可见
* touchable 是否可点击
* sortingOrder 渲染顺序
* group 所属组合
* text 文本内容
* icon 图标
* tooltips 悬浮提示文本
* parent 所在父组件
* removeFromParent() 从父组件移除自己
* popup([Object[, PopupDirection]) 弹出控件，可选参数：位置和方向
* togglePopup([Object[, PopupDirection]) 弹出或关闭控件，可选参数：位置和方向
* hidePopup() 关闭弹出
* globalToLocal(x, y) 全局坐标转换为当前UI坐标
* localToGlobal(x, y) 当前UI坐标转换为全局坐标
* center() 居中显示
* name 名字
* data 关联的任意lua值
* asTextField 转换成TextField
* asTextInput 转换成TextInput
* asRichTextField 转换成RichTextField
* asGraph 转换成Graph
* asLoader 转换成Loader
* asList 转换成List
* asComponent 转换成Component
* asLabel 转换成Label
* asButton 转换成Button
* asComboBox 转换成ComboBox
* asProgressBar 转换成ProgressBar
* asSlider 转换成Slider
* asScrollBar 转换成ScrollBar