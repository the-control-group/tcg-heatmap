# tcg-swipe

**This element is compatible with Polymer 0.5.**

__Example:__

```
	<tcg-swipe id="swipe" isReveal="{{ isReveal }}" xThreshold="{{ xThreshold }}" animationTime="{{ animationTime }}">
		<div touchpad>Overlay Content</div>
		<div left>
			Left Content
			<a href="#" class="close" on-tap="{{ close }}">Close</a>
		</div>
		<div right>
			Right Content
			<a href="#" class="close" on-tap="{{ close }}">Close</a>
		</div>
	</tcg-swipe>
```
# Attributes

#### `isReveal`

Boolean that determines if the left and right content is position right below the touchpad. If `false`, left and right content moves with the touchpad.

#### `xThreshold`

Number that determines if it'll reveal the full content on trackend event. Default is `50` px

#### `animationTime`

Number in milliseconds for animation length

# Methods

#### `close`

Resets the positions