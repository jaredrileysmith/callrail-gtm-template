# callrail-gtm-template
This is an unofficial Google Tag Manager template for the CallRail Dynamic Number Insertion tag.

# Deployment Instructions
This template requires two valid user inputs in order to be saved.  The first is the Account Number (the nine-digit number that references the ID CallRail assigns to your account when it is created) and the second is the Company ID (a 20 character alphanumeric string assigned to a company upon creation in your account).  Both the Account Number and Company ID can be found in CallRail JavaScript snippet generated when each Company is created.  The image below is from the [CallRail website](https://www.callrail.com/).

![image](https://user-images.githubusercontent.com/26010307/70452536-e2146900-1a6c-11ea-8d41-99af639db9ce.png)

The Account Number is the **bold** part of the example below (from image above)
cdn.callrail.com/companies/**123456789**/abcdefghijkl123456/12/swap.js

The Company ID is the **bold** part of this example (from image above)
cdn.callrail.com/companies/123456789/**abcdefghijkl123456**/12/swap.js

Input these values into their corresponding fields in the template as seen below
![image](https://user-images.githubusercontent.com/26010307/70453554-95319200-1a6e-11ea-84d3-27fdc344a46f.png)

Finally, give your tag an appropriate trigger and save for publishing in your GTM container.
