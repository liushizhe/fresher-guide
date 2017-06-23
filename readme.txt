1、cookie操作，不过只能在火狐浏览器使用
2、引导步骤都是图片，将图片当成背景（位于网页背景上层），根据display:block/none切换显示图片，步骤显示时设置背景透明属性opacity（或filter:alpha(opacity=50)）
3、图片内相应位置嵌入相应矩形框，用到绝对定位，矩形框中有文字，通过text-indent:-999px;overflow:hidder;方式屏蔽文字
