# COVID-19

Uses data in https://github.com/CSSEGISandData/COVID-19.git

### 2020-03-06 (Removed cases from cruises):

    South Korea and Italy: They started lockdowns. We can see the slowdown of confirmed cases in the log-scale chart.
  
    Japan: Japan's cases grow very slow. hiding info or wearing mask?
  
    US, Germany, and France: Cases are growing exponentially. Slope: France - 0.31 (1.36), Germany - 0.35 (1.42), US - 0.37 (1.45)

    Why does Italy have more deaths than South Korea?

### US Predictions

|Date | Prediction | Actual |
|-----|------------|--------|
|3/7  |   345      |  351   | (Total 67 from boats)
|3/8  |   502      |  517   | (Total 67 from boats)
|3/9  |   731      |  671   | (Total 67 from boats)
|3/10 |   1063     |        
|3/11 |   1546     |        
|3/12 |   2248     |        
|3/13 |   3270     |        


### 2020-03-09

I had to correct the numbers because Johns Hopkins's numbers are inaccurate. Different websites reported anywhere between 707 and 738 cases in US, while JH's reported 607. Obviously JH was wrong.

JH's 3/8 reported number was likely to be wrong as well.

### 2020-03-10

Run regression again up to 3/9. With a few more data points, the slope is 0.35 (1.42). The growth barely slowed down. The correlation is still quite linear.

|Date | Prediction | Actual |
|-----|------------|--------|
|3/10 |   932      |   951  |
|3/11 |   1334     |   1240 |
|3/12 |   1910     |   1690 |
|3/13 |   2734     |   2226 |
|3/14 |   3913     |     

### 2020-03-11

New York State sent in national guards into New Rochelle. This should slow down the growth of confirmed cases.

### 2020-03-12 / 2020-03-13

Significantly lower! We have to observe it for a week or so. Just want to make sure it is not because of inadequate testing.

Rerun regression and predications after 3/12:

|Date | Prediction | Actual |
|-----|------------|--------|
|3/13 |   2528     |   2226 |
|3/14 |   3612     |   2943 |
|3/15 |   5161     |    |
|3/16 |   7374     |    |
|3/17 |   10535    |

Looks like I need a new regression
