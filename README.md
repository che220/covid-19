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

### 2020-03-12 / 2020-03-13 / 2020-03-14

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

### 2020-03-14

Use quadratic function. The spread is slowing down a bit. This is due to social distancing and reduced outdoor activities.

|Date | Prediction | Actual |
|-----|------------|--------|
|3/15 |   3647     |  3738  |
|3/16 |   4756     |  4669  |
|3/17 |   6146     |  6427  |
|3/18 |   7870     |  9351  |
|3/19 |   9989     | 13611  |

### 2020-03-15

Quadratic function worked well for one day. We need to watch it for a couple of more days. We need the curve to bend down even more. Social distancing is working!

### 2020-03-18

Yesterday's cases are more than forecasted. Looks like the previous lower numbers are simply an indication of inadequate tests. Wearing masks is still expected to be the turning point of this pandemic in the US. I will wait for one more day to check the model again.

Significant higher than forecast. This is the result of more testings.

### 2020-03-19

As testing gets more comprehensive, confirmed cases are growing fast. I have to go back to the linear model. Unless masks are widely enforced, linear model will stay.

|Date | Prediction | Actual |
|-----|------------|--------|
|3/20 |   19255    |  19700 |
|3/21 |   26712    |  26800 |
|3/22 |   37056    |  35120 |
|3/23 |   51405    |  46100 |
|3/24 |   71311    |  55100 |

We will take a look at the curve again after 3/24 data

### 2020-03-24

Looks like the curve is flattening. Use quadratic function again. NYC's method works.

1. widespread testing
2. lockdown

Hopefully other big cities adopt this quickly.

|Date | Prediction | Actual |
|-----|------------|--------|
|3/25 |   72093    |  69150 |
|3/26 |   94449    |  86000 |
|3/27 |  123269    | 104800 |
|3/28 |  160276    | 124600 |
|3/29 |  207605    | 142600 |

Stop updating.
