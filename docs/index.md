# BitcoinSViki

<!-- This line should go where you want to put your button -->
<div class="money-button"
  data-to="12873"
  data-amount="2"
  data-currency="USD"
  data-label="Donate"  data-client-identifier="1bb7b64622364fd021fb94c253331c32"data-button-id="1611208325864"
  data-button-data="{}"
  data-type="buy"
></div>
<!-- This line can go anywhere -->
<script src="https://www.moneybutton.com/moneybutton.js"></script>


A First Level Header
===

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

A Second Level Header
---------------------

Now is the time for all good men to come to
the aid of their country. This is just a
regular paragraph.

The quick brown fox jumped over the lazy
dog's back.

<img src="https://wiki.bitcoinsv.io/images/a/aa/Simplified_Payment_Verification.png">

### Header 3

> This is a blockquote.
> 
> This is the second paragraph in the blockquote.
>
> ## This is an H2 in a blockquote
Output:

<h1>A First Level Header</h1>

<h2>A Second Level Header</h2>

<p>Now is the time for all good men to come to
the aid of their country. This is just a
regular paragraph.</p>

<p>The quick brown fox jumped over the lazy
dog's back.</p>

<h3>Header 3</h3>

<blockquote>
    <p>This is a blockquote.</p>

    <p>This is the second paragraph in the blockquote.</p>

    <h2>This is an H2 in a blockquote</h2>
</blockquote>

Some of these words *are emphasized*.
Some of these words _are emphasized also_.

Use two asterisks for **strong emphasis**.
Or, if you prefer, __use two underscores instead__

<p>Some of these words <em>are emphasized</em>.
Some of these words <em>are emphasized also</em>.</p>

<p>Use two asterisks for <strong>strong emphasis</strong>.
Or, if you prefer, <strong>use two underscores instead</strong>.</p>


Unordered (bulleted) lists use asterisks, pluses, and hyphens (*, +, and -) as list markers. These three markers are interchangable; this:

*   Candy.
*   Gum.
*   Booze.


this:

+   Candy.
+   Gum.
+   Booze.


and this:

-   Candy.
-   Gum.
-   Booze.
all produce the same output:

<ul>
<li>Candy.</li>
<li>Gum.</li>
<li>Booze.</li>
</ul>
Ordered (numbered) lists use regular numbers, followed by periods, as list markers:

1.  Red
2.  Green
3.  Blue
Output:

<ol>
<li>Red</li>
<li>Green</li>
<li>Blue</li>
</ol>

```
   print(hello)
```   
```
[] create blog
[] item 2
```


Markdown supports two styles for creating links: inline and reference. With both styles, you use square brackets to delimit the text you want to turn into a link.

Inline-style links use parentheses immediately after the link text. For example:

This is an [example link](http://example.com/).
Output:

<p>This is an <a href="http://example.com/">
example link</a>.</p>
## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

# To add a page
 *curl 'https://jaspervdj.be/lorem-markdownum/markdown.txt' > docs/about.md*