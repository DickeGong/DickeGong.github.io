### 初始CSS
* style 表示风格、样式
* background-color:gray; 设定背景颜色
* font-size：24px; 设定字体大小
* color:white; 设定字体颜色
*  span 一个容器标签，不具备任何特殊功能，仅当作容器来使用。用于包裹一段文本，便于给文本增加样式。
* div 一个通用容器标签，不具备任何特殊功能，仅当作容器来使用。可以包裹任何内容，也可以容器直接互相包裹。
### 如何居中
*  text-align:center; 让容器内部元素水平居中
*  margin：auto； 让容器本身水平居中
*  margin 表示边距
*  auto 表示自动
---
    <div id="banner"></div>
    <div id="navigation"><div>
    <div id="bottom"></div>
---
* banner 横幅
* navigation 导航
* bottom 底部
### div容器的特点
* 一个空div，默认宽度100%，高度为0
### 行高
---
    line-height:21px
    21px是行高的默认高度
---
### CSS内部样式
---
    <style>
    a{
           text-decoration：none;color：black；margin：0 15px；
    }
    </style>
---
### CSS选择器
#### 1.ID选择器 #box
* ID表示身份，在页面中元素的id不允许重复，因此id选择器只能选择单个元素
#### 2.标签选择器 div
* 根据标签名称选择对应的所有标签
#### 3.类（别）选择器
* 选择拥有该类别的多个元素
#### 4.通用选择器
* 针对页面所有的标签都生效
### 边框
---
    ————  solid
    ----  dashed
    ....  dotted
---
* none 表示没有
* 行内样式优先级>内部样式
### CSS优先级
* 行内样式 > ID选择器 > 类选择器 > 标签选择器 > 通用选择器
---
    <...styie="...">  行内样式
    #box{...}  ID选择器
    .con{...}  类选择器
    div{...}   标签选择器
    *{...}     通用选择器
---
### 权重值
* 1.通用选择器 *
* 权重值0
* 2.标签（元素）选择器 div、p...
* 权重值1
* 3.类（别）选择器 .act]、.nav...
* 权重值10
* 4.ID选择器 #btn、#box
* 权重值100
* 5.行内样式
* 权重值1000
### CSS文本属性
* font-family        字体类型
* font-weight:bold   字体加粗
* font-style：italic  斜体字
* line-height：35px； 行高
* text-indent：60px   缩进
* text-decoration     文本修饰
### 常见图片格式区别
* 图片压缩格式
---
    jpg
    支持动画
    只有全透明和不透明
    只有256种颜色

    gif
    采用有损压缩算法
    体积较小
    不支持透明
    不支持动画

    png
    采用无损压缩算法
    体积也相对较小
    支持背景透明
    不支持动画
---
### 图片的使用
* 元素宽高的百分比，是相对于父元素而言的，若父元素高度为0，则子元素高度即使设置100%，大小也是0，html元素大小是相对于浏览器窗口而言的
---
     repeat   重复
     position 位置
     right    右
     bottom   底部
     center   居中
---
### 元素的浮动
* 浮动元素会他脱离网页文档，与其他元素发生重叠但是，不会与文字内容发生重叠
---
    float:left  左浮动
    float:right 右浮动
---
* 子元素是可以把父元素撑开
---
    overflow  表示溢出的意思 
    clear：left   表示该元素不受左浮动的影响
    clear：right  表示该元素不受右浮动的影响
---
## background
---
    background-color  背景色
    background-image  背景图片
    background-repeat 背景图平铺方式
    background：gray url(xxx/xx.png) no-repeat；
    background: url(xxx/xx.png) repeat-y;
    background:gray;
---
## border
---
    border-width  边框宽度
    border-style  边框样式
    border-color  边框颜色
    boeder：1px solid #D2f402；
    boeder：3px dashed；颜色默认为黑色
---