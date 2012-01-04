# node-twitter-text

A wrapper for [twitter-text-js][] the official twitter text linkification. 

[twitter-text-js]: https://github.com/twitter/twitter-text-js


## Installation

    $ npm install node-twitter-text


## Usage

Extract screen names:

    var twttrtxt = require('node-twitter-text');
    var usernames = twttrtxt.extractMentions("Mentioning @twitter and @jack");
    console.log(usernames);
    // ["twitter", "jack"]

