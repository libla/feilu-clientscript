# JSON接口

JSON序列化和反序列化

## 调用列表

* parse(string) 传入一个JSON字符串，得到一个对应的lua中表示的值
* print(value, [boolean[, boolean]]) 传入一个number/boolean/string/table，得到对应的JSON字符串，可选参数：第一个boolean表示是否格式化，第二个boolean表示非ASCII字符是否Unicode化显示
* null 表示JSON的null值