# BTC-Twitter-App

This is a Python script that tweets the current price of Bitcoin (BTC) along with an image.

## External Libraries

The following external libraries are required:

- tweepy
- Pillow (PIL)

## Usage

To use this script, you need to have API keys from Twitter and CoinMarketCap. Once you have these, follow these steps:

1. Clone this repository.
2. Create a new file named `auth_file.py` in the same directory as `btc-twitter-app.py`.
3. In `auth_file.py`, add your API keys like this:

    ```py
    consumer_key = 'YOUR_CONSUMER_KEY'
    consumer_secret = 'YOUR_CONSUMER_SECRET'
    access_token = 'YOUR_ACCESS_TOKEN'
    access_secret = 'YOUR_ACCESS_SECRET'
    pro_api_key = 'YOUR_COINMARKETCAP_API_KEY'
    ```

4. Install the required external libraries (tweepy and Pillow) using `pip`.
5. Run the script using the command `python btc-twitter-app.py`.
