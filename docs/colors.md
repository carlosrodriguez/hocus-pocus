### Colors

Colors available as variables (so you can override them if you wish):

<div class="color-block bg-white text-muted">$color-white</div>
<div class="color-block bg-silver">$color-silver</div>
<div class="color-block bg-gray">$color-gray</div>
<div class="color-block bg-black">$color-black</div>
<div class="color-block bg-red">$color-red</div>
<div class="color-block bg-orange">$color-orange</div>
<div class="color-block bg-yellow">$color-yellow</div>
<div class="color-block bg-lime">$color-lime</div>
<div class="color-block bg-green">$color-green</div>
<div class="color-block bg-olive">$color-olive</div>
<div class="color-block bg-teal">$color-teal</div>
<div class="color-block bg-aqua">$color-aqua</div>
<div class="color-block bg-blue">$color-blue</div>
<div class="color-block bg-navy">$color-navy</div>
<div class="color-block bg-fuchsia">$color-fuchsia</div>
<div class="color-block bg-purple">$color-purple</div>
<div class="color-block bg-maroon">$color-maroon</div>

Defaults:

```scss
$color-ui: $color-silver;        // ui elements color like rules, borders, form inputs
$color-btn: $color-black;        // button color without any modifiers
$color-font: $color-black;       // base font color
$color-link: $color-blue;        // links color
$color-muted: $color-gray;       // blockquote and `.text-muted` color
$color-disabled: $color-ui;      // disabled form input and buttons color
$color-brand: $color-blue;       // brand color
$color-positive: $color-green;   // positive color
$color-negative: $color-red;     // negative color
$color-informative: $color-blue; // informative color
$color-map: (
  'white': $color-white,
  'silver': $color-silver,
  'gray': $color-gray,
  'black': $color-black,
  'red': $color-red,
  'orange': $color-orange,
  'yellow': $color-yellow,
  'lime': $color-lime,
  'green': $color-green,
  'olive': $color-olive,
  'teal': $color-teal,
  'aqua': $color-aqua,
  'blue': $color-blue,
  'navy': $color-navy,
  'fuchsia': $color-fuchsia,
  'purple': $color-purple,
  'maroon': $color-maroon,
  'brand': $color-brand,
  'positive': $color-positive,
  'negative': $color-negative,
  'informative': $color-informative,
  'muted': $color-muted
);                               // color helpers are generated based on this map
```

### Color Helpers

Specify text and background color of an element.

Color helpers use `!important` and are generated for each color in `$color-map`.

Usage:

```scss
.text[-color];
.bg[-color];

/*
 * Where [-color] is one of these values:
 *   -aqua, -blue, -navy, -teal, -green, -olive, -lime, -yellow, -orange,
 *   -red, -fuchsia, -purple, -maroon, -white, -silver, -grey, -black,
 *   -informative, -positive, -negative, -brand, -muted
 */
```

<div class="example">
  <p class="text-muted">Paragraph with a muted text</p>
  <p class="text-brand">Paragraph with a brand text</p>
  <p class="bg-negative">Paragraph with a negative background</p>
  <p class="bg-black text-white">Paragraph with a black background and white text</p>
</div>

```html
<p class="text-muted">Paragraph with a muted text</p>
<p class="text-brand">Paragraph with a brand text</p>
<p class="bg-negative">Paragraph with a negative background</p>
<p class="bg-black text-white">Paragraph with a black background and white text</p>
```
