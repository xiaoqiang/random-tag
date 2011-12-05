###随机算法：
1. 先给元素随机出一个左上顶点的位置；
1. 然后根据元素的框高，用一维数组判断元素所在的二维坐标有没有被标记arr=1；
1. 如果有被标记的，计数随机次数randomTag++，然后重新进行第一步，并且标记flag=false，结束第二部的循环检查；
1. 如果randomTag == randomKey阀值，则假设这个层满了，不能塞进块了，那么就新建一层arr=[]；
1. 如果在第3步所有的点都没有被标记，即flag=true，则把这个节点显示在页面上，重置randomTag = 0；
[在线演示地址](http://xiaoqiang.org/demo/random-position/random-position.html)
