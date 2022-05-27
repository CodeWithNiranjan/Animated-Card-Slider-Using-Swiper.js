# Animated Card Slider Using Swiper.js

Swiper is the most modern free mobile touch slider with hardware accelerated transitions and amazing native behavior.

## Installation

Use UNPKG - [CSS file](https://unpkg.com/swiper@7/swiper-bundle.min.css)  , [JavaScript file](https://unpkg.com/swiper@7/swiper-bundle.min.js)

```css
<link rel="stylesheet" href="https://unpkg.com/swiper@8/swiper-bundle.min.css"/>
```

```javascript
<script src="https://unpkg.com/swiper@8/swiper-bundle.min.js"></script>
```

## Usage

```html
<!-- Slider main container -->
    <div class="swiper">
      <div class="swiper-wrapper">
        <div class="swiper-slide">
            <div class="container">
                <h1>A</h1>
            </div>
        </div>
        <div class="swiper-slide">
            <div class="container">
                <h1>B</h1>
            </div>
        </div>
        <div class="swiper-slide">
            <div class="container">
                <h1>C</h1>
            </div>
        </div>
        <div class="swiper-slide">
            <div class="container">
                <h1>D</h1>
            </div>
        </div>
        <div class="swiper-slide">
            <div class="container">
                <h1>E</h1>
            </div>
        </div>
        <div class="swiper-slide">
            <div class="container">
                <h1>F</h1>
            </div>
        </div>
      </div>
      <div class="swiper-pagination"></div>
    </div>
```

```css
@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');
```

```javascript
const swiper = new Swiper('.swiper', {
  effect: "slider",
  slidesPerView : 3,
  grabCursor: true,
  centeredSlides: true,
  pagination: {
    el: '.swiper-pagination',
  },
});
```

## Subscribe
Please subscribe [CodeWithNiranjan](https://youtube.com/channel/UCzfQyi4_E-lS9ps3fVb0jlA)

<h1>Thank You</h1>
