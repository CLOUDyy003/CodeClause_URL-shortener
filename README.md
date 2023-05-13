# URL-shortener
URL shortener in Python using the Flask web framework.

To run this script, you'll need to install the Flask package by running pip install flask. Once installed, save the code in a file, for example url_shortener.py, and run the script with python url_shortener.py. This will start a local web server where you can access the URL shortener in your browser.

Here's an example of the output you might see when running the code:

Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)

When you visit http://127.0.0.1:5000/ in your browser, you will see a form where you can enter a URL. Let's say you enter https://www.urlshortner.com and click "Shorten". 

The output on the webpage will be:
Short URL: http://127.0.0.1:5000/ABC123

The ABC123 part is the generated short URL for the original URL https://www.urlshortner.com. You can now use this short URL http://127.0.0.1:5000/ABC123 to access the original URL.

If you visit http://127.0.0.1:5000/ABC123 in your browser, you will be redirected to https://www.urlshortner.com.

Note: The actual output may vary depending on your environment and the specific URLs you enter.






