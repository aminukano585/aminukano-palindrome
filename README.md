# Phrase object (with palindrome detector)

This is a sample NPM module created for demonstration purpose.

The module can be used as follows:

```
$ npm install --global aminukano-palindrome
$ nano test.js
let Phrase = require("aminukano-palindrome");
let napoleonsLament = new Phrase("Able was I, ere I saw Elba.");
console.log(napoleonsLament.palindrome());
$ node test.js
true
```

