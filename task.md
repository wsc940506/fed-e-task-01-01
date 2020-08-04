## 1.D
## 2.D
## 3.开始时先触发钩子函数 prepatch 以及 update,然后对比新旧节点，第一步对比text属性， 如果老节点有children，移除老节点children对应的DOM元素，然后设置新节点对应DOM元素的textContent 总的来说以新虚拟节点为准，创造新的真实节点。最后回调postpatch钩子

