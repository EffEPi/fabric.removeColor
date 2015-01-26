# fabric.removeColor
New filter for fabric.js to remove a specific color from an image

@example

    var filter = new fabric.Image.filters.RemoveColor({
      color: [235,158,84]
    });
    object.filters.push(filter);
    object.applyFilters(canvas.renderAll.bind(canvas));
