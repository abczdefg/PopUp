# PopUp with triangle by CSS

纯CSS绘制带三角形弹出框

原理：

1. 带border的三角形：利用盒子模型，将`width`和`height`设为0，4个`border`则为4个三角形

3. 用以上方法分别画出**弹出框背景色**的三角形，和**弹出框边框色**的三角形，利用position让2个三角形重叠，看起来是带边框的三角形

3. 利用css的hover属性和各种选择器，控制弹出框的显示


（顺便复习flex布局）