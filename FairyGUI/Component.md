# Component

继承自Object

## 静态
* new() 构造函数

## 成员
* addChild(Object) 添加子控件
* addChild(Object, int) 添加子控件到指定顺序
* removeChild(Object) 删除指定的子控件
* removeChild(int) 删除指定顺序位置的子控件
* getChild(string) 通过名字获取子控件
* getChild(int) 获取指定顺序位置的子控件
* getChildIndex(Object) 获取指定子控件的顺序位置
* setChildIndex(Object, int) 设置指定子控件的顺序位置
* swapChildren(Object, Object) 交换2个指定子控件的顺序位置
* swapChildren(int, int) 交换2个指定顺序位置的子控件
* numChildren 获得子控件的数量
* getController(string) 获得控制器
* getTransition(string) 获得动效
* opaque 是否点击穿透
* scrollPane 获取滚动控制面板(如果有滚动)
* fullscreen() 设置为全屏
* removeChildren() 移除全部子控件
* removeChildren(int, int) 移除指定顺序位置范围的子控件