# HW - Lorenz Attractor

## I. Overview

- The Lorenz Attractor was created/discovered by Edward Lorenz while he was studying how to simulate convection currents present in weather phenomena.
- Dynamical systems such as these as seen throughout nature, and are compelling subjects to explore in interactive media
- Today we will implement this systemin JavaScript/Canvas - and pretty much as a port of Daniel Shiffman's Processing example linked below. (Thanks so much to Daniel for his series of creative coding videos!)


## II. Handy Links
- The Coding Train - [Coding Challenge #12: The Lorenz Attractor in Processing](https://www.youtube.com/watch?v=f0lkz2gSsIk)
- https://en.wikipedia.org/wiki/Lorenz_system
- http://ww2010.atmos.uiuc.edu/(Gh)/guides/mtr/hyd/cond/conv.rxml
- http://paulbourke.net/fractals/lorenz/

## III. Video Links

- [Lorenz Attractor-1 (10:20)](https://video.rit.edu/Watch/about-lorenz-attractor) - About the Lorenz Attractor
- [Lorenz Attractor-2 (16:30)](https://video.rit.edu/Watch/visualizing-lorenz-attractor) - Visualizing the Lorenz Attractor

See myCourses for submission instructions.

## IV. Start Code


**LA-start.html**

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8" />
	<title>Lorenz Attractor Start</title>
	<style>canvas{border: 1px solid black;}</style>
	<script>
	
	let ctx;
	const canvasWidth = 800, canvasHeight = 600;
	
	
	function init(){
	  ctx = canvas.getContext("2d");
	  canvas.width = canvasWidth;
	  canvas.height = canvasHeight;
	  ctx.fillRect(0,0,canvasWidth,canvasHeight);
	}
	</script>
</head>
<body>
<canvas id="canvas"></canvas>

</body>
</html>
```