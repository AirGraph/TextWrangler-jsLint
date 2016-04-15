# TextWrangler jsLint
Applescript for linting javascript documents in TextWrangler

## Questions and Bug Reports
* mailing list: Victor.Vazin@gmail.com

## Installation
1. Install NodeJS and NPM (https://nodejs.org/en/download/) 
2. Install jslint (https://www.npmjs.com/package/jslint)
```
npm install jslint -g
```
3. Place symbolic link to NodeJS in /usr/bin
```
cd /usr/bin
sudo ln -s /usr/local/bin/node ./node
```
4. Copy jsLint text to Script Editor and save it as jsLint.scpt to
```
~/Library/Application Support/TextWrangler/Scripts
```
5. Launch TextWrangler, open js document, select jsLint in script menu and enjoy...
