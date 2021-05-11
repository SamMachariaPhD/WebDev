
## Getting started with HTML

### Documentation/Datasheet

- In programming, it is very important to have a documentation/datasheet
of the language you want to program in.

- For HTML documentation and others, you can visit devdocs.io

### Heading
`
<h1> First heading </h1>
<h6> Last heading </h6>
<h3> Third heading </h3>
<br> break the line (spacing)
`

### Anatomy of HTML tags

1. opening tag. e.g. `<h1>`
2. content. e.g. "First heading"
3. closing tag. e.g. `</h1>`

Some tags are 'self-closing' tags e.g. `<br>`
In this case, the closing tags maybe omitted.
Another example is horizontal rule, `<hr>`

`<hr size="3">`
hr = HTML element
size="3" = HTML attribute

HTML attribute provides more information to the browser.
For example, the 'size="3"' attribute specifies to the browser the size of
the horizontal rule.

To add a comment in html, use `<!-- a comment -->`

### An example

`
<!-- this is just an example -->
<center>
<hr size="3" noshade>
<h1>THE ADVENTURE OF <br> SHERLOCK HOLMES</h1>
<br>
<h3>BY</h3>
<br>
<h2>SIR ARTHUR CONAN DOYLE</h2>
<hr size="3" noshade>
</center>
`

### Interesting

- web.archive.org (way back machine) can show you the history of various websites.
Check the wayBackMachine folder to see snapshot of google.com way back in 1998.

- All these websites were purely HTML and CSS back in those days.

- These kind of websites still exist even with some of the top computer science professors.
e.g. Thomas H. Cormen (MIT), John Kleinberg (Cornell), Donald E. Knuth
Take a look at the SeriousPeople folder.

### HTML personal website

- To start the index.html page in an editor like Atom, use a shortcut such as
typing `html` and then hit Enter key. A sketch code will appear for you to
simply fill spaces. These are parts of code that are usually repeated when
programming. This kind of code is called `the boilerplate code`.

- I think excessive use of the boilerplate code and `auto-complete` can make you a superficial programmer.
More of these shortcuts can be found here [https://docs.emmet.io/cheat-sheet/]

- If your html code is rendered with an unspecified character set,
e.g., a non utf-8 character, you get some unknown characters called `Mojibake`
a Japanese word meaning character transformation. The interpretation should be
done using the specified unicode. If the language typed and the rendering
unicode character set does not match, you will get some Mojibake.

- The description meta tag tells what your website is about.

- `<em>` and `strong` should be used instead of `<i>` and `<b>` the results are
the same. The former is closely related to the structure and semantics while the later is more concerned with how the text looks/style. HTML is more concerned with structure. It is better to leave style to CSS.
