# Amazon Fresh Delivery Timeslot 

Supports **MacOS, Linux, Windows**.  
Requires: **bs4, selenium, twilio**  
Written in Python 3.7.4  
Download webdriver from: https://chromedriver.chromium.org/  

Add full path to line 54: ```driver = webdriver.Chrome("path-goes-here:/chromedriver", options=chromeOpts)```  
or add location of webdriver to PATH 

Replace username/password under Amazon credentials.  
Uncomment and add Twilio configuration to recieve texts when delivery slots are available.

# Compatible with this page
![alt_text](https://github.com/wfleisher/amazon_fresh_delivery_timeslot/blob/master/example-page.png)

# Example Cli
![alt_text](https://github.com/wfleisher/amazon_fresh_delivery_timeslot/blob/master/example-cli.png)
