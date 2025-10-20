确保标签带有开始和结束标签（例如 `<div>` 和 `</div>`）正确匹配和嵌套。

这个 HTML 不正确，因为没有结束的 `</div>` 标签。

--- code ---
---
language: HTML
filename: index.html
line_numbers: false
---

<section>
<div><p>Lorem ipsum</p>
</section>

--- /code ---

这个 HTML 不正确，因为 `</div>` 出现在结束 `</p>` 标签之前。

--- code ---
---
language: HTML
filename: index.html
line_numbers: false
---

<div><p>Lorem ipsum</div></p>

--- /code ---

**提示：**如果你的 HTML 不正确，那么有时 Web 浏览器会尝试推测你的预期效果。你仍然应该确保你的 HTML 是正确的，因为不正确的 HTML 可能会在以后引起问题。不正确的 HTML 也会使屏幕阅读器难以理解你的页面。
