# LittleWriter
Little Writer is a rich text editor for Haiku. It aims to become a well featured word processor for Haiku. Any contribute is very welcome (see the open issues).

Based on TextEdit demo by Digia.
http://doc.qt.io/qt-4.8/qt-demos-textedit-example.html

Requirements:

- a GCC2_Hybrid nighlty image (http://download.haiku-os.org/nightly-images/x86_gcc2_hybrid/)
- libqt4_x86 and libqt4_x86_devel from Haiku Depot

How to build:

 - setarch x86
 - make && addresource.sh

History:

Version 1.1
- Now, from the "File" menu, is possible to choose if to save the document as HTML or as ODT.

Version 1.0
- Added Haiku style Icons (thanks to Zumi http://zumi.xoom.it/myhaiku/)
- Added the ability to insert images inside the document (thanks to hey68you)
- Added the ability to change the background color (thanks to hey68you)
- Added the ability to change the text highlight color (thanks to hey68you)

Issues:

- Currently, Little Writer is not able to open ODT documents; however the ODT documents generated by Little Writer are almost properly displayed by other word processors (like, eg. Libre Office)
