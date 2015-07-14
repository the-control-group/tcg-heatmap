# tcg-heatmap

**This element is compatible with Polymer 0.5.**

copied this guy: http://bl.ocks.org/tjdecke/5558084

__Example:__

```
	<tcg-heatmap
		yAxisLabels="{{ yAxisLabels }}"
		xAxisLabels="{{ xAxisLabels }}"
		bgColors="{{ bgColors }}"
		textColors="{{ textColors }}"
		data="{{ data }}"></tcg-heatmap>
```
# Attributes

#### `margin`

Object to set margin around the heatmap. This will leave space for the axis labels and color key.

#### `width`

Number for the width of the entire element

#### `height`

Number for the height of the entire element

#### `duration`

Number in milliseconds for the animation time

#### `legendClassName`

String for the class name

#### `cellBackgroundClassName`

String for the class name

#### `cellTextClassName`

String for the class name

#### `xAxisLabelClassName`

String for the class name

#### `yAxisLabelClassName`

String for the class name

#### `xAxisLabels`

Array of strings for the x axis labels

#### `yAxisLabels`

Array of strings for the y axis labels

#### `bgColors`

Array of strings for the heatmap cell colors. Ordered by smallest value to largest value

#### `textColors`

Array of strings for the heatmap text colors. Ordered by smallest value to largest value

#### `data`

Array: Example [{x: 0, y: 0, value: 20}]