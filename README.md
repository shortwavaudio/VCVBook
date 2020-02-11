# VCVBook - Developing Virtual Synthesizers with VCV Rack - ABC Plugin

<img align="right" width="200" src="cover-small.jpg">
This repository contains material and examples related to the book:
"Developing Virtual Synthesizers with VCV Rack",
edited by Focal Press.
Find the book at:
https://www.routledge.com/Developing-Virtual-Synthesizers-with-VCV-Rack/Gabrielli/p/book/9780367077730

The ABC plugin contains all modules described in the book. You will find all the instructions in the book.
For building ABC, clone this repository and copy the ABC folder in your Rack installation "plugins" folder, i.e.:
```
git clone https://github.com/LOGUNIVPM/VCVBook.git
cp -r VCVBook/ABC <myRackInstallationFolder>/plugins/
cd <myRackInstallationFolder>/plugins/ABC/
```
Now you are ready to build and tweak.

All material is released under a GPLv3 license, except when differently stated.

Please note: these examples are for didactical purposes only. They are not necessarily meant to be efficient or bug-less. The book often provides a discussion on alternative ways to implement things, with pros and cons. Do not learn by Ctrl+C and Ctrl+V! 
Please note: many of my modules will have text labels written in code, not embedded as a path in the SVG file. This made the development of graphics quicker and more repeatable for me. This is not the best way for production, as explained in the book. Follow the Rack guidelines to prepare your SVG file and panel widgets.