1. Creating a collapsed section
    - Any Markdown within the `<details>` block will be collapsed until the reader clicks `>`  to expand the details.
    - Within the `<details>` block, use the `<summary>` tag to create a label to the right of `>`.
    - The Markdown will be collapsed by default.
    - After a reader clicks `>`, the details are expanded.
    - 折叠按钮：一对<detail></detail> 中间包裹内容，一对<summary></summary> 设置向右箭头，中间包裹内容；


<details><summary>click me</summary>
<p>

#### we can hide anything,even code!

```
ruby puts "hello world"
```
</p>
</details>
