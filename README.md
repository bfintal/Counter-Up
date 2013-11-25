Counter-Up
==========

Counter-Up is a jQuery plugin that *animates* a number from zero (counting up towards it). It supports counting up:

* integers `12345`
* floats `0.1234`
* numbers with commas `1,234,567.00`

*Requires [waypoints.js](http://imakewebthings.com/jquery-waypoints/)*

Demo
====

**[DEMO](http://bfintal.github.io/Counter-Up/demo/demo.html)**

Usage
=====

**HTML**

```
<span class="counter">1,234,567.00</span>
```

**jQuery**

```
$('.counter').counterUp();
```

**Extra parameters**

```
$('.counter').counterUp({
    delay: 10,
    time: 1000
});
```

Social Stuff
============

Twitter: [@bfintal](https://twitter.com/bfintal) & [@gambitph](https://twitter.com/gambitph)

Google+: <a href='https://plus.google.com/113101541449927918834' rel='author'>+Benjamin Intal</a>
