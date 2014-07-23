JAMAccurateSlider
===========

A UISlider subclass that enables more accurate value selection.

![example image](https://raw.githubusercontent.com/jmenter/JAMAccurateSlider/master/example.png "JAMAccurateSlider Example Image")

JAMAccurateSlider is a drop-in replacement for UISlider. It behaves exactly the same as UISlider with the following awesome differences:

1. When the user begins tracking, two small "calipers" appear at the extents of the track.
2. When the user tracks their finger up (or down) past a certain threshold (which is actually twice the height of the slider), the calipers move in towards the thumb and the thumb (and corresponding slider value) begins to move more slowly and accurately.
3. The further the user moves their finger from the slider, the greater the possiblity of accuracy.

This behavior is completely automatic. We think you'll love it.
