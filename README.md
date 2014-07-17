# Homepage

## Resume

* View
  * [here](https://docs.google.com/document/d/15xWJIhmr2CSUQkIFvXkPZtgQQyC-rm3hHiZdomM4tdU/pub)

## Projects

### Deck of Cards

* View
  * [demo](http://jarrellmark.duckdns.org:3000/deck_of_cards/1)
  * [code](https://github.com/jarrellmark/deck)
* Description
  * A deck of cards implemented in Ruby on Rails.

### The Fancifier

* View
  * [demo](https://fancifier-c9-jarrellmark.c9.io/index.php)
  * [code](https://github.com/jarrellmark/fancifier)
* Description
  * Enhances text. Replaces each word greater than 3 characters in the input with a _fancy_ synonym. _Fancy_ means long.
* Technical Details
  * Uses an Ajax call to prevent the page from refreshing.
  * Backend logic done in PHP.

### uCapsule

* View
  * [demo](http://jarrellmark.duckdns.org:8081/index.html)
  * [code](https://github.com/jarrellmark/uCapsule)
* Description
  * Mobile site simulating a fully loaded iPod.
  * Input is a list of artists. Upon clicking an artist, an album list is retrieved. Upon clicking an album, a song list is retrieved. Upon clicking on a song, a video is retrieved from YouTube.
* Technical Details
  * Implemented entirely in client-side HTML5 and Javascript.

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
