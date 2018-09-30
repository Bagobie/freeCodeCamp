---
id: 5900f4f71000cf542c51000a
challengeType: 5
title: 'Problem 395: Pythagorean tree'
---

## Description
<section id='description'>
The Pythagorean tree is a fractal generated by the following procedure:



Start with a unit square. Then, calling one of the sides its base (in the animation, the bottom side is the base):
 Attach a right triangle to the side opposite the base, with the hypotenuse coinciding with that side and with the sides in a 3-4-5 ratio. Note that the smaller side of the triangle must be on the 'right' side with respect to the base (see animation).
 Attach a square to each leg of the right triangle, with one of its sides coinciding with that leg.
 Repeat this procedure for both squares, considering as their bases the sides touching the triangle.

The resulting figure, after an infinite number of iterations, is the Pythagorean tree.





It can be shown that there exists at least one rectangle, whose sides are parallel to the largest square of the Pythagorean tree, which encloses the Pythagorean tree completely.


Find the smallest area possible for such a bounding rectangle, and give your answer rounded to 10 decimal places.
</section>

## Instructions
<section id='instructions'>

</section>

## Tests
<section id='tests'>

```yml
- text: <code>euler395()</code> should return 28.2453753155.
  testString: 'assert.strictEqual(euler395(), 28.2453753155, "<code>euler395()</code> should return 28.2453753155.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function euler395() {
  // Good luck!
  return true;
}

euler395();
```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>