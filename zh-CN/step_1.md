确保标签带有开始和结束标签（例如 `<div>` 和 `</div>`）正确匹配和嵌套。

这个 HTML 不正确，因为没有结束的 `</div>` 标签。

## --- code ---

language: HTML
filename: index.html
line_numbers: false
--------------------------------------------------------

<section>
<div><p>Lorem ipsum</p>
</section>

\--- /code ---

This HTML is incorrect because the `</div>` appears before the closing `</p>` tag.

## --- code ---

language: HTML
filename: index.html
line_numbers: false
--------------------------------------------------------

<div><p>Lorem ipsum</div></p>

\--- /code ---

**Tip:** If your HTML is incorrect, then sometimes a web browser will work out what you meant. You should still make sure your HTML is correct as incorrect HTML might cause problems later. Incorrect HTML also makes it difficult for screen readers to understand your page.
