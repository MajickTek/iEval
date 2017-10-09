# iEval
The iEval JavaScript Highlighting Specification

RTF binary format, created on macOS. If you need raw text with identical colors, view http://majicktek.blogspot.com/2016/12/majick-tek-ieval-syntax-highlighting.html .

## Raw Text below (uncolored; MarkDown does not automatically color text):

iEval Syntax Highlighting Specification.rtf:

This document is property of Majick Tek (http://majicktek.000webhostapp.com) and can only be used as a guide for syntax highlighting.

Keywords should always be this pink color: var. This symbolizes the meaning of the keyword, as all the other colors do.

A variable itself, global or not, should be represented as a light blue in Italics, like so: myVar.

Functions should be depicted as in the following:
Light red name (myFunc)
Parentheses, +, -, /, and others in normal black
Semicolon (if present) in normal black.

Strings should be in a light green color like so: “A \n String"

Comments, no matter what kind, should be in a light gray: //Small Comment /* Big Comment */
If a comment contains code (like in the example below), the style will NOT change, except for variables. Variables MUST be in Italics when referenced in a comment.

Combining these color specs, here is a code example:
var alerttext = prompt("Name:"); alert("Hello, "+alerttext+"!"); /* Creates a variable named allerttext which stores the contents of a prompt. The result is then printed after “Hello, “ and before “!” */

These specifications will work for similar languages like Java, Python, Ruby, and many others like those.

To make using this specification easier, use an editor that supports external customized styling like Notepad++ for Windows, Notepadqq for Linux or TextWrangler for macOS (or Mac OS X)
