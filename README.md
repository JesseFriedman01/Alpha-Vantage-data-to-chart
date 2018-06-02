# Alpha Vantage Data to Chart and Base64 Encoding 

Alpha Vantage (www.alphavantage.co) offers free, historical & realtime data on stocks, physical currencies, and digital/crypto currencies, through their easy to use API. 

Converting this raw data to a chart can be a bit more complicated.  Therefore, this script was created to demonstrate how to use Alpha Vantage's API to retrieve this data, format it and plot the data to a chart using matplotlib. 

This script also demonstrates how to encode an image (i.e. a png produced by matplotlib) to base64. A practical application of this can be seen on a portfolio site that I created -- http://165.227.89.136/stocks/

Note: To use this script, you need to:

1. Obtain a free API key from Alpha Vantage (https://www.alphavantage.co/support/#api-key).

1. Create and save "config.py" in the same directory as "AlphaToChart.py" and add the following line:
`	 api_key ="your API key"`

[![AlphaExample](http://206.189.195.136/wp-content/uploads/2018/06/AlphaExample.png "AlphaExample")](http://206.189.195.136/wp-content/uploads/2018/06/AlphaExample.png "AlphaExample")
