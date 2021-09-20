Web Development

> HTML5 for documents. CSS for style format. Javascript for front end behavior. Jave and database are for servor end. http/TCP/IP are for cybersecurity.

# 1. HTML 5 Learning

> HTML is short for World Wide Web's core markup language. It is semantic-level markup language to gap the hardware discrepancy.

* Multithreading is not consider. Serilizing the executaion of all script expect the Javascript **sharearrarybuffer**.
* Extensibility. class attribute. script type=" " for or server-side script.
* HTML vs XML. DOM.
* Materials:  [HTML5 Standards](https://html.spec.whatwg.org/#introduction)
* Tools 1: [try syntax online](https://www.w3schools.com/tags/tryit.asp?filename=tryhtml_phrase_strong)
* Tool 2: [COnformance check](https://whatwg.org/validator/)

## 1.1. Introduction

1. This is a simple example:

![alt](Fig1.png)

2. **Tags** have to be nested.

```html
<p>This <em>is <strong>correct</strong>.</em></p>
<!--- em is tag for italic. strong is for bold  p is for paragraph h is for heading--->

```
3. **Elements** and **attribute** 

```html
<a href="demo.html">simple</a>
<!--- a is the element. href is the attribute for hyperlink.--->
<input name=address maxlength=200>
<input name=address maxlength='200'>
<input name=address maxlength="200">

```
The attribute value can remain unquoted if it doesn't contain ASCII whitespace or any of " ' ` = < or >. Otherwise, it has to be quoted using either single or double quotes. The value, along with the "=" character, can be omitted altogether if the value is the empty string.

4. DOM(document object model) tree to decribe the html structure.

![](2021-09-20-16-10-31.png)
* head element has a titlle element and text node.
```html
<form name="main">
 Result: <output name="result"></output>
 <script>
  document.forms.main.elements.result.value = 'Hello World';
 </script>
</form>
```
* javascript is used in the script to set form's output to 'Hello World'.

```javascript
var a = document.links[0]; // obtain the first link in the document
a.href = 'sample.html'; // change the destination URL of the link
a.protocol = 'https'; // change just the scheme part of the URL
a.setAttribute('href', 'https://example.com/'); // change the content attribute directly

```
* javascript is a descriptive language, which you basically don't need to think about the memory too much.


```html
<!DOCTYPE html>
<html lang="en">
 <head>
  <title>Sample styled page</title>
  <style>
   body { background: navy; color: yellow; }
  </style>
 </head>
 <body>
  <h1>Sample styled page</h1>
  <p>This page is just a demo.</p>
 </body>
</html>

```
* CSS is for styling! Make it more fancy to look. You can make CSS or javascipt in seperate file or in the same file.

5. [Cybersecurity while HTML SQL Injection](https://www.w3schools.com/sql/sql_injection.asp)
> How to interpret illegal input for servers database?  A piece of string is also a piece of code--> Check each characters one by one.

- Cross-site requrest forgery. HTML forms can be hijacted and send to other orgin. 

6. Run to completion pitfall.
![](2021-09-20-17-04-01.png)

## 1.2
