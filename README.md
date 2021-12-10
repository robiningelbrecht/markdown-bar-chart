# markdown-bar-chart

## What is this?

This is a simple function that takes an array and generates a [GitHub flavored
markdown (GFM)][gfm] bar chart. This script heavily relies on https://github.com/wooorm/markdown-table. 
So a big thank you to Titus 🎉🎉🎉!   

## Install

```html
<script src="/markdown-bar-chart.js"></script>
```

## Use

```js
// Will display a chart woth 3 bars.

barChart('Chart title', [10, 20, 35], {
    'sortOnValue': 'DESC',
    'displayPercentages': false
})
```

