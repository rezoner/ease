[DEMO](http://canvasquery.com/playground-ease)

## Usage

```javascript
var value = ease(t, easing);
```

*t* is time from 0.0 to 1.0

## Standard easing equations

```javascript
var value = ease(0.25, "inOutBounce");
```

## Human readable easing notation

See [explanation](http://canvasquery.com/playground-ease)

```javascript
var value = ease(0.25, "0149");
```

## Global scope

If you don't like global scope pollution just skip to the end of file and replace this line with whatever suits you:

```javascript
window.ease = ease;
```

## Just the equations

If you are looking for [one argument equations](https://gist.github.com/rezoner/713615dabedb59a15470) - well you found them.