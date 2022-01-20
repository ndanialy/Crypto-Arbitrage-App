# Crypto Arbitrage App

An application for analyzing bitcoin prices from two different brokers in an attempt to find arbitrage opportunities.

---

## Technologies

This project uses Jupyter Lab in addition to the following libraries and add ons:

* [pathlib](https://docs.python.org/3/library/pathlib.html) for the path functions to locate the csv files.

* [pandas](https://pandas.pydata.org/docs/) for working with dataframes.

* [matplotlib](https://docs.python.org/3/library/pathlib.html) for the data visualization.

---

## Installation Guide

Please run the following commands in your terminal before running the app:
```
pip install jupyterlab
```
---

## Usage

The App imports and cleans the bitcoin price data from the two csv's before visualizing the data from the two exchanges overlaid:

![Image of overlaid data](https://user-images.githubusercontent.com/96391748/150264689-17f4d25d-c60c-4592-8a50-ac4a8dc74503.PNG)

In addition, it creates similar graphs for an early, middle, and late time period from the data in addition to box plots for each section such as the following:

![Box Plot](https://user-images.githubusercontent.com/96391748/150264919-7484bc66-8973-4c54-8e3f-31b54bc401dd.PNG)

Finally, it searches for arbitrage opportunities on the chosen dates in the beginjning, middle, and end of the dataset creating summaries of the opportunities:

![Data Summary](https://user-images.githubusercontent.com/96391748/150265240-f9874f52-120b-47a4-a870-9951634d0dce.PNG)

And, finally, creating a graph visualizing the cumulative sum of the profits if you take advantage of the arbitrage opportunities:

![Cumulative Sum](https://user-images.githubusercontent.com/96391748/150265308-062d20fe-0671-41af-9d22-e6eda7f5fa36.PNG)

---

## Contributors

* Nicklaus Danialy nickdanialy@gmail.com 

---

## License

Copyright (c) [2021] [Nicklaus Danialy]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE