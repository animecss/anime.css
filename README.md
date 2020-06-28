<p align="center">
  ⭐️ If you like Anime.css, give it a star! ⭐️
</p>

<img src="https://github.com/animecss/anime.css/blob/master/static/images/anime.png" align="right" />

# Anime.css

アニメ is a lightweight cross-browser CSS animations library.

## Install

`Anime.css` is available on npm:

```js
npm install anime.css --save
```

`Anime.css` is available on yarn as well:

```js
yarn add anime.css
```

<!-- or add it directly to your webpage:

```js
<head>
  <link
    rel="stylesheet"
    href="anime.min.css"
  />
</head>
``` -->

## Usage

Add the class `anime__animated` to an element, along with many of the anime names that starting with the `anime__` prefix:

```html
<img
  src="anime.png"
  class="anime__animated anime__fadeIn"
/>
```

#### Anime Names Starting with `anime__` Prefix

* Fade In
  * [x] `anime__fadeIn`
  * [x] `anime__fadeInDown`
  * [x] `anime__fadeInLeft`
  * [x] `anime__fadeInRight`

* Fade Out
  * [x] `anime__fadeOut`
  * [x] `anime__fadeOutDown`
  * [x] `anime__fadeOutLeft`
  * [x] `anime__fadeOutRight`
  * [x] `anime__fadeOutUp`

* Bounce In
  * [x] `anime__bounceIn`
  * [x] `anime__bounceInDown`
  * [x] `anime__bounceInLeft`
  * [x] `anime__bounceInRight`

* Bounce Out
  * [x] `anime__bounceOut`
  * [x] `anime__bounceOutDown`
  * [x] `anime__bounceOutLeft`
  * [x] `anime__bounceOutRight`
  * [x] `anime__bounceOutUp`

* Flip In
  * [x] `anime__flipInX`
  * [x] `anime__flipInY`

* Flip Out
  * [x] `anime__flipOutX`
  * [x] `anime__flipOutY`

* Roll
  * [x] `anime__rollIn`
  * [x] `anime__rollOut`

* Rotate In
  * [x] `anime__rotateIn`
  * [x] `anime__rotateInUpLeft`
  * [x] `anime__rotateInUpRight`
  * [x] `anime__rotateInDownLeft`
  * [x] `anime__rotateInDownRight`

* Rotate Out
  * [x] `anime__rotateOut`
  * [x] `anime__rotateOutUpLeft`
  * [x] `anime__rotateOutUpRight`
  * [x] `anime__rotateOutDownLeft`
  * [x] `anime__rotateOutDownRight`

* Light Speed
  * [x] `anime__lightSpeedIn`
  * [x] `anime__lightSpeedOut`

* Action
  * [x] `anime__flash`
  * [x] `anime__hinge`
  * [ ] `anime__pulse`
  * [ ] `anime__wobble`
  * [ ] `anime__winggle`
  * [ ] `anime__shake`
  * [ ] `anime__swing`
  * [ ] `anime__tada`

<!--

* TODO
  * [ ] Fade Out Right Big
  * [ ] Fade In Left Big
  * [ ] Bounce
  * [ ] Fade Out Up Big
  * [ ] Fade Out Left Big
  * [ ] Fade In Right Big
  * [ ] Fade In Up
  * [ ] Fade In Up Big
  * [ ] Fade Down Big
  * [ ] Bounce Up
  * [ ] Flip

-->

## Inspired by

Huge thanks to:

* [Chris Coyier](https://github.com/chriscoyier)
* [Tutorials Point](https://www.tutorialspoint.com/css/css_animation.htm)

## Contributing

We'd love to have your helping hand on contributions to `Anime.css` by forking and sending a pull request!

Your contributions are heartily ♡ welcome, recognized and appreciated. (✿◠‿◠)

## License

The MIT License [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

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
