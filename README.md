# Readme Helper

Snippets for [Sublime Text](http://www.sublimetext.com/) to speed up the process of writing Markdown-formatted Readme files.

## Installation

### Package Control

1. Make sure you already have [Package Control](http://wbond.net/sublime_packages/package_control/) installed
2. Choose *Install Package* from the Command Palette (`Ctrl+Shift+P` on Windows and Linux, `⇧⌘P` on OS X)
3. Select *Readme Helper* and press `Enter`

### GitHub

1. Change to your Sublime Text `Packages/User` directory
2. Clone repository `git clone https://github.com/idleberg/Readme-Helper.git`

### Manual installation

1. Download the files using the GitHub .zip download option
2. Unzip the files to your Sublime Text `Packages/User` directory

## Usage

By default, command completion should be enabled in all Sublime Text versions. If the completion popup doesn't show while typing one of the following commands, you can force showing it using `Ctrl+Space` or by adding the Markdown scope (text.html.markdown) to your user settings under `auto_complete_selector`. Most of the included snippets are limited to the Markdown scope, the text-only licenses are also available for plain text files.

All command completions are prefixed with `rm`. Thanks to Sublime Text fuzzy search, you can use shortcuts such as `rmtip` to trigger `rm:gittip` or `rmsf` to trigger `rm:sourceforge`.

See below for a full list of available commands.

### Scaffolding

`rm:sublime`
instructions for Sublime Text Package Control

`rm:node`
(very basic) instructions for the Node Package Manager

### Snippets

#### Licenses

`rm:apache`  
[Apache License, Version 2.0](http://opensource.org/licenses/Apache-2.0)

`rm:bsd2`  
[BSD 2-Clause License](http://opensource.org/licenses/BSD-2-Clause)  

`rm:bsd3`  
[BSD 3-Clause License](http://opensource.org/licenses/BSD-3-Clause)

`rm:ccby3`  
[Creative Commons Attribution 3.0 Unported License](http://creativecommons.org/licenses/by/3.0/)

`rm:cc0`  
[Creative Commons CC0 1.0 Universal](http://creativecommons.org/publicdomain/zero/1.0/legalcode)

`rm:ccby4`  
[Creative Commons Attribution 4.0 Unported License](http://creativecommons.org/licenses/by/4.0/)

`rm:ccbync3`  
[Creative Commons Attribution-NonCommercial 3.0 Unported License](http://creativecommons.org/licenses/by-nc/3.0/)

`rm:ccbync4`  
[Creative Commons Attribution-NonCommercial 4.0 Unported License](http://creativecommons.org/licenses/by-nc/4.0/)

`rm:ccbyncnd3`  
[Creative Commons Attribution-NonCommercial-NoDerivs 3.0 Unported License](http://creativecommons.org/licenses/by-nc-nd/3.0/)

`rm:ccbyncnd4`  
[Creative Commons Attribution-NonCommercial-NoDerivs 4.0 Unported License](http://creativecommons.org/licenses/by-nc-nd/4.0/)

`rm:ccbyncsa3`  
[Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License](http://creativecommons.org/licenses/by-nc-sa/3.0/)

`rm:ccbyncsa4`  
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 Unported License](http://creativecommons.org/licenses/by-nc-sa/4.0/)

`rm:ccbynd3`  
[Creative Commons Attribution-NoDerivs 3.0 Unported License](http://creativecommons.org/licenses/by-nd/3.0/)

`rm:ccbynd4`  
[Creative Commons Attribution-NoDerivs 4.0 Unported License](http://creativecommons.org/licenses/by-nd/4.0/)

`rm:ccbysa3`  
[Creative Commons Attribution-ShareAlike 3.0 Unported License](http://creativecommons.org/licenses/by-sa/3.0/)

`rm:ccbysa4`  
[Creative Commons Attribution-ShareAlike 4.0 Unported License](http://creativecommons.org/licenses/by-sa/4.0/)

`rm:afferogpl3`  
[GNU Affero General Public License 3.0](http://opensource.org/licenses/AGPL-3.0)

`rm:gpl2`  
[GNU General Public License 2.0](http://opensource.org/licenses/GPL-2.0)

`rm:gpl3`  
[GNU General Public License 3.0](http://opensource.org/licenses/GPL-3.0)

`rm:lgpl2`  
[GNU Lesser General Public License 2.1](http://opensource.org/licenses/LGPL-2.1)

`rm:mit`  
[The MIT License](http://opensource.org/licenses/MIT)

`rm:zlib`  
[The zlib/libpng License](http://opensource.org/licenses/Zlib)

#### Badges

`rm:codeclimate`  
inserts a [Code Climate](https://coveralls.io) badge

`rm:coveralls`  
inserts a [Coveralls](https://coveralls.io) badge
![Coverage](https://s3.amazonaws.com/assets.coveralls.io/badges/coveralls_100.png)

`rm:bitdeli`  
inserts a [BitDeli](https://bitdeli.com) badge
[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/idleberg/readme-helper/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

`rm:david`  
inserts a [David](https://david-dm.org/) badge
![devDependency Status](https://david-dm.org/idleberg/Readme-Helper/dev-status.png)

`rm:flattr`  
inserts a [Flattr](http://flattr.com) badge
![Flattr this](https://api.flattr.com/button/flattr-badge-large.png)

`rm:flattr_icon`  
inserts a [Flattr](http://flattr.com) icon
![Flattr this](https://flattr.com/_img/icons/flattr_logo_16.png)

`rm:gem`  
inserts a [Gem](http://badge.fury.io/) version badge
![gem version](https://badge.fury.io/rb/gem.png)

`rm:grunt`  
inserts a [Grunt](http://gruntjs.com/) badge
[![Built with Grunt](https://cdn.gruntjs.com/builtwith.png)](http://gruntjs.com/)

`rm:follow`  
inserts [GitHub Follow](http://ghbtns.com/) button
<iframe src="http://ghbtns.com/github-btn.html?user=idleberg&type=follow" allowtransparency="true" frameborder="0" scrolling="0" width="132" height="20"></iframe>

`rm:follow_count`  
inserts [GitHub Follow Count](http://ghbtns.com/) button
<iframe src="http://ghbtns.com/github-btn.html?user=idleberg&type=follow&count=true" allowtransparency="true" frameborder="0" scrolling="0" width="165" height="20"></iframe>

`rm:fork`  
inserts [GitHub Fork](http://ghbtns.com/) button
<iframe src="http://ghbtns.com/github-btn.html?user=idleberg&repo=Readme-Helper&type=fork" allowtransparency="true" frameborder="0" scrolling="0" width="53" height="20"></iframe>

`rm:fork_count`  
inserts [GitHub Fork Count](http://ghbtns.com/) button
<iframe src="http://ghbtns.com/github-btn.html?user=idleberg&repo=Readme-Helper&type=fork&count=true" allowtransparency="true" frameborder="0" scrolling="0" width="95" height="20"></iframe>

`rm:star`  
inserts [GitHub Star](http://ghbtns.com/) button
<iframe src="http://ghbtns.com/github-btn.html?user=idleberg&repo=github-buttons&type=watch" allowtransparency="true" frameborder="0" scrolling="0" width="62" height="20"></iframe>

`rm:star_count`  
inserts [GitHub Star Count](http://ghbtns.com/) button
<iframe src="http://ghbtns.com/github-btn.html?user=idleberg&repo=Readme-Helper&type=watch&count=true" allowtransparency="true" frameborder="0" scrolling="0" width="110" height="20"></iframe>

`rm:star_large_count`  
inserts [GitHub Large Star](http://ghbtns.com/) button
<iframe src="http://ghbtns.com/github-btn.html?user=idleberg&repo=Readme-Helper&type=watch&count=true&size=large" allowtransparency="true" frameborder="0" scrolling="0" width="170" height="30"></iframe>

`rm:gittip`  
inserts a [Gittip](http://gittip.com) badge
![Gittip](https://raw.github.com/gittip/www.gittip.com/master/www/assets/gittip.png)

`rm:paypal`  
inserts a [PayPal](http://paypal.com) badge
![Donate](https://www.paypalobjects.com/WEBSCR-640-20110429-1/en_US/i/btn/btn_donate_SM.gif)

`rm:pypi`  
inserts a [PyPI](http://badge.fury.io/) badge
![npm module](https://badge.fury.io/py/pypi.png)

`rm:npm`  
inserts a [npm](http://badge.fury.io/) badge
![npm module](https://badge.fury.io/js/npm.png)

`rm:travis`  
inserts a [Travis](http://travis-ci.org) badge

#### URLs

`rm:bitbucket_repo`  
link to Bitbucket repository

`rm:googlecode`  
link to Google Code project

`rm:github_repo`  
link to GitHub repository

`rm:github_user`  
link to GitHub user profile

`rm:github_webpage`  
link to GitHub web page

`rm:heroku_webpage`  
link to Heroku web page

`rm:sourceforge`  
link to SourceForge project

## Contributions

If you'd like to contribute to this project, feel invited to commit to this repository!

## License

The MIT License (MIT)

Copyright (c) 2013 Jan T. Sott

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

## Donate

You are welcome support this project using [Flattr](https://flattr.com/submit/auto?user_id=idleberg&url=https://github.com/idleberg/Readme-Helper) or Bitcoin `17CXJuPsmhuTzFV2k4RKYwpEHVjskJktRd`