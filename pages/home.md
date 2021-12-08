
Scott Ledgerwood

# WebXR

# WebXR - Bablyon.js
The [`department.json`](#/dept) file configures the header and footer - you should not need to change it.

The [`site.json`](#/site) file configures your site content and navigation.
It contains:
* name of the site.
* a list of markdown pages and links to render and create navigation.

The `pages` element of the [`site.json`](#/site) file is a `[list]` of `{objects}`.
Objects contain `name:value` pairs providing the information needed to create the navigation and render the file content.
* **type** is `page`, `card`, `text`, or `link`.
* **title** is placed in the gray bar at the top of rendered page, card, and text items as well as the vertical menu.
* **menu** is placed in the horizontal menu bar and is much shorter than the title, usually a single word.
* **file** is the location of the file containing markdown content to render for `page`, `card`, and `text` items.
* **url** is the URL associated with the menu for `link` items, no page is rendered.

You can learn more about this file type at [JSON Introduction](https://www.w3schools.com/js/js_json_intro.asp).
You can verify the format of the file with [JSON Lint](http://jsonlint.com) if you are having problems.

# WebXR - Hardware Modalities
One of the benefits to 


# Study Results 
All page content is written in markdown format and given the `.md` extension.
Compare the [**Page**](#/page) and [**Card**](#/card) pages with the [**Text**](#/text) page or the [`markdown.md`](#/markdown) file to learn more about how markdown is rendered differently on this site based on the [`site.json`](#/site) type settings.
Compare the [**Faculty**](#/faculty) and [**Course**](#/course) pages with the [`faculty.md`](#/faculty) and [`course.md`](#/course) files for more examples.

Good markdown tutorials include:
* [Basic writing and formatting syntax](https://help.github.com/articles/basic-writing-and-formatting-syntax/)
* [Mastering Markdown](http://guides.github.com)
* [Markdown Syntax](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

