---
title:  "Useful Jupyter tips"
date: 2020-07-01
---

This post provides a short intro on picking up useful Jupyter hacks. We begin with a short overview of the most essential Jupyter shortcuts and skills. If you have not read the introduction to Jupyter you should do that immediately, see [here](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook).

## Keyboard short cuts

Editing and executing cells
- enter edit mode: click inside the cell or press `ENTR`
- exit edit mode: click outside cell or press `ESC`.
- executing code within a cell is `SHFT`+`ENTR` or `CTRL`+`ENTR` (not same!)

Adding removing cells (command mode only)
- delete a cell:`d`,`d` (press `d` twice)
- add cell: `a` above, `b` below

Converting between markdown and code (command mode only)
- as markdown: `m`
- as code: `y`

Cutting, copying and pasting cells (command mode only).
- cut cell(s): `x`
- copy cell(s): `c`
- paste cell(s): `v`


Tip: you can select multiple cells at once by holding shift and using mouse / arrow keys.

See all Jupyter keyboard shortcuts in menu (top): `Help > Keyboard Shortcuts`, or press `H` in command mode.

## Other tips

*Autocompletion*

Within Jupyter the `TAB` command will autocomplete your code. This can also be used to see which methods are available for a given object.

*Plotting*

Using the syntax `%matplotlib inline` allows you to make figures within Jupyter notebook.

*Function description*

Execute a cell with `?fct` will give you information about the function `fct`. Note this command also work on objects' methods.


## Further resources

DataCamp has some excellent resources for picking up additional Jupyter skills. Their cheatsheet, available [here](
https://www.datacamp.com/community/blog/jupyter-notebook-cheat-sheet), is excellent to print out and have is a coding aid. For a comprehensive overview of Jupyter to check out the official documentation, [see here](http://jupyter.readthedocs.io/en/latest/).

If you have other relevant stuff that you wish to share, make a pull request in our course page's [GitHub repo](https://github.com/abjer/sds).
