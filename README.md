# TheGoodData

TheGoodData is a service that helps users regain and enjoy ownership of their own data. Currently it helps users harvest, secure, process and trade their browsing data and use it for a good cause. It is expected to cover in the future additional types of data besides browsing.

TheGoodData is more than a technology or a service, but a new way to approach data ownership issues in a truly open and collaborative way. In order to achieve it, ownership of TheGoodData company is vested in its users.

For more info about TheGoodData, please visit our site and FAQs

## Dev HOWTO

0. Fork this repository.
1. Switch to your working directory of choice.
2. Clone the development repo:
3. git clone git@github.com:thegooddata/extension.git

## In Chrome

0. Go to the Chrome menu > Tools > Extensions.
1. Check Developer mode then press Load unpacked extension... .
2. Find your working directory.
3. To test after you make a change, be sure to expand the extension listing then press Reload.
4. Push your changes.
5. Send us pull requests!

## How to change extension environment

There is a variable that tells the extension what settings to load depending on the case.

By default the extension works in "production" mode, with the official production API.

In order to make it work in "development" mode to se debugging info in console, or to make 
it work with the API of a local version of the webapp you must do the following:

After loading the unpacked extension, open the console/debug window and type: 

    localStorage.TGD_ENV='dev';

List of environments are: dev, pre, prod, but more could be added if there is a special requirement.

Once changed you sould reload and disable/enable the extension to make sure the new environment is active.

## Software used

These libraries are bundled with the project and needn’t be updated manually:

0. jQuery
1. port.js
2. sitename.js
3. favicon.js

## License

Copyright 2014 The Good Data Cooperative, Ltd.

Copyright 2010–2014 Disconnect, Inc.

This program is free software, excluding the brand features and third-party portions of the program identified in the “Exceptions” below: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.
Exceptions

TheGoodData logos, trademarks, domain names and other brand features or design elements used in this program cannot be reused without express written permission and no license is granted thereto.

Further, the following third-party portions of the program and any use thereof are subject to their own license terms as set forth below:

0. Proxima Nova Soft replaces system fonts and is the valuable copyrighted property of MyFonts, and/or their suppliers. You may not attempt to copy, install, redistribute, convert, modify, or reverse engineer this font software. Please contact MyFonts with any questions. Proxima Nova Soft can be removed and will be replaced with a system font.

