###Octopress主题

基于<https://github.com/TheChymera/Koenigspress>，作以下修改：

- 对原主题中的标识作汉化处理；
- 替换JS库等加载缓慢或无法加载的链接；

```
http://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js

http://libs.baidu.com/jquery/1.9.1/jquery.min.js
```

- 添加返回顶部按钮：

	- 添加按钮png到`/source/images`
	- 在`/source/_includes/custom`目录下新建[scroll_to_top.html](https://github.com/jemoii/Koenigspress/blob/master/source/_includes/custom/scroll_to_top.html)
	- 在[/source/_layouts/default.html](https://github.com/jemoii/Koenigspress/blob/master/source/_layouts/default.html)中添加：

```html
<div id="topcontrol">
	{% include custom/scroll_to_top.html %}
</div>
```
