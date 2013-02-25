# tipbox

---

支付宝通用信息提示框样式，共有提示、成功、警告、等待等七种提示框。

---

## 演示 - 各类常用的提示框

> 本组件使用了 `alice.iconfont` 组件，请保证页面引用了相应代码。

<link type="text/css" rel="stylesheet" media="screen" href="src/tipbox.css">

### 信息

````html
<div class="ui-tipbox ui-tipbox-message">
    <div class="ui-tipbox-icon">
        <i class="iconfont" title="提示">&#x00ED;</i>
    </div>
    <div class="ui-tipbox-content">
        <h3 class="ui-tipbox-title">提示标题</h3>
        <p class="ui-tipbox-explain">完成的说明完成的说明。</p>
        <p class="ui-tipbox-explain"><a href="#">查询缴费记录</a> | <a href="#">我的支付宝</a></p>
    </div>
</div>
````

### 出错

````html
<div class="ui-tipbox ui-tipbox-error">
    <div class="ui-tipbox-icon">
        <i class="iconfont" title="出错">&#x006B;</i>
    </div>
    <div class="ui-tipbox-content">
        <h3 class="ui-tipbox-title">错误标题</h3>
        <p class="ui-tipbox-explain">完成的说明完成的说明。</p>
        <p class="ui-tipbox-explain"><a href="#">查询缴费记录</a> | <a href="#">我的支付宝</a></p>
    </div>
</div>
````

### 警告

````html
<div class="ui-tipbox ui-tipbox-warning">
    <div class="ui-tipbox-icon">
        <i class="iconfont" title="警告">&#x00EC;</i>
    </div>
    <div class="ui-tipbox-content">
        <h3 class="ui-tipbox-title">警告标题</h3>
        <p class="ui-tipbox-explain">完成的说明完成的说明。</p>
        <p class="ui-tipbox-explain"><a href="#">查询缴费记录</a> | <a href="#">我的支付宝</a></p>
    </div>
</div>
````

### 成功

````html
<div class="ui-tipbox ui-tipbox-success">
    <div class="ui-tipbox-icon">
        <i class="iconfont" title="成功">&#x00EF;</i>
    </div>
    <div class="ui-tipbox-content">
        <h3 class="ui-tipbox-title">成功标题</h3>
        <p class="ui-tipbox-explain">完成的说明完成的说明。</p>
        <p class="ui-tipbox-explain"><a href="#">查询缴费记录</a> | <a href="#">我的支付宝</a></p>
    </div>
</div>
````

### 阻止


````html
<div class="ui-tipbox ui-tipbox-stop">
    <div class="ui-tipbox-icon">
        <i class="iconfont" title="阻止">&#x00EE;</i>
    </div>
    <div class="ui-tipbox-content">
        <h3 class="ui-tipbox-title">阻止标题</h3>
        <p class="ui-tipbox-explain">完成的说明完成的说明。</p>
        <p class="ui-tipbox-explain"><a href="#">查询缴费记录</a> | <a href="#">我的支付宝</a></p>
    </div>
</div>
````

### 等待

````html
<div class="ui-tipbox ui-tipbox-wait">
    <div class="ui-tipbox-icon">
        <i class="iconfont" title="等待">&#x00F3;</i>
    </div>
    <div class="ui-tipbox-content">
        <h3 class="ui-tipbox-title">等待标题</h3>
        <p class="ui-tipbox-explain">完成的说明完成的说明。</p>
        <p class="ui-tipbox-explain"><a href="#">查询缴费记录</a> | <a href="#">我的支付宝</a></p>
    </div>
</div>
````

### 疑问


````html
<div class="ui-tipbox ui-tipbox-question">
    <div class="ui-tipbox-icon">
        <i class="iconfont" title="疑问">&#x00F1;</i>
    </div>
    <div class="ui-tipbox-content">
        <h3 class="ui-tipbox-title">疑问标题</h3>
        <p class="ui-tipbox-explain">完成的说明完成的说明。</p>
        <p class="ui-tipbox-explain"><a href="#">查询缴费记录</a> | <a href="#">我的支付宝</a></p>
    </div>
</div>
````

### 空白的提示框，可以嵌入到 xbox 里，与上面的样式配合使用

````html
<div class="ui-tipbox ui-tipbox-white ui-tipbox-message">
    <div class="ui-tipbox-icon">
        <i class="iconfont" title="提示">&#x00ED;</i>    
    </div>
    <div class="ui-tipbox-content">
        <h3 class="ui-tipbox-title">提示标题</h3>
        <p class="ui-tipbox-explain">完成的说明完成的说明。</p>
        <p class="ui-tipbox-explain"><a href="#">查询缴费记录</a> | <a href="#">我的支付宝</a></p>
    </div>
</div>
````

### 简单的提示框

````html
<div class="ui-tipbox ui-tipbox-message">
    <div class="ui-tipbox-icon">
        <i class="iconfont" title="提示">&#x00ED;</i>    
    </div>
    <div class="ui-tipbox-content-simple">
        <h3 class="ui-tipbox-title">一句话就说明白的事</h3>
    </div>
</div>
````
