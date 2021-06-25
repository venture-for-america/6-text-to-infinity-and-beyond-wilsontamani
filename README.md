# Text to Infinity and Beyond

In the previous lesson's video, Flatiron School founder Avi Flombaum stated that
"the entire web is made of of giant strings of HTML." A "string" as he's using
it here is technologist-speak for a series of letters placed one after another.
A less-technical synonym for this idea is "text." HTML stands for *hypertext
markup language* and we will learn about it in this section.

**The texts sent back and forth on the web are HTML documents**. HTML documents
are strings that contain both _content_ and _markup_. Content looks like: `hi
there` and markup looks like `<p>`. In HTML they are blended together so that
the string `<p>hi there</p>` tells the browser to display the words `hi there`
to the screen in whatever a **p**aragraph, according to the browser, looks like.

Here's another fragment of an HTML document:

```html
<h1>About My Poodle</h1>

<p>I have an adorable black poodle named Byron.</p>
```

This document has two "elements" an `<h1>` or "Heading 1" element and a `<p>`
element or "Paragraph" element.

The browser receives, from the server, this HTML document and then uses it to
"draw" a non-markup version in your browser. It drops the HTML elements, but
uses the specification of the _meaning_ of those elements to structure what it
displays on-screen.

A byproduct of a web page being a drawing of an HTML document is that we can
see the drawing (or, "rendered page") **or**, if we're curious, we can see the
HTML document that the browser used to build the rendered page.  Right-click (control + click on a Mac)
anywhere on a webpage, select "View Page Source" and you'll see the HTML
document that the browser used to "render" the website.

Let's peek behind the scenes of two of our favorites websites to see how they
are built: Wikipedia and StackOverflow.

## Seeing the Text Underneath

**Wikipedia's homepage:**

![](https://curriculum-content.s3.amazonaws.com/web-development/wikipedia.jpeg)

**View source on Wikipedia's homepage:**

![](https://curriculum-content.s3.amazonaws.com/web-development/wikipedia-view-source.jpeg)

**Stackoverflow's highest voted questions page:**

![](https://curriculum-content.s3.amazonaws.com/web-development/stackoverflow.jpeg)

**View source on Stackoverflow's highest voted questions page:**

![](https://curriculum-content.s3.amazonaws.com/web-development/stackoverflow-viewsource-updated.jpeg)

Much of that will look like gobbledygook, and that's fine for now, but it's
**HTML** gobbledygook.  Now peek behind your two favorite websites. Visit them
and view their page source. You will see that **behind that product you love
are a collection of HTML text**, or **HTML documents**.

## Resources

- [Wikipedia home page](https://en.wikipedia.org/)
- [StackOverflow Highest Voted Questions page](https://stackoverflow.com/questions?sort=votes)
