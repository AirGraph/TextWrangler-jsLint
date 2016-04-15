# TextWrangler-jsLint
Applescript for linting javascript documents in TextWrangler

## Questions and Bug Reports
* mailing list: Victor.Vazin@gmail.com

## Installation
Install NodeJS and NPM (https://nodejs.org/en/download/) 
Install jslint (https://www.npmjs.com/package/jslint)
```
npm install jslint -g
```
Place symbolic link to NodeJS in /usr/bin
```
cd /usr/bin
sudo ln -s /usr/local/bin/node ./node
```
Copy jsLint text to Script Editor and save it as jsLint.scpt to
```
~/Library/Application Support/TextWrangler/Scripts
```
Launch TextWrangler, open js document, select jsLint in script menu and enjoy...

## QuickStart
All available options of jsLint you may place in ~/.jslintrc, for example.
Something like this:
```
{"sloppy":true, "maxerr":9, "terse":true, "white":true}
```

