# instacart-delivery-slot-finder
Mac Script that notifies you once a delivery slot is available on Instacart

# Versions
Latest Version: Version #6 4/18/20 6:35 PM PST. If you receive notification for delivery slot available when the website still shows "No delivery times available", please download file again.

-Version #5 4/18/20 6:25 PM PST. If you receive this error: error "The variable input is not defined." number -xxxx from "input" Please redownload the instacart-deliveryslot-finder.scpt file.
- Version #4: 4/18/20 4:43 PM PST. If you receive notification for delivery slot available when the website still shows "No delivery times available", please download file again.
- Version #3: 4/14/20 11:20 PM PST. If you want a faster version, please download again. Version #2 should also work fine.
- Version #2: 4/14/20 10:18 PM PST. If you receive this error: error "The variable input is not defined." number -xxxx from "input" Please redownload the instacart-deliveryslot-finder.scpt file.
- Version #1: 4/13/20 10:40 PM PST. Please download again to get the latest update.

# DISCLAIMER
I don’t guarantee that slots will be found when you’re running the script or whether the slot will remain open during the time you are checking out your Instacart order. Feel free to post concerns in the Issues section if you run into any problems with the service.

# Updates
- After running the script, let the script minimize the window (should take around 20-30 seconds), then proceed to carry on with computer use. 

- 4/18/20 6:35 PM PST. If you receive notification for delivery slot available when the website still shows "No delivery times available", please download file again.
- 4/18/20 6:25 PM PST. If you receive this error: error "The variable input is not defined." number -xxxx from "input" Please redownload the instacart-deliveryslot-finder.scpt file.
- 4/18/20 4:43 PM PST. Fixed false notification error.
- 4/14/20 11:20 PM PST. Faster version.
- 4/14/20 10:18 PM PST. If you receive this error: error "The variable input is not defined." number -xxxx from "input" Please redownload the instacart-deliveryslot-finder.scpt file.
- 4/13/20 10:40 PM PST: Enhanced to notify when a fresh food item is not available.

I will continue to release updates and bug fixes to this script as they arise/suggested.

# Instructions
1. Download instacart-deliveryslot-finder.scpt
2. Open Safari on your Mac
3. Open Safari Preferences (command + comma key)
4. Click Advanced
5. Checkmark the “Show develop menu in menu bar” option
6. Go back to Safari window
7. Click Develop on the Menu Bar
8. Enable “Allow JavaScript from Apple Events”
9. Open Instacart and fill up your cart
10. Go to Checkout after you have placed everything you wanted in your cart
11. Choose your delivery address
12. Your screen should show an Image with 'No Delivery times available'
13. Open up the downloaded script in Script Editor and click the Run Button (3rd Button on the top)
14. Make sure your volume is on because the script will give a sound notification once a delivery slot becomes available


# How the Script Works
1. Opens a new window with Instacart and refreshes it around every 30 seconds
2. Checks to see if a delivery slot is available
3. If it is available, it will send a desktop notification with sound and/or an email if you had selected the option

Make sure to quickly checkout because slots will be filled out very fast. These workers risk their lives and are often not paid well, so please remember to tip well!


# Inspiration
COVID-19 caused my family, and many others in my community, to scramble for basic necessities like toilet paper, food, cleaning supplies, etc. As the pandemic got worse, many families could not go to stores in person and relied on services like Instacart. However, these services quickly became busy and many families struggled to place their order. I saw my parents spending hours placing an order on Instacart, which inspired me to come up with a solution. I realized that many other families run into similar issues, so I want to publicly release this code for everyone to use. I would like to also thank Adrian Hertel for inspiration to actually tackle this issue and make a working script.


# Comments/Questions
Any comments and/or questions that you don't want to add to the Issues tab can be redirected to: araavp@berkeley.edu
