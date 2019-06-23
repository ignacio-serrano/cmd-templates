CMD Scripting Templates
=======================

A collection of files to quickly start CMD scripting projects. After copying 
one of the subdirectories, look for all instances of `${` and replace them with
whatever is described within.

TODO:
-----
  * Incorporate the `manual-test.bat` file and its dependencies to the 
    `program` template.
  * Update the `install.bat` of `program` template, with the changes introduced
    in `bpp` project. It is more generic.

Project layout
--------------
  * `program`: Template for new programs.

---
Below, a markdown cheatsheet.

Heading
=======
Sub-heading
-----------
### Another deeper heading

---

Paragraphs are separated
by a blank line.

Two spaces at the end of a line leave a  
line break.

Text attributes _italic_, *italic*, __bold__, **bold**, `monospace`.

Bullet list:

  * apples
  * oranges
  * pears

Numbered list:

  1. apples
  2. oranges
  3. pears

A [link](http://example.com).

```javascript
function {
  //Javascript highlighted code block.
}
```

    {
    Code block without highlighting.
    }
