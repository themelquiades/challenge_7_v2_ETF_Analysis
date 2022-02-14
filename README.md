# ETF Return Analysis
7th weekly challenge, analyzing a hypothetical equal-weighted fintech ETF by building a financial database and web application using SQL, Python, and the Voilà library.

As a first step, this analysis pulled in closing price and daily return data on one underlying stock held by the ETF (PYPL) to analyze its performance. 

It then focused on filtering and sorting performance data using SQL queries. 

Finally, the analysis pulled in closing price and daily return information on the 4 stocks held by the hypothetical ETF to calculate the ETF's annualized return and cumulative return from 12/16/16-12/4/20.

To turn the analysis into a web-based application, Voila was run in the termnial, resulting in the webpage shown below:

![Video_voila](/images/ScreenRecording_1.mov)

![Screenshot_voila](/images/ScreenShot_1.png)

## Technologies

This app runs on python 3.7 with the following packages:

* [SQLAlchemy](https://github.com/sqlalchemy) - To synthesize and analyze each stock's performance database

* [Voila](https://github.com/voila-dashboards/voila) - To turn the analysis into a web-based application

---

## Installation Guide

Please install the following dependencies:

```python
  pip install SQLAlchemy
  conda install -c conda-forge voila
```


---

## Contributors

This analysis was created by Nico Cortese with support from the lovely Fintech Coding Boot Camp Team at Boot Camp Spot / Columbia School of Engineering

Nico Cortese

XXX-XXX-XXXX

XXXX@gmail.com

---

## License

MIT License

Copyright (c) 2022 NicoCortese

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
SOFTWARE.
