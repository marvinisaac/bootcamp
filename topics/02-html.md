# HTML

## Introduction

HTML is the basic structure of a website. It declares ***all*** content displayed inside a page.

## Elements and Tags

All HTML elements are defined with tags that look like this:

```
<h1> Hello, World! </h1>
```

The `<h1>` is what's called as the "opening tag" while the `</h1>` is called as the "closing tag". The text `Hello, World` in between them is the content displayed in the browser.

## HTML Starting Point

Modern websites will always have these lines in their HTML file:

```
<!DOCTYPE html>
<html>
    <head>
        <title>My Website</title>
    </head>

    <body>
    </body>
</html>
```

### The DOCTYPE

```
<!DOCTYPE html>
```

This line tells the browser that the website is using HTML5. Older versions are longer and more complicated. There is also very little chance that you'll need to use them so, moving forward, we'll always use HTML5.

### The HTML Element

```
<html>
    ...
</html>
```

These lines provide the browser with the root element of website. All other elements will be a child or descendant of this root element.

### The Head Element

```
    <head>
        <title>My Website</title>
        ...
    </head>
```

This element will contain information for the browser. Things like the page's title, the location of CSS and JS files, and site meta data will be added here later on.

### The Body Element

```
    <body>
        ...
    </body>
```

This is where the displayed content will be added. All images, links, lists, and text must be put here.
