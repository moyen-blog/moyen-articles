# Info

See [GitHub Flavored Markdown (GFM) spec](https://github.github.com/gfm/).

# Text Wall

HugewordherewithnospacesorotherwhitespacetospeakofweshallseehowitisdisplayedandwhetheritcompletelyfucksupmybeautifulstylingthatIhaveinvestedsolittletimeintowellthatoughtadoitkbye.

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Turpis nunc eget lorem dolor sed viverra ipsum nunc. Eget nullam non nisi est sit amet. Euismod lacinia at quis risus sed vulputate odio. Sodales ut eu sem integer vitae justo eget magna fermentum. Vel facilisis volutpat est velit egestas dui. A cras semper auctor neque vitae. Lectus proin nibh nisl condimentum id venenatis a condimentum vitae. Diam vel quam elementum pulvinar etiam non quam. Porta nibh venenatis cras sed felis eget velit aliquet sagittis. Natoque penatibus et magnis dis parturient montes nascetur ridiculus.

Et tortor at risus viverra adipiscing. Odio ut sem nulla pharetra. Etiam sit amet nisl purus in mollis. Nibh mauris cursus mattis molestie a iaculis at erat. Posuere lorem ipsum dolor sit amet. Varius vel pharetra vel turpis nunc eget. Etiam non quam lacus suspendisse faucibus. Molestie at elementum eu facilisis sed odio morbi quis commodo. Est pellentesque elit ullamcorper dignissim cras tincidunt. Auctor neque vitae tempus quam. Hendrerit dolor magna eget est. Lectus nulla at volutpat diam ut venenatis tellus in. Ac tortor dignissim convallis aenean et tortor at. Cursus euismod quis viverra nibh cras pulvinar mattis nunc sed. Vel pharetra vel turpis nunc eget. Porta lorem mollis aliquam ut porttitor leo a diam. Egestas congue quisque egestas diam in arcu cursus euismod.

Ultricies mi quis hendrerit dolor magna eget est lorem ipsum. Commodo odio aenean sed adipiscing diam donec adipiscing. Sed turpis tincidunt id aliquet. Erat nam at lectus urna. Quisque sagittis purus sit amet volutpat. Tempor orci dapibus ultrices in iaculis nunc. Condimentum lacinia quis vel eros. Adipiscing vitae proin sagittis nisl rhoncus mattis rhoncus urna. Eget egestas purus viverra accumsan in nisl nisi. Nisl purus in mollis nunc sed id. Sit amet mattis vulputate enim nulla aliquet porttitor lacus. Morbi enim nunc faucibus a pellentesque sit amet. Amet purus gravida quis blandit turpis. Massa id neque aliquam vestibulum. A erat nam at lectus urna duis convallis convallis. Mattis enim ut tellus elementum sagittis. Condimentum id venenatis a condimentum vitae sapien pellentesque habitant morbi. Mauris in aliquam sem fringilla ut morbi tincidunt augue interdum.

---

# Heading H1

## Heading H2

### Heading H3

- # Heading H1 in Unordered List

# Tables

With leading and trailing pipes:

| Column One | Column Two | Column Three | Column Four |
| --- | --- | --- | --- |
| foo | bar | biz | bim |

Many columns and rows mixing narrow and wide headers:

| Column A | Column B | Column C | Column D | Column E is really wide and packs a lot of needless info | F | G | Column H | Column I | Column J |
| -- | -- | -- | -- | -- | -- | -- | -- | -- | -- |
| 0A | 0B | 0C | 0D | 0E | 0F | 0G | 0H | 0I | 0J |
| 1A | 1B | 1C | 1D | 1E | 1F | 1G | 1H | 1I | 1J |
| 2A | 2B | 2C | 2D | 2E | 2F | 2G | 2H | 2I | 2J |
| 3A | 3B | 3C | 3D | 3E | 3F | 3G | 3H | 3I | 3J |
| 4A | 4B | 4C | 4D | 4E | 4F | 4G | 4H | 4I | 4J |
| 5A | 5B | 5C | 5D | 5E | 5F | 5G | 5H | 5I | 5J |
| 6A | 6B | 6C | 6D | 6E | 6F | 6G | 6H | 6I | 6J |
| 7A | 7B | 7C | 7D | 7E | 7F | 7G | 7H | 7I | 7J |
| 8A | 8B | 8C | 8D | 8E | 8F | 8G | 8H | 8I | 8J |
| 9A | 9B | 9C | 9D | 9E | 9F | 9G | 9H | 9I | 9J |

No leading or trailing pipes, defined text alignment:

Left | Center | Right
---- | :----: | ----:
Lots of text in here | And some more over here | Finally, some here
bar  | baz    | bar

Two consecutive small tables:

A | B
--|--
1 | 2

C | D
--|--
3 | 4


# Images

Local image within paragraph: ![Test image](images/150.png) Followed by more text here.

Local large image (should downscale) from subdir, with title, redundant path, space in path (must be enclosed in angle brackets):

![Test image](<images/../images/New York.jpg> "A photo of New York")

Local image, URL-encoded space in path:

![Test image](images/New%20York.jpg)

Local image, no alt text, in link:

[![](images/150.png)](https://wikipedia.org)

Local image, blank title:

![Test image](images/150.png "")

Remote image, title:

![Test image](https://picsum.photos/seed/1/300/150?grayscale "test")

Wide remote image (1200x400):

![Test image](https://picsum.photos/seed/3/1200/400?grayscale)

## Images in a table

With headers:

Column One             |  Column Two
-----------------------|-----------
![Test image](https://picsum.photos/seed/2/600/150?grayscale) | ![Test image](images/150.png)

Empty headers:

|
-----------------------|-----------
![Test image](images/150.png) | ![Test image](https://picsum.photos/seed/2/600/150?grayscale)

# Styling

**Bold.**

*Italic.*

~~Strikethrough.~~

~~***Bold, italic, and strikethrough.***~~

`Inline code.`

Edge case emphasis (precedence test): *foo *bar* baz*

# Characters

Unicode U+0000 (literal `&#0;`): &#0;
U+25ba (literal `&#9658;`): &#9658;
U+0960 (literal `&#2400;`): &#2400;

Weird unicode 🅣🅔🅢🅣

Emoji: 👌😡🧚‍♂️🎅🏾🧘🏽⏰💎🙌🚣🏿‍♀️

# Code Blocks

```
# Language not specified
func something(s string) {
  fmt.Println(s)
}
```

```go
// Golang
func something(s string) {
  fmt.Println(s)
}
```

```javascript
// JavaScript
const something = (s) => {
  console.log(s);
};
```

With really long lines:

```
lsof / | awk '{ if($7 > 1048576) print $7/1048576 "MB" " " $9 " " $1 }' | sort -n -u | tail
find ~ -name ".git" 2> /dev/null | sed 's/\/.git/\//g' | awk '{print "-------------------------\n\033[1;32mGit Repo:\033[0m " $1; system("git --git-dir="$1".git --work-tree="$1" status")}'
clear;while x=0; do clear;date;echo "";echo "  [Count] | [IP ADDR]";echo "-------------------";netstat -np|grep :80|grep -v LISTEN|awk '{print $5}'|cut -d: -f1|uniq -c; sleep 5;done
```

With emoji:

```
// Emojis in code block ✊🏻 🐝 👨🏾 🍀
✌🏿 😇 👺 👨‍👨‍👧‍👧
```

# Block Quotes

> Here's a block quote.

With multiple lines:

>Testing multiple lines using `>` on only the first line.
`Code.` *Bold.* **Italic.** ~~Strikethrough.~~ ~~***Bold, italic, and strikethrough.***~~
Here's some more content.
And now a super long line that will, in all likelyhood, cause a word wrap towards the end (I'm running out of ways to pad this sentence).

Edge case link reference in block quote:

> Blockquote [blockquote].
>
> [blockquote]: https://wikipedia.org

# Lists

Indicators of block structure always take precedence over indicators of inline structure. So, for example, the following is a list with two items, not a list with one item containing a code span:

- `one
- two`

Complex list with embedded blocks:

1.  List item one.

    List item one continued with a second paragraph followed by an
    Indented block.

        $ ls *.sh
        $ mv *.sh ~/tmp

    List item continued with a third paragraph.

2.  List item two continued with an open block.

    This paragraph is part of the preceding list item.

    1. This list is nested and does not require explicit item continuation.

       This paragraph is part of the preceding list item.

    2. List item b.

    This paragraph belongs to item two of the outer list.

Edge case with gap in list:

1. one

2. two
3. three

Edge case with sublist and blank line:

1.  one
    - a

    - b
2.  two

Indented list markers:

 8. item 1
 9. item 2
10. item 2a

With asterisk HR in the middle:

* a
* * * * *
* b

List markers changing midway:

1. fee
2. fie
-  foe
-  fum

Empty list items:

* a
*
* b

## Task List

- [x] Checked
- [ ] Unchecked
- Not a task item
- [x] Another checked
- [-] Invalid task format

Nested task list:

1. One
    - [x] Checked
    - [ ] Unchecked
2. Two

# Links

[Wikipedia](https://wikipedia.org)

Italic links: [*Wikipedia*](https://wikipedia.org) *[Wikipedia](https://wikipedia.org)*

Bold links: [**Wikipedia**](https://wikipedia.org) **[Wikipedia](https://wikipedia.org)**

Bold and italic links: *[**Wikipedia**](https://wikipedia.org)* **[*Wikipedia*](https://wikipedia.org)** ***[Wikipedia](https://wikipedia.org)*** [***Wikipedia***](https://wikipedia.org)

With spaces in file name (must be enclosed in angle brackets): [To Do List Article](<Moyen To Do List.md>)

Leading `./`: [Leading CWD](./Markdown.md)

[Link to Heading](#heading-h1)

Edge case link with backtick (marker precedence test): [a backtick (`)](https://wikipedia.org) and [another backtick (`)](https://wikipedia.org).

## References

Hello, [refA]! With a label [label here][refA].

[refA]: https://wikipedia.org

Edge case duplicate references:

Hello, [refB]!

[refB]: https://wikipedia.org
[refB]: https://google.com

# Breaks

Horizontal rule with dash:

---

HR with asterisk:

* * *
