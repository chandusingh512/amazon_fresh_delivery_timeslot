# Amazon Fresh Delivery Timeslot 
Supports **MacOS, Linux, Windows**.  
Requires: **bs4, selenium, twilio**  
  ```pip install bs4 selenium twilio```  

Use amazon_fresh_delivery_autobuy.py to automatically checkout when delivery slot is available.

Download webdriver from: https://chromedriver.chromium.org/  
Add full path to line: ```driver = webdriver.Chrome("path-goes-here:/chromedriver", options=chromeOpts)```  
or add location of webdriver to PATH 
  
Uncomment and add Twilio configuration to recieve texts when delivery slots are available or orders have been placed.


# Compatible with this page
![alt_text](https://github.com/wfleisher/amazon_fresh_delivery_timeslot/blob/master/images/example-page.png)

# Example Cli
![alt_text](https://github.com/wfleisher/amazon_fresh_delivery_timeslot/blob/master/images/example-cli.png)
