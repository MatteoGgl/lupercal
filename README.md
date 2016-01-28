# Lupercal
---
A Ghost theme written for programmers and not heretics/mutants/aliens.

### What?

**Lupercal** is a theme for the blogging platform [Ghost](http://github.com/tryghost/ghost/) written using LESS.
It includes [FontAwesome](http://fortawesome.github.io/Font-Awesome/) for icons and [Prism](http://prismjs.com/) for syntax highlighting.

It was developed on version 0.7.5.

### How?

#### Installation
```
$ cd /directory-you-like-the-most
$ git clone https://github.com/MatteoGgl/lupercal.git
```
or just download the zipped repository.

* Copy the directory ```lupercal``` into ```/ghost-root/content/themes```
* Restart the server
* Go to ```your-blog-address.com/ghost -> Settings``` and select the Lupercal theme.

The ```posts``` folder contains different test posts written in Markdown to test the different aspects of the theme. Remove it if you don't plan to use them.

#### Syntax highlighting
Prism is already configured to be used with:

* Apache Configuration Language
* C-like languages
* Bash
* CSS
* Docker
* Javascript
* Git
* JSON
* LESS
* PHP
* Python

When you want to use syntax highlighting in a post, you must specify the language by starting the code block with the following Markdown:

```markdown
  ```language-xxx
```

### Who?

Lupercal is written by me, @MatteoGgl, in my free time.

### Why?

I wanted to write my own theme + learn LESS + populate my GitHub profile + contribute with something myself.

## Copyright & License

Copyright (c) 2016 Matteo Guglielmetti - Releades under MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Copyright (c) 2013-2016 Ghost Foundation - Released under the MIT license.
