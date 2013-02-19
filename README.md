Install on Mac OS X
-------------------

First you need Xcode, and the Xcode command line tools. After Xcode install, open Xcode, Preferences, Downloads, Install Command Line Tools.

Install brew from http://mxcl.github.com/homebrew/

```
ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go)"
```

Install Glui and Glew from brew

```
brew install glui
brew install glut
```

Compile using make
```
make
```
