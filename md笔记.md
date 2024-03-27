#以下是Markdown文件笔记（按需取用！）
##标题写法
---

# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6
####### Heading level 7
……

##标题写法2
---

Heading level 1
===============
Heading level 2
---------------

##粗体写法
---

I just love **bold text**.

I just love __bold text__.

Love**is**bold

##斜体写法（Italic）
---

Italicized text is the *cat's meow*.

Italicized text is the _cat's meow_.

A*cat*meow

##粗斜体写法
---

This text is ***really important***.	

This text is ___really important___.	

This text is __*really important*__.	

This text is **_really important_**.	

This is really***very***important text.	

##引用写法
---

> Dorothy followed her through many of the beautiful rooms in her castle.

---

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

---

> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

---

> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.

##序号(有序列表)写法
---

1. First item
2. Second item
3. Third item
4. Fourth item
---

1. First item
8. Second item
3. Third item
5. Fourth item
---

1. First item
1. Second item
1. Third item
    2. Indented item
    2. Indented item
1. Fourth item

##序号(无序列表)写法
---

- First item
- Second item
- Third item
- Fourth item
---

- First item
+ Second item
* Third item
* Fourth item
---

- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item

---

*   This is the first list item.
*   Here's the second list item.

	> A blockquote would look great below the second list item.

*   And here's the third list item.


##代码写法
---

At the command prompt, type `nano`.

---

``Use `code` in your Markdown file.``

---
    <html>
      <head>
      </head>
    </html>
    
---

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

---

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

##链接写法
---

这是一个链接 [Markdown语法](https://markdown.com.cn)。

---
这是一个链接 [Markdown语法（悬停版）](https://markdown.com.cn "鼠标悬停显示")。

---
https://markdown.com.cn

fake@example.com

*有些情况需要加尖括号 <https://markdown.com.cn> <fake@example.com>*

---
I love supporting the **[EFF](https://eff.org)**.

This is the *[Markdown Guide](https://www.markdownguide.org)*.

See the section on [`code`](#code).

##图片写法
---

*![图片alt](图片链接 "图片title")*

![图片alt](D:/新建文件夹 (5)/参考.jpg "图片title")

[![沙漠中的岩石图片](/assets/img/shiprock.jpg "Shiprock")](https://markdown.com.cn)


##表格写法
---

| Syntax | Description |
| --- | ----------- |
| Header | Title |
| Paragraph | Text |


---

| Syntax左对齐      | Description居中 | Test Text右对齐     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

---

##脚注写法
---

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.


##删除线写法
---

~~世界是平坦的。~~ 我们现在知道世界是圆的。

##表情写法
---

去露营了！ :tent: 很快回来。

真好笑！ :joy:

