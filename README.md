# Year of the Horse SVG Animation
This SVG is 600 by 400 pixels.

## Horse
This is a series of four PNGs imported via means of the `image` tag. Each PNG shows a different silhouette of a horse in motion.
- Each `image` tag has two animations.
- Animations fade in, then fade out (animation on opacity)
- Each animation on an `image` tag runs when the previous `image` tag's animations end.
- The first `image` tag animation runs when the SVG is loaded, and when the last `image` tag animations end. This makes the entire galloping horse animation run indefinitely.

## Sky
- a `rect` tag that has an animated `LinearGradient` background. It cycles through deep blue (dawn), light blue (day), orange (dusk) and deep purple (night).

## Moon
- a `circle tag` that has both `opacity` and `cx` animated. It moves from right to left, opacity going from 1 to 0, and 1 again.

## Ground
- a `g` tag that contains one `path` tag that has an animated `LinearGradient` background. The color cycles though different shades of green.
- The `path` has a shape that is repeated till the shape is twice the width of the SVG.
- The `g` tag is animated to move left until the right edge meets the SVG's right edge, and repeats.

## Hills
- a `g` tag that contains a series of `path` tags that has an animated `LinearGradient` background. The color cycles though different shades of brown.
- The `paths` are repeated till the entire collection, as a whole, is twice the width of the SVG.
- The `g` tag is animated to move left until the right edge meets the SVG's right edge, and repeats.
- This animation moves slightly slower than the ground.
  
## Mountains
- a `g` tag that contains a series of `path` tags that has an animated `LinearGradient` background. The color cycles though different shades of dark brown.
- The `paths` are repeated till the entire collection, as a whole, is twice the width of the SVG.
- The `g` tag is animated to move left until the right edge meets the SVG's right edge, and repeats.
- This animation moves slightly slower than the hills.
