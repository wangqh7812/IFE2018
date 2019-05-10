##贝塞尔曲线
transition: all 2.0s cubic-bezier(a, b, c, d)

P0：默认值 (0, 0)  
P1：动态取值 (x1, y1)  
P2：动态取值 (x2, y2)  
P3：默认值 (1, 1)  

abcd就是p1p2的取值  

X 轴的取值范围是 0 到 1，当取值超出范围时 cubic-bezier 将失效；  
Y 轴的取值没有规定，当然也毋须过大。

##input属性
outline

##CSS函数
calc()函数：C允许计算 CSS 的属性值，比如动态计算长度值。

##box-shadow
box-shadow: h-shadow v-shadow blur spread color inset;  

值|说明
----|----
h-shadow|必需的。水平阴影的位置。允许负值
v-shadow|必需的。垂直阴影的位置。允许负值
blur|可选。模糊距离
spread|可选。阴影的大小
color|可选。阴影的颜色。在CSS颜色值寻找颜色值的完整列表
inset|可选。从外层的阴影（开始时）改变阴影内侧阴影


##CSS "~"选择器
element1~element2：选择前面有element1元素的每个element2元素。