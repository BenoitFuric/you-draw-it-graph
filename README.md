# A great idea from the NYT

Inspired by the New York Times article : [You Draw It: What Got Better or Worse During Obama’s] (https://www.nytimes.com/interactive/2017/01/15/us/politics/you-draw-obama-legacy.html)
	
This repository is a fork from <a href="https://bl.ocks.org/1wheel/07d9040c3422dac16bd5be741433ff1e">Adam Pearce’s early/simplified version of “You draw it”</a>, based on <a href="https://d3js.org/">D3.js</a>.

## Demo
[Check the demo] (https://benoitfuric.github.io/you-draw-it-graph/) - An interactive graph which works on desktop and mobile.

![DrawIt gif](https://benoitfuric.github.io/you-draw-it-graph/DrawIt.gif)

## Set the range
In ``js/_script.js``, put the limit of the view.

```javascript
c.x.domain([2007, 2016])
c.y.domain([0, 700])
```

## Place your graph in your page
You can define the place of the  in ``js/_script.js``.  Choose an element or an id.
```javascript
var sel = d3.select('#infographie').html('')`
```

# Todo / Option to  :
- Reveal the result with a button and not at the end of the drawing
- Display data on the graph
- Add a grid
 
