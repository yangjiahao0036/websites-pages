# Page Template

复制这个目录结构来新增页面：

```text
new-topic/
  index.html
```

然后在根目录 `index.html` 的 `.grid` 内增加一个卡片：

```html
<a class="card" href="new-topic/">
  <span class="tag">分类</span>
  <h2>页面标题</h2>
  <p class="desc">页面简介。</p>
  <span class="open">打开页面</span>
</a>
```
