# [Data Visualization](https://material.io/design/communication/data-visualization.html#principles)

<br>

## [Principles](https://material.io/design/communication/data-visualization.html#principles)

<br>

Data visualization portrays dense and comple data of varying types and sizes in graphical form. The resulting visuals are designed to make it easy to compare data and use it to tell a story – both of which can help users in decision making.

* Prioritize data accuracy, clarity, and integrity, presenting information in a way that doesn’t distort it.
* Help users navigate data with context and affordances that emphasize exploration and comparison.
* Adapt visualizations for different device sizes, while anticipating user needs on data depth, complexity, and modality.

<br><hr><br>

## [Types](https://material.io/design/communication/data-visualization.html#types)

### Change over time
Change over time charts show data over a period of time, such as trends or comparisons across multiple categories.

![Change Over Time Charts](https://lh3.googleusercontent.com/1FVHVFOGBmn24yzy89_kF1KYBshEDQNIpO_g9JvMFc9fuQLDfc4WinuouV6dLEmR5xSiMzScG7xoEWEpapIUehp_61euXJ5mM10YRzA=w1064-v0)

<br>

### Category comparison
Category comparison charts compare data between multiple distinct categories.

![Category Comparison Charts](https://lh3.googleusercontent.com/sWcsvo9zlN62ofZ79-mhIxqC_4tp7wKFVAC1tL6s6zm4zrnooSMfLlpvT8nRQQMZkArcS8LqKu-IzbmlpNnpoRzh5jbgrdRMDpr-MRA=w1064-v0)

<br>

### Ranking
Ranking charts show an item's position on an ordered list.

![Ranking Charts](https://lh3.googleusercontent.com/HhGsWg8PwW1BrrIz5Ayi6WJOphU-ucL7TLtUdKBQuYGceaaAb6T16HIdEXeaYZJkWT0KJZhzRpsLhRhYYGZU772HS5Ai_Oe9DygAJqE=w1064-v0)

<br>

### Part-to-whole
Part-to-whole charts show how partial elements add up to a total.

![Part-to-whole Charts](https://lh3.googleusercontent.com/JkGXDgyjM9ks_vXnb5CjC8otM9ta9SbTc37Nd7H_JGOYkcQbTTBRM1IyxQEzRX-UA_dBToUHl8oU0Q20V643NrROlGJK_3IbdnrLXZI=w1064-v0)

<br>

### Correlation
Correlation charts show correlation between two or more variables.

![Correlation Charts](https://lh3.googleusercontent.com/znC2lq_Pnimdwts8F-3F15bxEeFum32vgivU6WnrZxs748JEc56LCAE_8cNPs5AfEKKZKel46uqdcNunowLoKjNpFB5wibtDmNpszw=w1064-v0)

<br>

### Distribution
Distribution charts show how often each values occur in a dataset.

![Distribution Charts](https://lh3.googleusercontent.com/eqQ7PdvmAPsO6NB0nN6lpPky8V2sXCm6F_YdWOJJCYW3CZNYSt7UKKd2kp30be4X2-gjAZw8EGrf072lS-QvGHZnUMTXoXsiF9rSqQ=w1064-v0)

<br>

### Flow
Flow charts show movement of data between multiple states.

![Flow Charts](https://lh3.googleusercontent.com/sXAaq0Qd8ei4veGJcAMCguWZ9SyJ7TczkYdoEzRJBC8fuLmRHQ6ZJUWs9dCLIrmkYOZEmCONIQ4EKexf0dTdE64uLHWWRWb6eJ0X=w1064-v0)

<br>

### Relationship
Relationship charts show how multiple items relate to one other.

![Flow Charts](https://lh3.googleusercontent.com/VbvAFy732XBm9Mhr-svOhf2swZ6zGGebys0mZ5ib_yXToU2-IUR8IKTSLUXLFqBdGqMqGs-Rf09c0NcvuOw5MJwDrVF8aldxl_ybPA=w1064-v0)

<br><hr><br>

## [Selecting charts](https://material.io/design/communication/data-visualization.html#selecting-charts)

### Showing change over time
Change over time can be expressed using a time series chart, which is a chart that represents data points in chronological order. Charts that express change over time include: line charts, bar charts, and area charts.

<br>

| Type of chart | Usage | Baseline value (starting value on y-axis) | Quantity of time series | Data type |
| ------------- | ----- | ----------------------------------------- | ----------------------- | --------- |
| Line chart | To express minor variations in data | Any value | Any time series (works well for charts with 8 or more time series) | Continuous |
| Bar chart | To express larger variations in data, how individual data points relate to a whole, comparisons, and ranking | Zero | 4 or fewer | Discrete or categorical |
| Area chart | To summarize relationships between datasets, how individual data points relate to a whole | Zero (when there’s more than one series) | 8 or fewer | Continuous |

<br>

### Bar and Pie Charts
Both bar charts and pie charts can be used to show proportion, which expresses a partial value in comparison to a total value.

* Bar charts express quantities through a bar’s length, using a common baseline
* Pie charts express portions of a whole, using arcs or angles within a circle

Bar charts, line charts, and stacked area charts are more effective at showing change over time than pie charts. Because all three of these charts share the same baseline of possible values, it’s easier to compare value differences based on bar length.

![Bar and Pie Charts](../assets/bar-and-pie-charts.png)

<br>

### Area charts

Area charts come in several varieties, including stacked area charts and overlapped area charts:

* Stacked area charts show multiple time series (over the same time period) stacked on top of one another
* Overlapped area charts show multiple time series (over the same time period) overlapping one another

![Area Charts](../assets/area-charts.png)

<br><hr><br>

## [Style](https://material.io/design/communication/data-visualization.html#style)

Area charts come in several varieties, including stacked area charts and overlapped area charts:

* Stacked area charts show multiple time series (over the same time period) stacked on top of one another
* Overlapped area charts show multiple time series (over the same time period) overlapping one another

![Area Charts](../assets/area-charts.png)
