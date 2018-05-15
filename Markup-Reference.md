# Markup Reference

### Headings
Precede the line with up to 5 '#' symbols. More hashes means smaller heading.
# Main Heading
```
# Main Heading
```

## Sub-Heading
```
## Sub-Heading
```

### Smaller Heading
```
### Smaller Heading
```

#### Even Smaller Heading
```
#### Even Smaller Heading
```

##### Smallest Heading
```
##### Smallest Heading
```

And Normal

### Paragraphs
This line has two spaces at the end so that the next line will start a new paragraph.  
Isn't that nice?

This line just has a carriage return at the end
so even though it's a separate line, it just gets shoved on the end of the last line.

However, if you don't want to do the weird two space thing,

Github lets you just add a blank line....

### Style
**Let's do some BOLD by using two asterisks to encapsulate the text**
```
**Let's do some BOLD by using two asterisks to encapsulate the text**
```

*And some italics with a single asterisk before and after*
```
*And some italics with a single asterisk before and after*  
```

### Code
This is fun. Here's a command in-line using backticks: `df -h`
```
This is fun. Here's a command in-line using backticks: `df -h`
```

And here we have a block of code using three backticks:
```
for i in {1..10}; do
  echo "I'm only going to eat $i pringles"
done

echo "Oops. I'm out of pringles..."
```

\`\`\`  
for i in {1..10}; do  
  echo "I'm only going to eat $i pringles"  
done  

echo "Oops. I'm out of pringles..."  
\`\`\`

### How about some lists?
Start the line with asterisk and space for bullets. Number, period, then space for numbered lists.

**Bullet point list:**
* First Point
* Second Point
* Third Point
```
* First Point
* Second Point
* Third Point
```

**Numbered List**
1. Item one
2. Item two
3. ???
4. Profit
```
1. Item one
2. Item two
3. ???
4. Profit
```

### Blockquotes
Start a line with the '>' symbol to make a block quote.
> If you've got a lot to say but you didn't say it, put it in a blockquote.  
>   -Mark Twain
```
> If you've got a lot to say but you didn't say it, put it in a blockquote.  
>   -Mark Twain
```

### Horizontal Rules
---
Break stuff up with three dashes
```
---
```
___
Three underscores
```
___
```
***
Or even three asterisks
```
***
```

### Links
[Put brackets around the text you want to display, followed by the link in parentheses](github.com/jeremiahharmon/html5-practice)
```
[Put brackets around the text you want to display, followed by the link in parentheses](github.com/jeremiahharmon/html5-practice)  
```
If you want the link to just show the address itself, use these guys: '<' and '>'. That way you can avoid all the syntax.

Like this: <https://www.github.com/jeremiahharmon/html5-practice>
```
Like this: <https://www.github.com/jeremiahharmon/html5-practice>
```

### Images
Same syntax as links but with an exclamation point **preceding** it.  
![](https://www.github.com/unicorn.png)
```
![](https://www.github.com/unicorn.png)
```

### Quick notes
Backslash escape as is the standard.
