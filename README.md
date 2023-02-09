# envelope-effect
css和基本的js实现信纸从信封中拿出来的效果
# 原理
改变物体的top值来实现上下移动。在信纸被hover时，改变信纸的css代码。此时就应该改变top。
# 缺陷
在信纸被after遮盖时，无法通过hover信纸来选择此时的物体。具体的一些样式，没有往代码中写，比如说当input控件被focus时，应该改变input的background值。
使之凸显。同时应该增加input控件的placeholder值。来提示用户。等等，很多东西都没有实现。但是主要的效果实现了就ok了。
