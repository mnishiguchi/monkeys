# Monkeys
- Simple website about monkeys that has a basic top navbar.
- Plain HTML and CSS only (no js)

## Inspiration
- http://us.billabong.com/
- http://us.billabong.com/tribong/

## Images
- http://imgur.com/gallery/d3vJa1d
- http://imgur.com/gallery/Usarp
- https://www.flickr.com/photos/jonathan-leung/16630462593/

## Information on monkeys
- https://en.wikipedia.org/wiki/Monkey
- https://simple.wikipedia.org/wiki/Monkey
- [Science Kids](http://www.sciencekids.co.nz/sciencefacts/animals/monkey.html)

## Width in percentage
```css
#wrapper {
    width: 80%;
    margin-left: auto;
    margin-right: auto;
}
```

## Responsive column
```html
<div class="column">
    <p>Image title</p>
    <img src="some_url" alt="">
</div>

<div>
    <p>Image title</p>
    <img src="some_url" alt="">
</div>

<div>
    <p>Image title</p>
    <img src="some_url" alt="">
</div>
```

```css
.column {
    width: 33.33%;
    float: left;
    padding: 0 2%;
    box-sizing: border-box;
}
```

```css
/* Include this, at the beginning of the CSS */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

```css
/* To retain the natural size of images in case of using a huge display */
img {
    max-width: 100%;
    height: auto;  /* To ensure that image will distort */
}
```
