Here's a quick rundown of GFM:

# \# Header 1 [page title]
## \#\# Header 2 [section title]
### \#\#\# Header 3 [subheading]... etc.

\*\*bold\*\* or \_\_bold\_\_
\*italics\* or \_italics\_
I believe we lack an underline, on Discord it was double-underscore
\~\~strikethrough\~\~
\`code\`
\\ backslashes escape control chars, making them appear normally
[all the above characters are escaped]

\`\`\`[language]
codeblock
\`\`\`

Denote newlines with a blank line in between or two trailing spaces

[i.e.]
```
new

line
```

or

```
new##
line
```

[where \#s represent space chars in the above]

LINKS:
\[square brackets around link text\]\(parentheses around URL\)

Example: `[Here's Google!](https://google.com)` makes
[Here's Google!](https://google.com)

Linking between pages is a little... tricky. If the page is in the same folder
or a subfolder, just use a relative link. For example, say you have the
following:

* pages
** contains `1.md` and `subfolder`
* subfolder
** contains `2.md`

To link to `2.md` from `1.md`, just use `[title](subfolder/2.md)`

To link to `1.md` from `2.md`, though, you need to start at the root.
The root with this software will always be `#!pages`. To link to the homepage
from a subfolder, for example, just type `[title](#!pages/index.html)`. So, to
link from `2.md` to `1.me` would require typing `#!pages/1.md` as the URL.

Finally, please make an effort to keep lines at 80 characters or less, thanks

Feel free to practice at the sandbox if you missed anything. You can also just
look at this page's source to see how it's formatted.

For links, don't worry, you'll get used to them.

[And no, Discord does NOT support titled links, FOR WHATEVER FUCKING REASON.]