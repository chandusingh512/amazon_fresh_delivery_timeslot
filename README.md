# Amazon Fresh Delivery Timeslot 
Written in Python 3.7.4  
Supports **MacOS, Linux, Windows**.  
Requires: **bs4, selenium, twilio**  
  ```pip install bs4, selenium, twilio```  


Download webdriver from: https://chromedriver.chromium.org/  
Add full path to line: ```driver = webdriver.Chrome("path-goes-here:/chromedriver", options=chromeOpts)```  
or add location of webdriver to PATH 

Use amazon_fresh_delivery_timeslot_windows.py for Windows  

Linux and MAC users may need to install SOX  
**Linux:** sudo apt install sox  
**MAC:** sudo port install sox  

Replace username/password under Amazon credentials.  
Uncomment and add Twilio configuration to recieve texts when delivery slots are available.


# Compatible with this page
![alt_text](https://github.com/wfleisher/amazon_fresh_delivery_timeslot/blob/master/images/example-page.png)

# Example Cli
![alt_text](https://github.com/wfleisher/amazon_fresh_delivery_timeslot/blob/master/images/example-cli.png)
