#3dcarousel.js 
An all-purpose pure CSS 3D carousel.
Requires Chrome or Safari.

##Usage

    function onCellAdded(cell,index) {
    	// Here define what goes inside the cell at given index
    }
    
    ...
    
    var container = document.getElementById("container");
    carousel = new Carousel(container,// Containing node
                            9,        // Nb Cells
                            465,      // Cell width
                            352,      // Cell height
                            onCellAdded,
                            onCellFocus,
                            onCellBlur,
                            onCellSelect
                            );

##Demo

[Try out the demo](http://kaizouman.github.com/3dcarousel/).

##License

You may use this code under the terms of the MIT license.
