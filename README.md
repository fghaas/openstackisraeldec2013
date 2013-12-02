# Greetings from Havana
## A fresh perspective on globally distributed OpenStack

Florian Haas
OpenStack Israel
December 9, 2013

These slides rely on reveal.js and qrcode.js, which they expect to be
checked out into sibling directories named `reveal.js` and `qrcodejs`,
respectively.

In other words, after you clone _this_ repository, make sure you do
the following:

    cd ..
    git clone git://github.com/hakimel/reveal.js
	git clone git://github.com/davidshimjs/qrcodejs

Then, change back into your checkout of _this_ repository, and run

    make

... to create symlinks to required `reveal.js` and `qrcodejs` CSS and
JavaScript files.

If you chose to clone `reveal.js` or `qrcodejs` somewhere else, run

    make REVEAL=/path/to/reveal.js

or

    make QRCODE=/path/to/qrcodejs

instead.

Then, just open `index.html` (from this repo) in your favorite browser.
We've found Chrome/Chromium to work best; in Firefox the transitions and
animations can be a bit jerky at times.

If you want to try out a different reveal.js theme or transition type,
feel free to specify them by adding `theme` and/or `transition`
parameters in your browser's address bar, like so:

    index.html?theme=sky&transition=concave

Oh, and please don't even ask about IE, thank you.

This content is under the Creative Commons Attribution-ShareAlike 3.0
(CC-BY-SA 3.0) license. Thus, feel free to reuse the content, but do
remember to state your source, provide a URL to the original, and make
your own modifications available under a compatible license.
