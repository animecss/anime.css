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

or add it directly to your webpage:

```js
<head>
  <link
    rel="stylesheet"
    href="https://unpkg.com/anime.css@1.0.1/anime.min.css"
  />
</head>
```

## Usage

Add the class `anime__animated` to an element, along with many of the anime names that starting with the `anime__` prefix:

```html
<img src="anime.png" class="anime__animated anime__fadeIn" />
```

#### Anime Names Starting with `anime__` Prefix

- Fade In

  - `anime__fadeIn`
  - `anime__fadeInDown`
  - `anime__fadeInLeft`
  - `anime__fadeInRight`

- Fade Out

  - `anime__fadeOut`
  - `anime__fadeOutDown`
  - `anime__fadeOutLeft`
  - `anime__fadeOutRight`
  - `anime__fadeOutUp`

- Bounce In

  - `anime__bounceIn`
  - `anime__bounceInDown`
  - `anime__bounceInLeft`
  - `anime__bounceInRight`

- Bounce Out

  - `anime__bounceOut`
  - `anime__bounceOutDown`
  - `anime__bounceOutLeft`
  - `anime__bounceOutRight`
  - `anime__bounceOutUp`

- Flip In

  - `anime__flipInX`
  - `anime__flipInY`

- Flip Out

  - `anime__flipOutX`
  - `anime__flipOutY`

- Roll

  - `anime__rollIn`
  - `anime__rollOut`

- Rotate In

  - `anime__rotateIn`
  - `anime__rotateInUpLeft`
  - `anime__rotateInUpRight`
  - `anime__rotateInDownLeft`
  - `anime__rotateInDownRight`

- Rotate Out

  - `anime__rotateOut`
  - `anime__rotateOutUpLeft`
  - `anime__rotateOutUpRight`
  - `anime__rotateOutDownLeft`
  - `anime__rotateOutDownRight`

- Light Speed

  - `anime__lightSpeedIn`
  - `anime__lightSpeedOut`

- Action
  - `anime__flash`
  - `anime__hinge`
  - `anime__pulse`
  - `anime__wobble`
  - `anime__winggle`
  - `anime__shake`
  - `anime__swing`
  - `anime__tada`

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

- [Chris Coyier](https://github.com/chriscoyier)
- [Tutorials Point](https://www.tutorialspoint.com/css/css_animation.htm)

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

@media print, (prefers-reduced-motion: reduce) {
  .animated {
    animation-duration: 1ms !important;
    transition-duration: 1ms !important;
    animation-iteration-count: 1 !important;
  }

  .animated[class*='Out'] {
    opacity: 0;
  }
}

-->
