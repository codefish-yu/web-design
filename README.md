1. $(selector).hover(handlerIn,handlerOut)
当鼠标悬停在被选元素上时会运行两个函数，触发：mouseenter和mouseleave事件
示例文件：jQuery_hover.html

2. $(selector).stop(stopAll,goToEnd)
功能：被选元素停止当前正在运行的动画
参数：stopAll规定是否停止被选元素的所有加入队列的动画，默认为false
　　　goToEnd规定是否立即完成当前额动画，默认为false