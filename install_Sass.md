## Download Sass globally using this below command:

npm i -g sass

## Ab sass ko use krny k 3 ways hain:

<!-- 01 -->

Aghr tu mai sass ko app.sass extension use krk likhogi tu file k andr ka code kuch essa hoga..
no braket no commas etc..

body 
    padding: 0
    margin: 0

lkin ab browser is file ko essy read ni krskta tu mjy terminal pr command sy isko read krwana pryga like this:

sass -w app.sass -o app.css (ab browser isko read/watch krskyga and it will work good...)