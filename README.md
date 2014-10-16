strider-gitlab
==============
This plugin provides seamless integration between [Strider](https://github.com/Strider-CD/strider) and [GitLab](https://github.com/gitlabhq/gitlabhq). It enables
you to add GitLab repositories to Strider and it hooks up necessary webhooks in
order to automatically test on commits.

[![NPM](https://nodei.co/npm/strider-gitlab.png?downloads=true&stars=true)](https://nodei.co/npm/strider-gitlab/)

setup
=====
When you add a gitlab project into strider, in order to checkout your branch
you need to put the strider project public key in a gitlab user ssh keys.

requirements
============
  * Strider 1.4
  * Gitlab 6.2

contributors
============
  * Martin Ericson (http://www.devbox.com)
  * [nodefourtytwo/strider-gitlab](https://github.com/nodefourtytwo/strider-gitlab)
  * [jonlil](https://github.com/jonlil)
  * [edy](https://github.com/edy)

license
=======
The MIT License (MIT)

Copyright (c) 2014 Martin Ericson

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
