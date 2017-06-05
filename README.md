# dialog
一个小巧简约的弹窗插件
* width:   弹窗的宽度   number
* padding:  弹窗元素的 padding   字符串类型
* title:   弹窗的title名称   字符串类型
* discription:   弹窗的描述    字符串类型
* borderRadius:    弹窗的圆角    字符串类型
* bottons:   弹窗的按钮    数组类型  ['确定','取消']
* maskBg:    浮层的背景色    字符串类型
* dialogBg:    弹窗的背景色    字符串类型
* type:   弹窗的样式   字符串类型   defalut   primary   success   danger   warning
* zIndex:   弹窗的层级     number
* hideScroll:    是否在弹窗的时候  关闭右侧的滚动条    bool
* isBtnHasBgColor:  bottons 是否有背景色   bool
* showBoxShadow:   弹窗是否显示box-shadow    bool
* animateStyle:    弹窗进入的动画   fadeInNoTransform   字符串类型
* isInput:     是否显示文本输入框    bool
* inputPlaceholder:   文本输入框的Placeholder的设置    字符串类型

#回调
* callBack:function(ret){}   
* 返回值ret  ret.index 点击的索引, ret.input.status  (如果有输入框为1，否则为0),  ret.input.value  输入框的值
 
预览地址
http://daiwei.org/components/dialog/
