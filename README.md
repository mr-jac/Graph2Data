# Graph2Data
A tool I made for myself in my college days for times when I was expected to use numerical data as if in a spreadsheet but was only given an image of a graph to work with.
Originally in MATLAB, now adapted for the web in pure JavaScript!

Latest working version can be found [on my website](https://jacobdeboer.com/graph2data).


## About The Project

Note that this should **not** be counted on for exact numerical accuracy, since the quality of results will be limited by the detail and resolution of the graph, as well as user error. But the data should be within a reasonable margin of error and should convey general trends that further calculations can be performed with.

## Usage

This is one-page web application that can be accessed without any additional libraries or setup by just opening `index.html`.

**Note that this application relies on making precise clicks on a page with a cursor, and therefore it will not work on a mobile device or tablet. Using a computer with a mouse is highly recommended.**

Generally, you will go through the items on the right hand sidebar from top to bottom:

1. Click the "upload button", then browse for the image of the graph you wish to extract data from.
2. In the **Mark Axes** section, mark the x axis minimum, x axis maximum, y axis minimum, and y axis maximum on the graph.
4. In the **Mark Data** section, click the <span style="color:green;">+</span> button to create as many data series as you wish. For each data series, click on any points on the graph image you wish to get the value of, then move on to the next data series.
5. In the **Options** section,
6. Click export to download your data points to a CSV file.

## Contributing

I will shortly be posting bugs and improvements on the issues page for this project. Contributions from others are appreciated, pending review.

## License

Copyright 2022 Jacob DeBoer

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.