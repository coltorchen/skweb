# skweb
skweb is a simple web render by skia

https://github.com/SerenityOS/serenity 这个仓库下有一个比较简单的LibWeb和LibJS,能够渲染简单的HTML页面,并且支持CSS2,我打算移植一下,使得这个LibWeb可以运行在各个主流的操作系统上.

底层的图形库,由于LibWeb依赖该仓库的LibGfx,初步打算将该图形库换成Skia,方便各个平台运行显示.

目标很简单,就是做一个HTML和CSS的Web渲染器.
