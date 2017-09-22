# Masonry view grid, class js.
Init masonry grid:
```js
let masonryGrid = new Masonry(list, col, res);
```
#### Arguments
- <b>list</b> - items list container class or id
- <b>col</b> - columns for different resolutions
```javascript
col = {
    md: 3,
    sm: 2,
    xs: 1
}
```
- <b>res</b> - resolutions
```javascript
res = {
    md: [992, Infinity],
    sm: [769, 991],
    xs: [-Infinity, 768]
}
```

#### Update grid 
Recalculate items position in grid
```javascript
masonryGrid.update();
```
