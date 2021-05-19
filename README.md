# Accessible carousel boiilerplates

Carousels aren't [effective](https://erikrunyon.com/2013/01/carousel-interaction-stats/) or [popular](https://www.nngroup.com/articles/auto-forwarding) with real users, but sometimes you just have no choice! At [Accessible360](https://accessible360.com/), we see carousels on client sites every day, and we've found them to be a common source of accessibility barriers practically every time they are used.

To help make a difference for end users and developers sooner rather than later, we're releasing this set of realistic, ready-to-use code snippets for popular carousel packages that you can start using right now to create more accessible carousels and sliders! So far we have snippets for:

* <a href="#accessible-slick">accessible-slick</a>
* <a href="#Flickity">Flickity</a>
* <a href="#Owl-Carousel-2">Owl Carousel 2</a>
* <a href="#Slick-Slider">Slick Slider</a>
* <a href="#Splide">Splide</a>

If you'd like to see snippets for other carousel packages or use cases, [please let us know](https://github.com/Accessible360/accessible-carousel-boilerplates/issues)!

All of these code snippets can also be found over on [CodePen in this collection](https://codepen.io/collection/narjZO) (they are exactly the same!).

## accessible-slick
[accessible-slick](https://github.com/Accessible360/accessible-slick) is a drop-in replacement for the classic Slick Slider package that adds a layer of built-in accessibility improvements. Since practically all of its accessibility improvements are baked right into the package, these code snippets end up being the smallest and simplest.

* Hero banner - [live demo](https://accessible360.github.io/accessible-carousel-boilerplates/accessible-slick/hero-banner.html) and [source code](https://github.com/Accessible360/accessible-carousel-boilerplates/blob/main/accessible-slick/hero-banner.html)
* Linked product cards - [live demo](https://accessible360.github.io/accessible-carousel-boilerplates/accessible-slick/linked-product-cards.html) and [source code](https://github.com/Accessible360/accessible-carousel-boilerplates/blob/main/accessible-slick/linked-product-cards.html)
* PDP product image with thumbnails - [live demo](https://accessible360.github.io/accessible-carousel-boilerplates/accessible-slick/pdp-product-image-with-thumbnails.html) and [source code](https://github.com/Accessible360/accessible-carousel-boilerplates/blob/main/accessible-slick/pdp-product-image-with-thumbnails.html)
* Product tiles with quick view functionality - [live demo](https://accessible360.github.io/accessible-carousel-boilerplates/accessible-slick/product-tiles-with-quick-view-functionality.html) and [source code](https://github.com/Accessible360/accessible-carousel-boilerplates/blob/main/accessible-slick/product-tiles-with-quick-view-functionality.html)
​
## Flickity
[Flickity](https://github.com/metafizzy/flickity) has some good things going for it, but also a few major issues for accessibility. Avoid using the `wrapAround` and `accessibility` options, and be sure to hide all the interactive content inside of each slide.

* Hero banner - [live demo](https://accessible360.github.io/accessible-carousel-boilerplates/Flickity/hero-banner.html) and [source code](https://github.com/Accessible360/accessible-carousel-boilerplates/blob/main/Flickity/hero-banner.html)
* Linked product cards - [live demo](https://accessible360.github.io/accessible-carousel-boilerplates/Flickity/linked-product-cards.html) and [source code](https://github.com/Accessible360/accessible-carousel-boilerplates/blob/main/Flickity/linked-product-cards.html)
* PDP product image with thumbnails - [live demo](https://accessible360.github.io/accessible-carousel-boilerplates/Flickity/pdp-product-image-with-thumbnails.html) and [source code](https://github.com/Accessible360/accessible-carousel-boilerplates/blob/main/Flickity/pdp-product-image-with-thumbnails.html)
* Product tiles with quick view functionality - [live demo](https://accessible360.github.io/accessible-carousel-boilerplates/Flickity/product-tiles-with-quick-view-functionality.html) and [source code](https://github.com/Accessible360/accessible-carousel-boilerplates/blob/main/Flickity/product-tiles-with-quick-view-functionality.html)
​
## Owl Carousel 2
[Owl Carousel 2](https://github.com/OwlCarousel2/OwlCarousel2) is officially deprecated and should not be used for new projects! Avoid using the inaccessible built-in slide dots, and be sure to use the events API to hide all non-visible slides.

* Hero banner - [live demo](https://accessible360.github.io/accessible-carousel-boilerplates/Owl$20Carousel%202/hero-banner.html) and [source code](https://github.com/Accessible360/accessible-carousel-boilerplates/blob/main/Owl$20Carousel%202/hero-banner.html)
* Linked product cards - [live demo](https://accessible360.github.io/accessible-carousel-boilerplates/Owl$20Carousel%202/linked-product-cards.html) and [source code](https://github.com/Accessible360/accessible-carousel-boilerplates/blob/main/Owl$20Carousel%202/linked-product-cards.html)
* PDP product image with thumbnails - [live demo](https://accessible360.github.io/accessible-carousel-boilerplates/Owl$20Carousel%202/pdp-product-image-with-thumbnails.html) and [source code](https://github.com/Accessible360/accessible-carousel-boilerplates/blob/main/Owl$20Carousel%202/pdp-product-image-with-thumbnails.html)
* Product tiles with quick view functionality - [live demo](https://accessible360.github.io/accessible-carousel-boilerplates/Owl$20Carousel%202/product-tiles-with-quick-view-functionality.html) and [source code](https://github.com/Accessible360/accessible-carousel-boilerplates/blob/main/Owl$20Carousel%202/product-tiles-with-quick-view-functionality.html)
​
## Slick Slider
[Slick Slider](https://github.com/kenwheeler/slick) is perhaps the most widely-used carousel package, even though it has been [abandoned](https://github.com/kenwheeler/slick/graphs/contributors) (though not officially deprecated) by its author. Ironically, you should avoid the `accessibility` option, since it actually makes the markup worse for disabled users! Be sure to use the latest version (1.8.1 as of May 2021), which includes some important updates that affect accessibility. Custom JavaScript will be needed to ensure that non-visible slides are actually hidden.

* Hero banner - [live demo](https://accessible360.github.io/accessible-carousel-boilerplates/Slick%20Slider/hero-banner.html) and [source code](https://github.com/Accessible360/accessible-carousel-boilerplates/blob/main/Slick%20Slider/hero-banner.html)
* Linked product cards - [live demo](https://accessible360.github.io/accessible-carousel-boilerplates/Slick%20Slider/linked-product-cards.html) and [source code](https://github.com/Accessible360/accessible-carousel-boilerplates/blob/main/Slick%20Slider/linked-product-cards.html)
* PDP product image with thumbnails - [live demo](https://accessible360.github.io/accessible-carousel-boilerplates/Slick%20Slider/pdp-product-image-with-thumbnails.html) and [source code](https://github.com/Accessible360/accessible-carousel-boilerplates/blob/main/Slick%20Slider/pdp-product-image-with-thumbnails.html)
* Product tiles with quick view functionality - [live demo](https://accessible360.github.io/accessible-carousel-boilerplates/Slick%20Slider/product-tiles-with-quick-view-functionality.html) and [source code](https://github.com/Accessible360/accessible-carousel-boilerplates/blob/main/Slick%20Slider/product-tiles-with-quick-view-functionality.html)
​
## Splide
[Splide](https://github.com/Splidejs/splide) may be the most accessible package of all of these, with good use of semantic HTML. Avoid the `keyboard` and `slideFocus` options. Some minor work needs to be done to ensure that non-visible slides are fully hidden.

* Hero banner - [live demo](https://accessible360.github.io/accessible-carousel-boilerplates/Splide/hero-banner.html) and [source code](https://github.com/Accessible360/accessible-carousel-boilerplates/blob/main/Splide/hero-banner.html)
* Linked product cards - [live demo](https://accessible360.github.io/accessible-carousel-boilerplates/Splide/linked-product-cards.html) and [source code](https://github.com/Accessible360/accessible-carousel-boilerplates/blob/main/Splide/linked-product-cards.html)
* PDP product image with thumbnails - [live demo](https://accessible360.github.io/accessible-carousel-boilerplates/Splide/pdp-product-image-with-thumbnails.html) and [source code](https://github.com/Accessible360/accessible-carousel-boilerplates/blob/main/Splide/pdp-product-image-with-thumbnails.html)
* Product tiles with quick view functionality - [live demo](https://accessible360.github.io/accessible-carousel-boilerplates/Splide/product-tiles-with-quick-view-functionality.html) and [source code](https://github.com/Accessible360/accessible-carousel-boilerplates/blob/main/Splide/product-tiles-with-quick-view-functionality.html)

---

## Credits
The research and code snippets provided in this article were made by [Accessible360](https://accessible360.com), whose expert accessibility engineers were invaluable in providing their insight, feedback, and time on this topic.

If your company is looking for an accessibility partner to help bring your product to the next level through live user audits, monitoring, training, or remediation support, then get in touch today!

[![Visit Accessible360.com](./images/accessible360-tag-logo-color.png)](https://accessible360.com)