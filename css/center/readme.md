- CSS Rule
    1.盒子模型  content + padding + border + margin 快递
    2.背景颜色调试大法
    3.css 布局方式的一种
        - 离它最近的position relateive 元素定位
        - 如果没有，就一直往外查找 body
    4.block 块级元素  盒子能力  占增个一行，设置宽高 把兄弟元素挤下去
      inline 行内元素  没有盒子 自身内容撑起来的 不能设置宽高
      inline-block 既能设置宽高 又不会把兄弟元素挤下去
    5.display: flex; 弹性布局

- 垂直居中
    1.父子元素
        父元素 relative(不是必须的)
        子元素 absolute
    2.先确定大小
        transform rotate | translate |scale
        变基

- 方法
        - 定位 + margin负值
            父元素  一定要得到大小  (不如transform)
        - 定位 + transform
            相对于自身移动
        - calc 将父元素的一半减去子元素的一半
            缺点是性能不好
        - 弹性布局
            不用定位,
            缺点是太新了，兼容性不好