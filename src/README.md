# 手写 DOM 库

## 文档说明
`create(string)` 创建元素

`find(selector, scope)` 查找元素

`after(node, node2)` 在 node 后插入 node2

`before(node, node2)` 在 node 前添加 node2

`append(parent, child)` 给 parent 添加子元素 child

`wrap(node, parent)` 给 node 新增父节点 parent

`remove(node)` 删除 node

`empty(node)` 清空 node 的所有子节点

`attr(node, name, value)` 读、写属性

`text(node, content)` 读写文本

`html(node, html)` 读写 node 中的 HTML

`style(node, name, value)` 读写 node 的 style

`class.add(node, className)` 给 node 添加 class

`class.remove(node, className)` 移除 node 的某个 className

`class.has(node, className)` 判断 node 中是否有某个 class

`on(node, eventName, fn)` 绑定事件

`off(node, eventName ,fn)` 解除事件绑定

`parent(node)` 获取 node 的父节点

`children(node)` 获取 node 的所有子元素

`siblings(node)` 获取 node 的所有兄弟元素

`next(node)` 下一个兄弟元素

`previous(node)` 上一个兄弟元素

`each(nodeList, fn)` 遍历 nodeList

`index(node)` 获取 node 在所有兄弟元素中的次序