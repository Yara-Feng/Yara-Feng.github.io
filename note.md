# 学习笔记
## DOM的属性和方法
**有些只对元素节点有效，有些只对文本节点有效，有些对所有节点都有效。**
```JS
.nodeType // 节点类型
.nodeName // 节点名称
.textContent // 节点文本内容
.parentNode // 节点的父节点
.parentElement // 节点的父元素节点
.children // 节点的子元素节点
.firstChild // 节点的第一个子节点
.lastChild // 节点的最后一个子节点
.cloneNode(true/false) // 克隆节点，参数为true时，会克隆节点的所有子节点，参数为false时，只克隆节点本身
.removeChild() // 删除子节点
.appendChild() // 添加子节点
.remove() // 删除节点
.querySelector() // 选中节点的第一个符合条件的子元素节点
.querySelectorAll() // 选中节点的所有符合条件的子元素节点
.getAttribute() // 选中节点的属性值
.setAttribute() // 设置节点的属性值
.removeAttribute() // 删除节点的属性值
.hasAttribute() // 判断节点是否有某个属性
.hasAttributes() // 判断节点是否有任何属性
.innerHTML // 节点的HTML内容
.innerText // 节点的文本内容
.style // 节点的样式属性
.style.property // 节点的样式属性值
.style.property = value // 设置节点的样式属性值
.classList // 节点的类名列表
.classList.add() // 添加类名
.classList.remove() // 删除类名
.classList.toggle() // 切换类名
.classList.contains() // 判断是否包含某个类名
.classList.replace() // 替换类名
.classList.item() // 选中类名列表中的某个类名
.classList.length // 类名列表的长度
.classList.forEach() // 遍历类名列表
```
