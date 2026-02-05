# more-and-more-stronger
more and more stronger


## 零基础转行web3学习路线记录
#### **day1：HTML：标签、表单、列表、超链接，CSS：选择器、盒模型**
##### 实操任务：写一个「个人介绍页面」，包含文字、图片、表单
```
    验收标准：页面结构完整，样式整洁
    选择器：
    作用：通过在HTML元素中使用"id" 和 "class"选择器，设置CSS样式
    id 选择器：id选择器可以为标有特定 id 的 HTML 元素指定特定的样式。HTML元素以id属性来设置id选择器,CSS 中 id 选择器以 "#" 来定义。（ID属性不要以数字开头，数字开头的ID在 Mozilla/Firefox 浏览器中不起作用。）
        #para1{  text-align:center;color:red;  }

    class 选择器：class 选择器用于描述一组元素的样式，class 选择器有别于id选择器，class可以在多个元素中使用。
    class 选择器在 HTML 中以 class 属性表示, 在 CSS 中，类选择器以一个点 . 号显示：
        .center {text-align:center;}

    所有HTML元素可以看作盒子，在CSS中，"box model"这一术语是用来设计和布局时使用。
    CSS盒模型本质上是一个盒子，封装周围的HTML元素，它包括：边距，边框，填充，和实际内容。
    盒模型允许我们在其它元素和周围元素边框之间的空间放置元素。

```

#### **day2：CSS：浮动、定位、弹性布局（Flex）**
##### 实操任务：改造个人介绍页面，用 Flex 实现页面布局居中
```
验收标准：掌握 Flex 核心用法

浮动：float
css的浮动，会使元素向左或向右方向移动，其周围的元素也会跟着重新排列
清除浮动：clear:both 在左右两侧均不允许浮动元素。
clear的属性值：left right both none inherit(规定应该从父元素继承 clear 属性的值)

定位：position
position的属性值：absolute（绝对） fixled（固定） relative（相对定位） static（没有定位） sticky（粘贴定位） inherit（继承父元素）
重叠的元素 设置z-index（数值大的放在前面）

弹性布局：flex
display: flex;

flex-direction 属性指定了弹性子元素在父容器中的位置。
flex-direction: row | row-reverse | column | column-reverse
justify-content	设置弹性盒子元素在主轴（横轴）方向上的对齐方式。
align-items	设置弹性盒子元素在侧轴（纵轴）方向上的对齐方式。
flex-wrap	设置弹性盒子的子元素超出父容器时是否换行。
align-content	修改 flex-wrap 属性的行为，类似 align-items, 但不是设置子元素对齐，而是设置行对齐
flex-flow	flex-direction 和 flex-wrap 的简写
order	设置弹性盒子的子元素排列顺序。
align-self	在弹性子元素上使用。覆盖容器的 align-items 属性。
flex	设置弹性盒子的子元素如何分配空间。
```

#### **day3：CSS：网格布局（Grid）、响应式布局（媒体查询）**
##### 实操任务：做一个「响应式导航栏」，适配手机 / 电脑端, 页面在不同尺寸下正常显示