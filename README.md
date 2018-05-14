# Markup Reference

### Headings
Precede the line with up to 5 '#' symbols. More hashes means smaller heading.
# Main Heading

## Sub-Heading

### Smaller Heading

#### Even Smaller Heading

##### Smallest Heading

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

*And some italics with a single asterisk before and after*  

### Code
This is fun. Here's a command in-line using backticks: `df -h`

And here we have a block of code using three backticks:
```
for i in {1..10}; do
  echo "I did stuff with your mom $i times last night"
done
```

### How about some lists?
Start the line with asterisk and space for bullets. Number, period, then space for numbered lists.

**Bullet point list:**
* First Point
* Second Point
* Third Point

**Numbered List**
1. Item one
2. Item two
3. ???
4. Profit

### Blockquotes
Start a line with the '>' symbol to make a block quote.
> If you've got a lot to say but you didn't say it, put it in a blockquote.  
>   -Mark Twain

### Horizontal Rules
---
Break stuff up with three dashes
___
Three underscores
***
Or even three asterisks

### Links
[Put brackets around the text you want to display, followed by the link in parentheses](github.com/jeremiahharmon/html5-practice)
If you want the link to just show the address itself, use these guys: '<' and '>'. That way you can avoid all the syntax.

### Images
Same syntax as links but with an exclamation point **preceding** it.
![Here's a Unicorn that GitHub provides](https://www.github.com/unicorn.png)

### Quick notes
Backslash escape as is the standard.
