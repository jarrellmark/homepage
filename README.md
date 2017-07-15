# Homepage

## Resume

* [View](https://docs.google.com/document/d/15xWJIhmr2CSUQkIFvXkPZtgQQyC-rm3hHiZdomM4tdU/pub)

## Projects

### Neighborhood Mood

* View
  * [article](https://medium.com/@jarrellmark/goodbye-spark-streaming-hello-aws-kinesis-analytics-37ccf0bc2e5e)
  * [code](https://github.com/jarrellmark/neighborhood_mood_aws)
* Description
  * Demo app mapping neighborhood moods using Twitter and Kinesis.
* Story
  * At first, I was trying to learn about processing streams using Apache Spark. I then ran into a new product at the time, AWS Kinesis.

### MarketOwl

* View
  * [website](https://marketowl.io)
* Description
  * Web application helping day traders minimize risk by sticking to rules.
* Story
  * Creating this product was a 1.5 year effort by 3 people including myself. We were trying to create a useful tool for ourselves and others.
  
### Simple Trading Algorithm

* View
  * [code](https://github.com/jarrellmark/trading_algorithms/tree/master/simple)
* Description
  * Backtests a simple trading algorithm using pyAlgoTrade.
  * The algorithm
    * index = the 30 stocks in the DOW 30
    * portfolio = null
    * each day:
      * sell all stocks in portfolio
      * yesterdays_top_5 = yesterday's 5 gainers from index. A gain means a percent change and can be negative (if every stock in index lost for example)
      * buy yesterdays_top_5 into portfolio
  * Hypothesis behind the algorithm
    * The weather today is like the weather tomorrow except for when it's not.
    * Applied to stocks instead of weather.
* Story
  * I have an interest in finance and wanted to see what open source backtesting libraries were available.

### The Fancifier

* View
  * [code](https://github.com/jarrellmark/fancifier)
* Description
  * Enhances text. Replaces each word greater than 3 characters in the input with a _fancy_ synonym. _Fancy_ means long.
* Technical Details
  * Uses an Ajax call to prevent the page from refreshing.
  * Backend logic done in PHP.
* Story
  * This was created at a Hackathon in 2012.

### uCapsule

* View
  * [code](https://github.com/jarrellmark/uCapsule)
* Description
  * Mobile site simulating a fully loaded iPod.
  * Input is a list of artists. Upon clicking an artist, an album list is retrieved. Upon clicking an album, a song list is retrieved. Upon clicking on a song, a video is retrieved from YouTube.
* Technical Details
  * Implemented entirely in client-side HTML5 and Javascript.
* Story
  * I created this app over a spring break in college to learn about AJAX, Javascript, and mobile-first design.

### Deck of Cards

* View
  * [code](https://github.com/jarrellmark/deck)
* Description
  * A deck of cards implemented in Ruby on Rails.
