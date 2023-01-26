# 按钮类
soui的标准库内提供了5中按钮样式，您可以使用属性 `.soui-btn` 创建一个按钮。  
![标准按钮](https://gp0.saobby.com/i/3QqW9SrYB10Vecrw.png)
```html
<button class="soui-btn" onclick="alert('你点击了按钮')">默认按钮</button>
<button class="soui-btn soui-correct-btn" onclick="alert('你点击了按钮')">正确按钮</button>
<button class="soui-btn soui-error-btn" onclick="alert('你点击了按钮')">错误按钮</button>
<button class="soui-btn soui-warning-btn" onclick="alert('你点击了按钮')">警告按钮</button>
<button class="soui-btn soui-tip-btn" onclick="alert('你点击了按钮')">提示按钮</button>
```
### 禁用按钮事件
通过 `<button>` 元素设置属性 `disabled` 和 `.soui-noclick-btn` 来禁用按钮。  
![禁用按钮事件](https://gp0.saobby.com/i/jTfXxM5uwZlQNx2C.png)
```html
<button class="soui-btn soui-noclick-btn" onclick="alert('你点击了按钮')" disabled>被禁用的按钮</button>
```
### 带轮廓的按钮
如不希望按钮带有背景颜色，请将按钮的样式属性改变为 `.soui-outline-*-btn`。  
![带轮廓的按钮](https://gp0.saobby.com/i/3ZEv966WtJvc5phI.png)
```html
<button class="soui-btn soui-outline-btn">带轮廓的按钮</button>
<button class="soui-btn soui-outline-correct-btn">带轮廓的按钮</button>
<button class="soui-btn soui-outline-error-btn">带轮廓的按钮</button>
<button class="soui-btn soui-outline-warning-btn">带轮廓的按钮</button>
<button class="soui-btn soui-outline-tip-btn">带轮廓的按钮</button>
```
### 按钮尺寸
想要不同大小的按钮？使用属性 `.soui-lg-btn` 和 `.soui-sm-btn` 来设置按钮的大与小。  
![按钮尺寸1](https://gp0.saobby.com/i/kAzxBMpv6WHbBUOE.png)
```html
<button class="soui-btn soui-lg-btn">更大的按钮</button> 
<button class="soui-btn">正常按钮</button> 
<button class="soui-btn soui-sm-btn">更小的按钮</button>  
```
通过属性 `.soui-block-btn` 来创建块级按钮（占满父元素的宽）  
![按钮尺寸2](https://gp0.saobby.com/i/yw6fwcpbbLq5rdCj.png)
```html
<button class="soui-btn soui-block-btn">块级按钮</button>
```
