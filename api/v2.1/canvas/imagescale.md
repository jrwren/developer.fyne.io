---
layout: page
tags: [api]
title: Fyne API "canvas.ImageScale"
package: fyne.io/fyne/v2/canvas
---

# canvas.ImageScale
---
```go
import "fyne.io/fyne/v2/canvas"
```

## Usage

#### type ImageScale

```go
type ImageScale int32
```

ImageScale defines the different scaling filters used to scaling images

```go
const (
	// ImageScaleSmooth will scale the image using ApproxBiLinear filter (or GL equivalent)
	ImageScaleSmooth ImageScale = 0
	// ImageScalePixels will scale the image using NearestNeighbor filter (or GL equivalent)
	ImageScalePixels ImageScale = 1
	// ImageScaleFastest will scale the image using hardware GPU if available
	//
	// Since: 2.0
	ImageScaleFastest ImageScale = 2
)
```
