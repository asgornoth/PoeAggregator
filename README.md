# PoeAggregator

Installation

Go to https://github.com/cpieprzak/PoeAggregator/releases
Download the PoeAggregator.Setup.<version number>exe

Once installed, click the "Settings" button.

poesessionid must be set in order to run live searches.


To compile:

# for use in npm scripts
npm install electron-packager --save-dev

# for use from cli
npm install electron-packager -g

electron-packager ./ PoeAggregator --platform=win32 --arch=x64