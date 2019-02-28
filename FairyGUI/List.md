# List

继承自Component

## 成员

* defaultItem 默认子项组件
* numItems 子项总数
* childToItem(int) 子项索引转换为列表索引
* itemToChild(int) 列表索引转换为子项索引
* itemRenderer 子项渲染
* scrollItemToViewOnClick 点击子项时是否滚动过去
* foldInvisibleItems 不显示的子项是否不占用空间
* selectedIndex 已选择的子项
* addSelection(int, bool) 添加选择项，并指定是否滚动过去
* removeSelection(int) 去掉选择项
* clearSelection() 清除所有选择项
* selectAll() 选择所有项
* selectReverse() 反选
* refreshVirtual() 刷新虚拟列表
* virtual 是否虚拟列表
* setVirtual 设置为虚拟列表(不可逆)
* getSelection() 获取所有选择项
* resizeToFit(int[, int]) 设置列表到合适的大小，可选参数：最小大小
* scrollToView(int) 滚动到指定项
* addItem([url]) 添加列表项
* removeItem(int/Object) 删除列表项
* removeItems() 删除所有列表项
* removeItems(int, int) 删除指定范围的列表项