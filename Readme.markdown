# MultiMarkdown QuickLook Plugin #

## Introduction ##

This is a complete rewrite of the MultiMarkdown version of Phil Toland's QLMarkdown plugin. 

But in order to fix it, it just made more sense to start over.

This program allows you to preview a MultiMarkdown text file (or OPML file) in the Finder after converting it to HTML with MMD.

## Installation ##

To install, simply put the "MultiMarkdown QuickLook" file in:

	~/Library/QuickLook

To make sure that this version is used, run `qlmanage -r` in the Terminal.

To uninstall, simply remove it, and again run `qlmanage -r`.

This version of the QuickLook plugin includes an embedded copy of MultiMarkdown 5.0.1, as well as `opml2mmd.xslt`.  So there's nothing else to install to get it to work.  The version of mmd that's embedded should run on any Intel Mac.


## Downloads ##


Source code is available at <http://github.com/fletcher/MMD-QuickLook>.

Downloadable binaries are also available: <https://github.com/fletcher/MMD-QuickLook/releases>.


## License ##

The QLMarkdown code is distributed under the MIT License:

MMD 5 is released under the MIT License.


### The MIT License ###

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

## Known Issues ##



## Version History ##

### 5.0.1 - 2015-12-01 ###

* Update embedded MultiMarkdown to version 5.0.1 and synchronize version numbering.
* Tweak Bundle Target properties

