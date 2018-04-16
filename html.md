

## 块引用

<blockquote> 与 </blockquote> 之间的所有文本都会从常规文本中分离出来，经常会在左、右两边进行缩进，而且有时会使用斜体。也就是说，块引用拥有它们自己的空间。

## 边框

要在元素周围创建边框，您只需要border-style 。 值可以是solid ， dotted ， dashed ， double ， groove ， ridge ， inset和outset 。

```
h2 { border-style: dashed; border-width: 3px; border-left-width: 10px; border-right-width: 10px; border-color: red; } 
```

## 缩略语

abbr用于标记缩写词，缩写形式的单词或短语。
缩写表示的扩展短语可以在title属性的值中定义。 这是可选的，但建议。

```
<p>This web site is about <abbr title="HyperText Markup Language">HTML</abbr> and <abbr title="Cascading Style Sheets">CSS</abbr> .</p> 
```

## 插入和删除 
ins和del分别用于显示编辑插入和删除 。 严格地说，它们不仅限于文本，还可以用于整个内容，但通常它们在审核中使用，就像文字处理器中的“追踪更改”功能一样


## 输入类型

```
 <input type="number" name="quantity" step="2" min="20" max="30">
 <input type="tel" name="telephone_number"> 
 <input type="url" name="web_address">
 <input type="email" name="email_address"> 
 <input type="range" name="temperature" min="15" max="25" step="0.5" value="18.5"> 

```

## 日期和时间

type="datetime"
type="date"
type="month"
type="week"
type="time"
type="datetime-local"


## 颜色

```
 <input name="color" type="color" value="#ff8800">
```

## 占位符文本

placeholder属性可以与文本input字段（以及它们的文本类表单，如type="email"和type="number" ）以及textarea元素一起使用。 它的目的是作为提示 ，而不是标签 ，仍然应该使用label元素。

## 自动对焦

当页面加载时，您可能需要将重点放在表单字段上。 例如，如果你想到一个搜索引擎，当你登陆它的主页时，你通常不需要点击搜索框来开始输入 - 你可以马上做，因为它已经有了焦点。 autofocus属性是实现此效果的一种快速方法。

## 视频 ， 音频

视频

```
 <video src="kitties.mp4" width="300" height="200" loop muted autoplay controls></video> 
```

音频
```
 <audio src="meow_mix.mp3" controls> Your stupid browser doesn't support HTML 5 audio. </audio>
 ```
