<a id="readme-head"></a>

## 1 line without 2 spaces or miss line:
first message in README.md
first message in README.md
first message in README.md
## How make a paragraph? 2 spaces or 1 miss line  
first message in README.md  
first message in README.md  
first message in README.md  

# Titles

# simbol \# - make titles, count \# - 1-6 Large-little

good rule is miss 1 line after title

# Title 1 = 1*\#

## Title 2 = 2*\#

### Title 3 = 3*\#

#### Title 4 = 4*\#

##### Title 5 = 5*\#

###### Title 6 = 6*\#

####### Title 7 = 7*\# - it dont work like a title

# Lists

### Numeral list
1. Syntax is simply
    1. Nested list1 (4 spaces)
    2. Nested kist2
2. Number + dot
3. Easy

### Nameless list
* Syntax different, * + - same result
    * Minus (4 spaces) nested list
    * Plus
* Star

# 3 Type of cursive

Cursive appear when we use \_text\_ or \*text\* Example:
1. *Text* = \_text\_ or \*text\*
2. **Text** = \_\_text\_\_ or \*\*text\*\*
3. ***Text*** = \_\_\_text\_\_\_ or \*\*\*text\*\*\*

# Horizontal lines
3 and more symbols(_ - *)

---
***
____

# Code in md
* one line code, use by \`code\` `print("Hello World")`
* some lines, use by \`\`\`python(for color syntax) or 4 spaces
*code*\`\`\`   
```python
    def factorial(n):
        """Calculate factorial n"""
        if n == 0:
            return 1
        else:
            return n * factorial(n - 1)
    
    result = factorial(5)
    print(f"factorial is {result}")
```

# Fence for special symbols

\\* = *  
\\ = \\\

# Quotes

> This is simple example qoute
>
> End quote

# Links

### syntax .md

* https://github.com/ailovenick/Markdown_Learning = without symbols, just link  
* <https://github.com/ailovenick/Markdown_Learning> = \<\>  
* [my project](https://github.com/ailovenick/Markdown_Learning) = \[my project\]\(https://github.com/ailovenick/Markdown_Learning\)  
* [my project](https://github.com/ailovenick/Markdown_Learning "text") = \[my project\]\(https://github.com/ailovenick/Markdown_Learning \"text\"\)
* [back to top](https://github.com/ailovenick/Markdown_Learning/tree/main?tab=readme-ov-file#1-line-without-2-spaces-or-miss-line) = `[back to top]([https://github.com/ailovenick/Markdown_Learning/edit/main/README.md#1-line-without-2-spaces-or-miss-line](https://github.com/ailovenick/Markdown_Learning/tree/main?tab=readme-ov-file#1-line-without-2-spaces-or-miss-line))`

### syntax html

* `<a id="readme-head"></a>` = label follow
* `<a href=#readme-head> This link follow back to top </a>` = <a href=#readme-head> This link follow back to top </a>
* `<p align=right><a href=#readme-head> This link follow back to top </a><p>` = <p align=right><a href=#readme-head> This link follow back to top </a><p>

<details>
    <summary> Test html list </summary>
    <ol>
        <li> 1 line </li>
        <li> 2 line </li>
        <li> 3 line </li>
        <li> <a href=#readme-head>link go to top</a></li>
    </ol>
</details>
