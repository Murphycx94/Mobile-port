# Mobile-port
about Mobile port 
如何使用？

这是rem布局的核心代码，这段代码的大意是：
如果页面的宽度超过了640px，那么页面中html的font-size恒为100px，否则，页面中html的font-size的大小为： 100 * (当前页面宽度 / 640)

 

为什么是640px？

设计图一般是640px的，这样相当于100px = 1rem，可以方便计算；
