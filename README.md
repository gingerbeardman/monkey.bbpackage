monkey.bbpackage
================

This package lets you to use the Mac OS X editor [BBEdit](http://www.barebones.com/products/bbedit/) as an IDE for the [monkey programming language](http://www.monkeycoder.co.nz).

Created by Matt Sephton, [http://www.gingerbeardman.com/monkey/](http://www.gingerbeardman.com/monkey/)

## Features

**Syntax Colouring**  
Easily see the difference between keywords, constants, strings and comments

**Easy Source Navigation**  
Navigate around your source using the index of functions, classes and methods

**Auto Completion of Keywords**  
Pause whilst typing a keyword to see a list of matches for you to choose from

**Context Sensitive Help**  
View the monkey module docs in your web browser by using the context menu "Find in Reference" on any keyword

**Build/Run scripts**  
Quick and easy full build, or a quicker update and run using scripts

**Configurable Shortcut Keys**  
...and more!

## To do
* Build System Scripts (Build, Update & Run)
* Clippings (code snippets)
* ctags?

## Installation

    $ cd Library/Application\ Support/BBEdit/
    $ mkdir Packages # if it doesn't already exists
    $ cd Packages
    $ git clone https://github.com/bbedit/monkey.bbpackage.git

And restart BBEdit.

## Color Scheme
As a nice little bonus, I've also converted my preferred theme to a BBEdit Color Scheme:  
[https://github.com/gingerbeardman/Monokai-BBEdit-Color-Scheme](https://github.com/gingerbeardman/Monokai-BBEdit-Color-Scheme)

## TextWrangler
If you don't own BBEdit but fancy trying some of the functions of this package, give TextWrangler a whirl.

[https://github.com/gingerbeardman/monkey.textwrangler](https://github.com/gingerbeardman/monkey.textwrangler)

## License
monkey.bbpackage is made available under a [Creative Commons Attribution-Share Alike 3.0 Unported License](http://creativecommons.org/licenses/by-sa/3.0).

## Support
You can talk about the package on the [official monkey forum](http://www.monkeycoder.co.nz/Community/posts.php?topic=1320)

## Requirements
- BBEdit [http://www.barebones.com/products/bbedit/](http://www.barebones.com/products/bbedit/)
- monkey [http://www.monkeycoder.co.nz](http://www.monkeycoder.co.nz)

## Changelog

2012-05-04  
- Added DrawPoint (v50)  

2011-10-08  
- Added FirstNode, LastNode, NextNode, PrevNode, Exp (v45c)  
- Added DisableKeyboard, EnableKeyboard (v45)  
- Added ACosr, ASinr, ATan2r, ATanr, Cosr, Sinr, Tanr (v44)  
- Added DrawPoly (v43)  
- Added App: UpdateRate  
- Added Audio: music commands (v35), Discard  
- Added Graphics: DeviceHeight, DeviceWidth, Frames, HandleX, HandleY, Height, Width  
- Added Lang: Print, Length, Resize, Compare, ToLower, ToUpper, Trim  
- Added List: Backwards, Clear, Count, First, IsEmpty, Last, LastNode, ObjectEnumerator, RemoveFirst, RemoveLast, Value, ToArray  
- Added Map: Set, Values, Key  
- Added Random: Seed  
- Added Set: Insert  
- Added Stack: Insert, Pop, Push, Top  
