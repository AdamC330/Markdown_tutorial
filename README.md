# Markdown_cheatsheet
This is a repo that contains the content for a jekyll template (docksy). I put text files here to store them in case of exporting the files to a new jekyll template.

## What is Markdown?


Markdown is a markup language that consists of text-encoded symbols...

Test for Markdown syntax
##Paragraphs, head titles, quotation blocks
```
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

# H1
## H2
### H3
#### H4
##### H5
###### H6
---

```
> This is a quoteblock
>
> This is the second paragraph in the quoteblock.
>>indentation
>
> ## ## This is H2 in the blockquote
```
> This is a quoteblock
>
> This is the second paragraph in the quoteblock.
>>indentation
>
> ## This is H2 in the blockquote
---

```
Heading 1
=======
```
Heading 2
=======
---

```
Sub-heading
-----------
```
Sub-heading
-----------
---

```
Horizontal Rule:
---
___
```
Horizontal rule:
---

```
Text attributes

Emphasis, aka italics, with *asterisks* or _underscores_.
Strong emphasis, aka bold, with **asterisks** or __underscores__.
Combined emphasis with **asterisks and _underscores_**.
Strikethrough uses two tildes. ~~Scratch this.~~
`monospace`
```

Text attributes

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

`monospace`.

---

```
Escape character: "\"
\*italic\* won't be rendered  

I have eaten\
the plums\
that were in\
the icebox

1986\. What a great season. Arguably the finest season in the history of the franchise.
```
\*italic\* won't be rendered  

I have eaten\
the plums\
that were in\
the icebox


1986\. What a great season. Arguably the finest season in the history of the franchise.
---
___

---

```
Strikethrough:
~~strikethrough~~
```
Strikethrough:
~~strikethrough~~

---

```
Bullet list:

* apples
  * nested item 1
  * nested item 2
* oranges
* pears

+ apples
+ oranges
+ pears

- apples
- oranges
- pears
```
* apples
  * nested item 1
  * nested item 2
* oranges
* pears

---

```
Numbered list:
1. leather
2. rinse
3. repeat
```
Numbered list:
1. leather
2. rinse
3. repeat

---

```
- [ ] Item one
- [ ] Item two
- [x] Completed item
```
- [ ] Item one
- [ ] Item two
- [x] Completed item

---

```
Links and images:
An [example](http://example.com).
An [example](http://example.com "title on hover").
![Image](Icon-pictures.png "icon")
<p>Check out <a href="https://www.freecodecamp.org/" target="_blank">freeCodeCamp</a>.</p>

Inline image with link
[![file_name](../../images/icon-76x76.png)](https://github.com)
Inline image
![file_name](../../images/icon-76x76.png =50x76 "hover text")
![Image][1]
⋮
[1]: http://url/b.jpg

[Hurricane][1] Erika was the strongest and longest-lasting tropical cyclone in the 1997 Atlantic [hurricane][1] season.

[1]:https://goo.gl/YEEHP0

![](https://commonmark.org/help/images/favicon.png)
![Logo][1]

[1]: https://commonmark.org/help/images/favicon.png "Creative Commons licensed"
```
Links and images:
An [example](http://example.com).

An [example](http://example.com "title on hover").

![Image](Icon-pictures.png "icon")
<p>Check out <a href="https://www.freecodecamp.org/" target="_blank">freeCodeCamp</a>.</p>

[Hurricane][1] Erika was the strongest and longest-lasting tropical cyclone in the 1997 Atlantic [hurricane][1] season.

[1]:https://goo.gl/YEEHP0

![](https://commonmark.org/help/images/favicon.png)

![Logo][1]

[1]: https://commonmark.org/help/images/favicon.png "Creative Commons licensed"
---

Inline Code Block:

To create an inline code block, you have to use a backtick \` at the beginning of the text and at the end of it.

`Inline code` with backticks

`<p> This is a paragraph </p>`
When `x = 3`, that means `x + 2 = 5`
    When `x = 3`, that means `x + 2 = 5`
---

Code Blocks:

If you want to write a code block, you have to enclose the code with three backticks \` at the beginning of the code and at the end of it.

```
# code block
print '3 backticks or'
print 'indent 4 spaces'

····# code block
····print '3 backticks or'
····print 'indent 4 spaces'
```

# code block
print '3 backticks or'
print 'indent 4 spaces'

    # code block
    print '3 backticks or'
    print 'indent 4 spaces'

your code here \``\`
```
npm install
npm start
```
---

Or you can specify a programming language in which the code is written after typing the initial three backticks i.e.

"```javascript
function add(num1, num2) {
  return num1 + num2;
}```"

"```python
def add(num1, num2):
  return num1 + num2
}```"


```javascript
function add(num1, num2) {
  return num1 + num2;
}
```

```python
def add(num1, num2):
  return num1 + num2
}

``` go
package main
import "fmt"
func main() {
    fmt.Println("Hello, 世界")
}
```

```
---


```
Tables

|  name | email            |  
|------:|------------------|
| tom   | tom@domain.com   |   
| jenny | jenny@domain.com |   
|       |                  |  

```
|  name | email            |  
|------:|------------------|
| tom   | tom@domain.com   |   
| jenny | jenny@domain.com |   
|       |                  |



```
| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| Left column 1 | this text       |  $100 |
| Left column 2 | is              |   $10 |
| Left column 3 | centered        |    $1 |

```

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| Left column 1 | this text       |  $100 |
| Left column 2 | is              |   $10 |
| Left column 3 | centered        |    $1 |

```
Math Formulas

```latex
X_k = \sum_{n=0}^{2N-1} x_n \cos \left[\frac{\pi}{N} \left(n+\frac{1}{2}+\frac{N}{2}\right) \left(k+\frac{1}{2}\right) \right]
```


```
1. Ingredients

    - spaghetti
    - marinara sauce
    - salt

2. Cooking

   Bring water to boil, add a pinch of salt and spaghetti. Cook until pasta is **tender**.

3. Serve

   Drain the pasta on a plate. Add heated sauce.

   > No man is lonely eating spaghetti; it requires so much attention.

   Bon appetit!
```
1. Ingredients

    - spaghetti
    - marinara sauce
    - salt

2. Cooking

   Bring water to boil, add a pinch of salt and spaghetti. Cook until pasta is **tender**.

3. Serve

   Drain the pasta on a plate. Add heated sauce.

   > No man is lonely eating spaghetti; it requires so much attention.

   Bon appetit!

```

```
