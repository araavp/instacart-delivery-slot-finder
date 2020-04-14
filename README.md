# instacart-delivery-slot-finder
Mac Script that notifies you once a delivery slot in available on Instacart


# DISCLAIMER
I don’t guarantee that slots will be found when you’re running the script or whether the slot will remain open during the time you are checking out your Instacart order. Feel free to post concerns in the Issues section if you run into any problems with the service.


# Updates
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

Make sure to quickly checkout because slots will be filled out very fast. Often, you will have to wait for multiple slots because they might fill up during the time in which you complete checking out.


# Inspiration
COVID-19 caused my family, and many others in my community, to scramble for basic necessities like toilet paper, food, cleaning supplies, etc. Services like Instacart, Amazon Whole Foods were busy and many struggled to place their order. As my parents are more vulnerable to COVID-19, as well as other families with grandparents and other elderly family members, I wanted to create an easier process for my parents to order basic necessities from the comfort of our home. I realized that many other families run into similar issues, so I want to publicly release this code for everyone to use. I would like to also thank Adrian Hertel for inspiration to actually tackle this issue and make a working script.


# Comments/Questions
Any comments and/or questions that you don't want to add to the Issues tab can be redirected to: araavp@berkeley.edu
