## Introduction

Recently I wrote a post about a simple program I wrote in Ruby to simplify applying Parse through POST, you can find it [here][1].

It was as simpler as filling out a file and execute the program in Ruby. This time it will be even simpler. Just fill out this form and click the "Apply" button.

What do I want to achieve with this?

* Have fun implementing it using HTML5 and JQuery
* Make it easier for you to apply Parse (just my 2 cents to thank them for their wonderful API)

## Applying 

You can apply using this form: http://alberto-villa.com/aparse/apply.html or you may just download the project files and apply using them locally.

## Issues

Performing a Cross-domain POST using AJAX has some problems that need to be solved with some server-side mechanism. As there is no way to make any change on the server, in order to confirm that the POST has been sucessful you should check the browser console in order to verify that the server answer with 200 OK.

[1]: https://github.com/albertovilla/aparse