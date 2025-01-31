## Ab sass ko use krny k 3 ways hain:

<!-- 01 -->

Aghr tu mai sass ko app.sass extension use krk likhogi tu file k andr ka code kuch essa hoga..
no braket no commas etc..

body 
    padding: 0
    margin: 0

lkin ab browser is file ko essy read ni krskta tu mjy terminal pr command sy isko read krwana pryga like this:

sass -w app.sass app.css (ab browser isko read/watch krskyga and it will work good...)


<!-- 02 -->

Install Live Sass Compiler extension from vscode...

And use Ctrl shift P command and write this:

Live Sass: Watch Sass(then watch sass will show in vscode at bottom bar...)
And if we wanna stop watching Sass then we can again use this Ctrl shift P command and 
again write this command:
Live Sass: Watch Sass and click on stop watching Sass then Sass will be stop.

Otherwise I can directly start or atop from terminl at botton bar...
