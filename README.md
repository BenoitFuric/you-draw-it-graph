# A great idea from the NYT

Inspired by the New York Times article : [You Draw It: What Got Better or Worse During Obama’s] (https://www.nytimes.com/interactive/2017/01/15/us/politics/you-draw-obama-legacy.html)
	
This repository is a fork from <a href="https://bl.ocks.org/1wheel/07d9040c3422dac16bd5be741433ff1e">Adam Pearce’s early/simplified version of “You draw it”</a>, based on <a href="https://d3js.org/">D3.js</a>.
	
## Demo
[Check the demo] (http://furic.be/web/draw-it/)


## Set the graph
In ``js/_script.js``, put 

```javascript
c.x.domain([2007, 2016])
c.y.domain([0, 700])
```

## Place your graph
You can define the place of the  in ``js/_script.js``.  Choose an element or an id.

`var sel = d3.select('#infographie').html('')`

# Todo / Option to  :
- Add a button below to reveal the result (instead of 
- Display data on the graph
- Add 
 
