# Class 4

It's important to understand how to navigate HTML directories so that we know how to send users to the correct parts of our website.

Functions provide flexibility and the ability to write reusable code.

## Links/Directory Structure

Use the absolute URL for the value of an href attribute in html when linking to a different site.

You can use a relative URL there instead if the link leads to another page within your own site.

The main homepage of a website written in HTML is called index.html.  If no file name is specified then this is usually the defualt page that a browser will direct you to.

i.e. example.com will bring you to example.com/index.html

Each subdirectory for a website usually also has an index.html for the homepage of that portion of the website.

If you're linking to a page on yourwebsite that's in a different folder, then you must include the file path in your relative URL.

i.e. /examplefolder/index.html

or

../examplefolder/index.html

If you want your link to open a new window in the user's browser, use this:

`target="_blank"`

in the anchor tag as an additional attribute/value.

Typically it is only reserved for something like opening a link to a new website.

## Layout

CSS oranizes elements as building blocks.

Block-Level Elements generally will create a new block (inside of a containing block) on a new line.

i.e. `<ul>` or `<p>`

Inline Elements will flow inside of whatever existing block they're inserted into.

i.e. `<b>` or `<img>`

The positioning of these blocks can be controlled with positioning schemes.

## Functions

Functions can be written to allow you to perform some action, and they can be reused as much as you want to without rewriting the needed steps.

Anonymous functions that have no name can be automatically called by the interpreter when it reads them. 

Functions can also take in information as arguments and return information outside of the function.

## Pair Programming

The practice of having two developers work on one thing together.

One works as "the driver" while the other is "the navigator." 

In this case the driver is the one that actually types the code and manages the files.

The navigator considers how to convert a concept into code, checks for errors in the driver's code, and thinks about what task to tackle next.  But they don't touch the code at any time.

