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

<!-- 03 -->

This way is used and preferabble with React...

And isklye install command will be :

npm i sass krogi tu React ki pkg.json ki file mai automattically install o jyega..

<!-- Use sass extension vs scss -->

Use sass:
aghr tu mai app.sass fil use krti o tu iska syntax basically python ki trhan hota hai and it works like python mtlb parent phr child 1 khali space sy b code error dedeta hai..

islye i will use scss:
and ismai me css ki trhan code likh skti hon...