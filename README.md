# classic-martinb

A simple Octopress theme. I made some edits to the original classic theme to slim it down a little and add different navigation links.

![classic-martinb theme screenshot](/classic-martinb.png)

## Installation

```shell
$ cd octopress
$ git submodule add git://github.com/fapper/classic-martinb.git .themes/classic-martinb
$ rake install['classic-martinb']
$ rake generate
```

If using zsh, there might by globbing issues running `$ rake install['classic-martinb']`, running `$ rake "install[classic-martinb]"` might be required.

## Customization
You will want to change the text in the footer and right sidebar. These files, among others you may want modify, can be found in the `source/_includes/custom/` directory.

## License
(The MIT License)

Copyright © 2013 Martin Bjeldbak Madsen

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the ‘Software’), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED ‘AS IS’, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

