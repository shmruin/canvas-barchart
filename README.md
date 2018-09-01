# canvas-barchart
Lightweight, configurable and simple bar chart library in Javascript

![Packagist](https://img.shields.io/packagist/l/doctrine/orm.svg)
![Codacy grade](https://img.shields.io/codacy/grade/e27821fb6289410b8f58338c7e0bc686.svg)

## Description
 * `bar.js` is a Canvas based simple Javascript Bar Chart Library to provide a configurable, lightweight and dependency free experience
 * Following code of udemy Canvas Bar Chart creator, Html5 Canvas calss

![Alt text](screenshots/barchart.PNG?raw=true "udemy canvas bar chart")

## Installation
Download the `bar.js` and include it in your project

```html
<script src="bar.js"></script>
```

## Usage
To create the bar chart, you need a block level container like a `div` or `p`

```html
<div id="chart">This will be a bar chart!</div>
```

Then you can create the BarChart object in your Javascript file 

```js
var barChart = new BarChart(chartId, chartWidth, chartHeight, data)
```

### Parameters
- `chartId - containerId (String)`
Defines the id of container like "Chart"

- `chartWidth (Integer)`
Defines the width of the chart like 500

- `chartHeight (Integer)`
Defines the height of the chart like 300

- `data (Object Array)`
Defines the data object. The object should have 2 key-value pair: label and value. Example Data:

```js
    var data = [
        { label: 'Jan', value: 123 },
        { label: 'Feb', value: 29 },
        { label: 'March', value: 5 },
        { label: 'April', value: 179 },
        { label: 'May', value: 66 },
    ]
```

## License
[MIT](License.md) © [shmruin](https://github.com/shmruin/)
