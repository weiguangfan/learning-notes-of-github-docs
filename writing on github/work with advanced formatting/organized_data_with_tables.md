1. Creating a table
   - You can create tables with pipes `|` and hyphens `-`. Hyphens are used to create each column's header, while pipes separate each column.
   - You must include `a blank line` before your table in order for it to correctly render.
   - 创建表格：用 | 分隔列，用 - 分隔行首；预留空白行，正确显示表格；
   
   | First Header | Second Header |
   | ------------ | ------------- |
   | Content Cell | Content Cell  |
   | Content Cell | Content Cell  |
   
   - The pipes on either end of the table are optional.
   - Cells can vary in width and do not need to be perfectly aligned within columns.
   - There must be at least three hyphens in each column of the header row.
   - 单元格的宽度随意改变，不需要严格对齐；行首单元格至少含有一组（三个） --- ；   

   | Command |Description|
   |---|---|
   |git status|list all new or modified files|
   |git diff|show file differences that haven't been staged|

2. Formatting content within your table

   - You can use formatting such as links, inline code blocks, and text styling within your table:
   - You can align text to the left, right, or center of a column by including colons `:` to the left, right, or on both sides of the hyphens within the header row.
   - To include a pipe `|` as content within your cell, use a `\` before the pipe:
   - 单元格内容可以使用基本操作，例如链接、粗斜体、引用等；
   - 在行首单元格的前、后、前后使用 ：，控制单元格内容左对齐、居中、右对齐；
   - 单元格内容使用 | ，需要使用转义字符 \。
   
   |command|description|
   |---|---|
   |`git status`|list all *new or modified* files|
   |`git diff`|show file differences that **haven't been staged**|

   | left-aligned | center-aligned | right-aligned |
   | :--- | :---: | ---:|
   | git status | git status | git status |
   | git diff | git diff | git diff |

   | name | character |
   | --- | --- |
   | backtick | ` |
   | pipe | \| |



