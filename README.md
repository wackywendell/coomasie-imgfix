# coomasie-imgfix

###### *A basic script for increasing legibility of coomassie gels*

This is meant to take images of Coomassie gels, and convert the images from a low-contrast blue to a high-contrast black-and-white.


## Setup

 1. Install Imagemagick (see below)
 2. Create a new folder in your home directory called `coomassie-in`
 3. Put images of your coomassie gels in that folder, assumedly in `jpg` format
 4. Run `imgfix.sh`
 5. Original image will be in `$HOME/coomassie-originals`, with new versions in `$HOME/coomassie-out`
 
### Dependencies

This requires Imagemagick and bash.

##### Imagemagick

On linux, install imagemagick with your package manager. Its almost certainly in the repositories for just about any distribution.

On Macs, I recommend installing [Homebrew](http://brew.sh/), and then installing Imagemagick:

```bash
brew install imagemagick
```

Imagemagick is also available through Macports.

##### Bash

Bash comes on all linux and Mac OS X platforms.

##### Windows

If you're using Windows, I'm sorry, you're on your own.
