# food-app
Ionic Angular Mobile Application

Installation: npm install
Run: ionic serve

Note: when you run the app and run through this problem 
"library: 'digital envelope routines',
[ng]   reason: 'unsupported',
[ng]   code: 'ERR_OSSL_EVP_UNSUPPORTED'"

[ERROR] ng has unexpectedly closed (exit code 1).

Reason: Updated Node.js
Solution: Install another node.js version (preferably 14.0.0 --v) 

Now open cmd and run as admin: nvm list > nvm use 14.0.0

Now run the app again: ionic serve
