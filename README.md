# VH-Toast

## 一款简约的基于原生 Javascript 的消息提示插件 VH-Toast

> 一款简约的基于原生 Javascript 的消息提示插件 VH-Toast。比如，`$vh.default`，`$vh.info` 等，默认为`default`。此时正文内容以`message`的值传入。同时，我们可传入 `vhHtml` 来支持 `HTML标签` 的显示。

> [韩小韩博客 - VH-Toast 一款简约的基于原生 Javascript 的消息提示插件](https://www.vvhan.com/vvhan-Toast.html)

## 演示地址

> [点击查看演示](https://www.vvhan.com/other/vh-toast/index.html)

## 调用

```html
<script src="https://cdn.jsdelivr.net/gh/uxiaohan/VH-Toast/lib/vh.toast.min.js"></script>
```

**默认样式**

```js
$vh.default("这是一条默认消息提示");

$vh.default({
  message: "这是一条默认消息提示",
});

$vh.default({
  message: "这是一条支持 HTML标签 的默认消息提示",
  vhHtml: true,
});
```

**成功样式**

```js
$vh.success("这是一条成功消息提示");

$vh.success({
  message: "这是一条成功消息提示",
});

$vh.success({
  message: "这是一条支持 HTML标签 的成功消息提示",
  vhHtml: true,
});
```

**消息样式**

```js
$vh.info("这是一条消息提示");

$vh.info({
  message: "这是一条消息提示",
});

$vh.info({
  message: "这是一条支持 HTML标签 的消息提示",
  vhHtml: true,
});
```

**警告样式**

```js
$vh.warning("这是一条警告消息提示");

$vh.warning({
  message: "这是一条警告消息提示",
});

$vh.warning({
  message: "这是一条支持 HTML标签 的警告消息提示",
  vhHtml: true,
});
```

**错误样式**

```js
$vh.error("这是一条错误消息提示");

$vh.error({
  message: "这是一条错误消息提示",
});

$vh.error({
  message: "这是一条支持 HTML标签 的错误消息提示",
  vhHtml: true,
});
```
