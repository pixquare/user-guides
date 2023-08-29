# Common tool options

## Pixel perfect
![Pixel perfect](images/pixel_perfect.png)<br/>
Pixel perfect helps you create cleaner lines easier by avoiding unwanted corner pixels. <br/>
This option is available for [brush](brush.md) and [eraser](eraser.md).

## Pressure sensitivity
![Pressure sensitivity](images/pressure_sensitivity.png)<br/>
If you're using a pencil, you can enabled this option so that the size of strokes will be dynamic based on the pressure of the pencil, the curve linear. Once enabled, you can adjust the range of the curve, the max range is 0x to 3x the current size.<br/>
This option is available for [brush](brush.md) and [eraser](eraser.md).

## Dithering
![Dithering](images/dithering.png)<br/>
There are 4 dithering type: none, 2x2, 4x4, and 8x8. This option is available for [brush](brush.md), [eraser](eraser.md), and [Color bucket with gradient fill mode](color_bucket.md).<br/>
For brush and eraser, you can adjust the intensity range. If you want to have a constant pattern, you can set the lower bound and upper bound of the range to be the same value.

## Stroke type
![Stroke type](images/stroke_type.png)<br/>
This is the shape that will be stamped on the path of stroke. You can select a square or round shape. <br/>
This option is available for all drawing tools.

## Water color
![Water color](images/water_color.png)<br/>
With this option enabled, when you draw translucent color (alpha less than 100%), it will paint that color on top of the current content. If this option is off, the new color will replace the current content. A trick with this is that you can turn this off, then drag opacity to 0%, at this point, drawing tools will act as eraser. <br/>
This option is available for all drawing tools.
