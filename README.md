<p align="center">
  ⭐️ If you like Anime.css, give it a star! ⭐️
</p>

<img src="https://github.com/animecss/anime.css/blob/master/static/images/anime.png" align="right" />

# Anime.css

アニメ is a lightweight cross-browser CSS animations library.

## Install

`Anime.css` is available on npm:

```
npm install anime.css --save
```

`Anime.css` is available on yarn as well:

```
yarn add anime.css
```

or add it directly to your webpage:

```
<head>
  <link
    rel="stylesheet"
    href="anime.min.css"
  />
</head>
```

## Usage

Add the class `anime__animated` to an element, along with many of the anime names that staring with the `anime__` prefix:

```html
<img
  src="anime.png"
  class="anime__animated anime__fadeIn"
/>
```

## Anime Names

* Fade In
  * [x] `anime__fadeIn`
  * [x] `anime__fadeInDown`
  * [x] `anime__fadeInLeft`
  * [ ] Fade In Left Big
  * [x] `anime__fadeInRight`
  * [ ] Fade In Right Big
  * [ ] Fade In Up
  * [ ] Fade In Up Big

* Fade Out
  * [x] Fade Out
  * [x] Fade Out Down
  * [x] Fade Out Left
  * [ ] Fade Out Left Big
  * [x] Fade Out Right
  * [ ] Fade Out Right Big
  * [x] Fade Out Up
  * [ ] Fade Out Up Big

* [ ] Fade Down Big

* Bounce In
  * [ ] Bounce
  * [x] Bounce In
  * [x] Bounce In Down
  * [x] Bounce In Left
  * [x] Bounce In Right

* Bounce Out
  * [ ] Bounce Up
  * [x] Bounce Out
  * [x] Bounce Out Down
  * [x] Bounce Out Left
  * [x] Bounce Out Right
  * [x] Bounce Out Up

* [ ] Flash

## Inspired by

Huge thanks to:

* [Chris Coyier](https://github.com/chriscoyier)
* [Tutorials Point](https://www.tutorialspoint.com/css/css_animation.htm)

<!-- 

<html>
  <head>
    <link
      rel="stylesheet"
      href="anime.min.css"
    />
  </head>
  <body>
    <center style="margin-top: 20%;">
      <h1 class="anime__animated anime__bounceOutUp">An animated element</h1>
      <img src="anime.png" class="anime__animated anime__bounceOutUp" />
    </center>
  </body>
</html>

-->
