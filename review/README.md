Looks good. Nice work on the Agile stuff.

On your HTML, please don't rely on word wrap. Keep your line lengths to 80 characters as much as possible. With HTML, you sometimes need longer lines. With JavaScript, you should never really need 80 characters let alone more. Also, note that you must enclose *each* paragraph in `<p></p>` tags. See below:

So instead of this:

```html
<p>The HTML Article Element (&lt;article&gt;) represents a self-contained composition in a document, page, application, or site, which is intended to be independently distributable or reusable (e.g., in syndication). This could be a forum post, a magazine or newspaper article, a blog entry, an object, or any other independent item of content. Each &lt;article&gt; should be identified, typically by including a heading (h1-h6 element) as a child of the &lt;article&gt; element.
  Content categories: FLow content, sectioning content, palpable content.
</p>
```

Try this:

```html
<p>
  The HTML Article Element (&lt;article&gt;) represents a self-contained
  composition in a document, page, application, or site, which is intended to be
  independently distributable or reusable (e.g., in syndication). This could be
  a forum post, a magazine or newspaper article, a blog entry, an object, or any
  other independent item of content. Each &lt;article&gt; should be identified,
  typically by including a heading (h1-h6 element) as a child of the
  &lt;article&gt; element.
</p>

<p>
  Content categories: FLow content, sectioning content, palpable content.
</p>
```

On pairing, were you able to pair with Anna? How did it go?

Your JS looks good. Did you test this in the REPL? Make sure you do.

One comment on style: We're following the [standard.js](http://standardjs.com/) style guide in Phase 0. Please indent your code 2 *space* inside of any block. So your `s2.js` file should look like this:

```js
function avg (a, b) {
  return (a + b) / 2
}

function avgOfThree (a, b, c) {
  return (a + b + c) / 3
}

function isOdd (x) {
  return (x % 2)
}

```

Please use spaces after commas, spaces around operators, and blank lines between definitions. You'll see all sorts of other variations out there, but for most jobs they will have a set style they expect everyone to use, so don't get too attached to any one style. We've picked this one because it's a good one, but also because it's not one with which most programmers are familiar (it's new), so everyone will have to adapt.

Nice work on the user-centered design and usability stuff. As you learn more about these topics, you'll discover that the Web is full of examples of terrible usability. Knowing the rules for good usability and accessibility will put you head and shoulders above the average programmer/web developer.

Keep up the good work. Ask questions on Slack if you have any.
