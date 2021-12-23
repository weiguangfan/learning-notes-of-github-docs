1. You can create `fenced code blocks` by placing `triple backticks ```\` before and after the code block.
2. We recommend placing `a blank line` before and after code blocks to make the raw formatting easier to read.
3. 引用代码块：一对``` 包裹内容；代码块前后，各留出一行，便于显示效果；
4. To display `triple backticks ```\` in a fenced code block, wrap them inside `quadruple backticks ````\`.
5. 若想在代码块内使用 ``` ，用 一对```` 包裹；
6. You can add `an optional language identifier` to enable syntax highlighting in your `fenced code block`.
7. 若高亮显示代码块，需要添加语言标识符；

```
function test(){
    console.log("notice the blank line before this function ?")
} 
```


````
```
look! you can see my backticks.
```
````


```ruby
require 'redcarpet'
markdown = Redcarpet.new("hello world")
puts markdown.to_html 
```










