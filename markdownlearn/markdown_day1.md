# markdown day1

# The larget heading (an <h1> tag)

## The second largest heading (an <h2> tag)
### 三级标题(an <h3> tag)
...
###### The 6th largest heading

# Unordered lists
* item
* item
* item

- 列表
- 列表
- 列表

# Ordered lists
You can make an ordered list by preceding list items with a number.
1. Item 1
2. Item 2
3. Item 3

# Code formatting
Inline formats
Use single backticks (`) to format text in a special monospace format. Everything within the backticks appear as-is, with no other special formatting.

Here's an idea: why don't we take `SuperiorProject` and turn it into `**Reasonable**Project`.

# Nested lists
You can create nested lists by indenting list items by two spaces.
1. Item 1
  1. A corollary to the above item.
  2. Yet another point to consider.
2. Item 2
  * A corollary that does not need to be ordered.
    * This is indented four spaces, because it's two spaces further than the item above.
    * You might want to consider making a new list.
3. Item 3

# Multiple lines
You can use triple backticks (```) to format text as its own distinct block
Check out this neat program I wrote:

```
x = 0
x = 2 + 2
what is x
```
#  Links
You can create an inline link by wrapping link text in brackets ( [ ] ), and then wrapping the link in parentheses ( ( ) ).

For example, to create a hyperlink to www.github.com, with a link text that says, Visit GitHub!, you'd write this in Markdown: [Visit GitHub!](https://www.github.com).

链接  [我的github](https://github.com/ronanhardiman/BruceRetrofit)

http://example.com

# day2:
image

![](https://github.com/wangdan/AisenWeibo/raw/master/resource/aisen1.gif)

引用:
```markdown
>引用1
>引用2
>引用3
```
```markdown
*斜体*
**粗体**
```
Both bold and italic can use either a * or an _ around the text for styling. This allows you to combine both bold and italic if needed.

**Everyone _must_ attend the meeting at 5 o'clock today.**

# Strikethrough
GFM adds syntax to create strikethrough text, which is missing from standard Markdown

~~Mistaken text.~~

# Tables

You can create tables by assembling a list of words and dividing them with hyphens - (for the first row), and then separating each column with a pipe |:

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

For aesthetic purposes, you can also add extra pipes on the ends:

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |
Note that the dashes at the top don't need to match the length of the header text exactly:

| Name | Description          |
| ------------- | ----------- |
| Help      | Display the help window.|
| Close     | Closes a window     |
You can also include inline Markdown such as links, bold, italics, or strikethrough:

| Name | Description          |
| ------------- | ----------- |
| Help      | ~~Display the~~ help window.|
| Close     | _Closes_ a window     |
Finally, by including colons : within the header row, you can define text to be left-aligned, right-aligned, or center-aligned:

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |
A colon on the left-most side indicates a left-aligned column; a colon on the right-most side indicates a right-aligned column; a colon on both sides indicates a center-aligned column.


# 代码
```java
public static void main(String[] args){
      System.out.println("hello world");
}
```
