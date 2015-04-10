<a href="https://github.com/ioflo/ioflo"><img src="https://github.com/ioflo/ioflo/blob/master/docs/images/floscript_logo.png?raw=true" height="25" width="85"></a>

# sublime-floscript
Sublime Text package with syntax highlighting support for [FloScript](https://github.com/ioflo/ioflo).

## Installation

#### Installation from Sublime Text
1. Open [Sublime Text](http://www.sublimetext.com/).
2. Select `Package Control` > `Install Package`. 
3. Search for `FloScript`. Click the FloScript package in the search results.

#### Manual Installation (OS X)
```console
cp floscript.tm* ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/
```

## Building
To build *floscript.tmLanguage* from *floscript.YAML-tmLanguage*:

1. In [Sublime Text](http://www.sublimetext.com/), open *floscript.YAML-tmLanguage*.
2. Select `Tools` > `Build`. This should auto-detect the YAML syntax and generate a floscript.tmLanguage file in Property List (XML) format.

To install, see Manual Installation instructions (above).
