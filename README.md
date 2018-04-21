# Coin Market Cap - TradingView watchlist creator
The script below automatically extracts the top 50 (or 100) matched against your desired pair(s). You can then import this as a watchlist into TradingView.com.

Setup process video here (or read the instructions below):
https://www.dropbox.com/s/1brs28ywpe2sm6t/CMC%20scraper%20setup.mov?dl=1

To set it up for use:
1. The code needs to be converted into a bookmarklet so you can access it from your browser bookmarks. 
Go to https://mrcoles.com/bookmarklet/ , paste the code where it says ‘Enter your javascript code here:’, click ‘Convert to bookmarklet’. Copy the code from where it says ‘and here is the code:’.
2. Go to your web browser Bookmark Manager and add a new bookmark. Paste the code you just copied into the ‘URL’ field, and name the bookmark (I’ve called it CMC 100 Scraper’). I’d recommend placing the bookmark on your ‘Bookmarks Bar’ for easy access.

To use:
1. Visit www.coinmarketcap.com
2. Click the bookmark you’ve just created.
3. Follow the prompts (which trading pair(s) do you want? How many of the top 100 do you want?).
4. A text file will automatically be generated and downloaded for you to import into TradingView.com (Import Watchlist…)

Keep in mind some exchanges may use different abbreviations than coinmarketcap.com (ie DSH vs DASH) so this is really just a quick way to get you on your way.

Check out my other repositories for exchange-specific trading pair watchlist creation scripts.