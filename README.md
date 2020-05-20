# HTML SESSION OF LEARNING

## What is HTML?
> HTML provides a way of disaplaying web pages with test and images or multimedia content. HTML is not a programming language, but a markup language. An HTML file is a text file containing small markup tags.The markup tags tell the Web browser, such as Mozilla Firefox or Google Chrome, how to display the page. An HTML file must have an htm or html file extension. HTML stands for Hyper > Text Markup LAnguage.

##  HTML PAGES ARE OF TWO TYPES:
```
1). STATIC PAGES 
2). DYNAMIC PAGES 
```
 > **Static Pages** - Static Pages, as the name indicates, comprise static content (text and images). 'So you can only see the contents of a web page without being able to have interaction  >  with it

> **Dynamic Pages** - Dynamic pages are those where the content of the web page depend on user input. So interaction with the user is required in order to display the web pages. For example, consider a web page which requires a number to be entered from the user in order to find out if it is even or odd. When the user enters the number and clicks on the appropriate button, the number is sent to the web server, which in turn returns the result to the user in an HTML page.

## Tags and Elements
  > **Tags** - A tag is a bit of text that acts as a point demarcation. To create a tag, HTML gives certain characters special meaning: the angel brackets < and >. <br />
  Putting characters within angle brackets creates > a tag. <br />

> **There are two tags:** <br/>
Start tag or opening tag and End tag or closing tag. An end tag always matches a start tag, expect that it has an extra forward slash after after the opening angle bracket.

```html
 <h1> A heading </h1>
```
  > **Elements** - The combination of a start and tags define an element. Everything between the two tags is referred to as the contents of the elements <br />
>

## Attribute
  > Attributes provide additional information about the contents of an elemnts. They appear on the opening tag of the elements and are made up of two parts:- a name and a value, separated by > equals sign.

```html
 <p lang = "en-us" > Paragraph in English </p>
```
The attribute name indicates what kind of extra information you are supplying about the element's content. It should be written in lowercae.
The value is the information or setting for the attribute. It should be placed in double quotes. Different attributes can have different values.

In this example an attribute callled `lang` is used to indicate tee language used in this elements. The value of this attribute on this page specifies it is in `US English`.

__NOTE__:- HTML5 *allow you to use uppercase attribute names and omit the quote marks, but this is not __recommends__*

## HTML Tag
> `< HTML >` is a starting tag. To delimit the test inside, add a closing tag by adding a forward slash "/" to the starting tag. Most but not all tags have a closing tag. It is necessary to write the code for an HTML page between < HTML > and `< HTML >`. This `</ HTML >` tells the browser is 'this is the start of an HTML document' and `</ HTML >` 'this is the end of an HTML document'.
```html
<html>
  ------------------------------
  ------------------------------
  ------------------------------
</html> 
```

## HEAD Tag
> Before the `< body >` element you will often see a < head > element. This contains information about the page, rather than information that is shown within the main part of the browser. You will usually find a `< title >` ellement inside the < head > element. `< head >` is opening head trg and `</ head >` is closing head tag.
```html
<html>
  <head>
    <title>
      HELLO
    </title>
  </head>
</html>
```
## Title Tag
> The contents of the `< title >` element are either shown in the top of the browser, above where you usually type in the URL of the page you want to visit, or on the tab for that page ( if your browser uses tabs to allow you to view multiple pages at the same time). `< title >` is opening title tag and `</ title >` closing title tag.

```html
<html>
  <head>
    <title>HELLO</title>
  </head>
</html>
```

## Body Tag
> Everything inside this element is shown inside the main browser window. `< body >` is opening body tag `</body>` is closing tag.

```html
<html>
  <head>
    <title>
      HELLO
    </title>
  </head>
  <body>
    <h1>I am heading indide body.</h1>
  </body>
</html>
```

## Type Of Tag

````html
1). Container Tag - Which has opening and closing Tag.
Example:-
<html>-------</html>
<head>-------</head>
<body>-------</body>

1). Empty Tag - Which has opening and closing Tag.
Example:-
<br>
<area>
<base>
<hr>
<img>
<input>
````

## HTML Versions
````html
| Versions   | Year  |
| -------    | ------|
| HTML       | 1991  |
| HTML 2.0   | 1995  |
| HTML 3.2   | 1997  |
| HTML 4.01  | 1999  |
| XHTMl      | 2000  |
| HTML 5     | 2014  |
````
## HTML 5
> HTML 5 enables to create to more interactive website by embedding video, audio and graphics on the web pages.
The purpose of the HTML5 is primarily to make easier for web developers.
````html
New Features:
  1) Browser support
  2) Geolocation
  3) Ofline application cache
  4) Web storage
  5) Error Handing
  6) New Application Programming Interface API
  7) New Structure
````

