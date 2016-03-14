---
title: Internet Booking Engine
tags: 
  - internet booking engine
  - IBE
  - online booking engine
keywords: "internet booking engine, IBE, online booking engine"
last_updated: "January 11th, 2016"
summary: This section describes how to customize the Internet Booking Engine (IBE).
published: true
---







#**Internet Booking Engine Customization**  


Frontdesk Anywhere offers real-time commissionless online bookings on their website through IBE (Internet Booking Engine). Configuring the booking engine is fast, simple and user friendly. IBE 3.5 offers a wide variety of customizations, allowing you to configure its style to complement your website. Rooms can be sold online with multiple pictures, promotion codes and up-sell items.

Your account's booking engine can be accessed using the below URL:

https://bookings.frontdeskanywhere.net/#account/XXXXXXXX

Replace XXXXXXX with your Frontdesk Anywhere account number. You can find this number on the Frontdesk homepage, right next to your property's name:  


![ibe.png]({{site.baseurl}}/images/ibe.png)


This guide covers the set-up of IBE 3.5 and selling POS products on your website.


##**IBE Customization**  

In order to configure and personalize your IBE, you will need to have access to the _Admin Settings_ control panel in your Frontdesk Anywhere account.

You will see a full list of links dedicated to IBE:  

![ibe2.png]({{site.baseurl}}/images/ibe2.png)


Here you  will find a list of the main settings that need to be configured in order to begin using the Frontdesk Anywhere booking engine.


##**Promo Code List**

IBE allows you to create special promotions that will only be visible to certain customers. For example, you may want to create a special rate valid only for returning customers: giving them a promo code will enable these guests to access a discounted or specific negotiated rates. 

Setting up a promo code is a three-step process.

1. [Set-up the rate](http://docs.frontdeskanywhere.net/build/rates_set_up.html) for your promotion, making sure to tag it as available on the IBE channel. 


![IBE_2.png]({{site.baseurl}}/images/IBE_2.png)


2. Click on the link _Promo Code List_ under section **IBE**:


![IBE_3.png]({{site.baseurl}}/images/IBE_3.png)



- Click on the blue button _Add a Promo Code_:  


![IBE_4.png]({{site.baseurl}}/images/IBE_4.png)



Enter the promo code (not case sensitive, no spaces), descriptive name for your reference and the start and end sale dates and finally tag the rate(s) which you created in the first step.

The start and end sale dates lets you offer your promotions only during a set period which does not need to coincide with the stay/rate availability dates. For example, you can offer an “EarlyBird” discount for people researching in the month of March for a stay in August. The promo code would be invalid if used in any other month and the person would see the normal rates available during that time.

Third, go back to the edit screens for the rates you just tagged. Scroll down towards the bottom and you will now see a checkbox allowing you to hide this rate from general availability unless the customer enters the promo code. If this is left unchecked, the rate will be searchable by anyone on IBE regardless of whether they entered the correct promo code.

**Guest Requests:** Set-up pre-defined options that you want to offer your guests. Options appear as check boxes that can be selected on IBE by the customer. Selected options conveniently appear as notes in the guest folio's comments section.

**Confirmation Type:** Choose your booking confirmation as either Email or Credit Card. With either selection the email is required but you can choose to omit the requirement of providing a credit card so the guest is not charged immediately. The email only option is not supported if Credit Card Processing is enabled for your account.

**Assign Room Logic:** 
Assign rooms to IBE bookings: Set whether web bookings are saved with a room assigned or as unassigned.
Enable split IBE bookings: Enable this feature to sell down to the last room available by splitting reservations if a single room is not available for the entire duration. Disabling this feature will prevent splits but will also prevent bookings even though there may still be availability at the property.

**Advanced Booking Period:** Set how many months in advance you allow your inventory to be available online for sale. Values between 2 and 36 months are allowed.

**Upsell Items:** Offer items in your POS inventory to be sold at the time of booking. Items appear on the guest’s bill. Items must first be entered as POS products and then can be selected on this screen. IBE 3.5 allows for pictures to be uploaded for each POS item. This is a great way to illustrate what’s on offer and incentivize the guest to purchase.

**Advanced Options:** There are many different advanced options that may be configured.

- Background Image: Upload an image to use as the background for IBE (JPEG only).

- Background Image Options: Decide whether to display the background image only on the first page of IBE or throughout the whole booking process (default is first page only).

- Promo Code Field: If for some reason you would like to disable all promo codes, you can choose to hide the field here. Otherwise IBE will display the promo code field if there are any valid promo codes.

- Google Analytics ID: Use this to add in your Google Analytics ID to enable Google Analytics tracking on IBE.

- Button Color: Choose the color for buttons as well as the calendar in IBE. Customers usually match or find a complementary color to their logo color.

**Payment Collection Rules**
For Payment Collection Rules to work, make sure that you already have a [payment gateway setup](http://docs.frontdeskanywhere.net/build/accounting.html#payment-processing) for IBE. Also make sure that your confirmation type is set to 'Credit Card'.

You may choose one option from the following four radio boxes:

- Collect First Night Rent: for this option you must choose either a percentage of the first night's rent or a fixed amount.

- Collect Sum of Entire Stay: for this option you must choose the percentage value (usually 100).

- Collect Higher Amount From Options Above: selecting this option will choose whichever total amount is higher from the above options. Make sure that the above percent or fixed fields are filled out properly.

- Authorize Only: This will authorize the credit card for $1.00 to make sure it is a valid credit card, but will not actually charge the customer.

You may also choose the time period within which the rule will be activated as well as create multiple rules. For example, you may wish to create one rule which collects 100% of the entire stay that is enforced only if the arrival date is within one week of the booking date and a second rule which simply authorizes the card for bookings farther than a week away.

These rules are only checked once at the time the booking is made. For instance, using the above example if I made a booking on IBE two months in advance of my arrival date, my credit card would only be authorized. Even when today's date falls within one week of my arrival date, I would not automatically be charged 100% of the entire stay since the rules are only checked at the time the booking is made.



##**Other Options**

Additional settings that are used by IBE can be found in other areas of the Admin Settings.

**Contact Details:** (under 'Property Info') In order to create the best appearance, you should upload a company logo for IBE 3.5. Note - Any logo used should have a white background color and be in JPEG format.

**Room Types:** (under 'Rooms') You may add as many images to IBE as you like and they will display in a gallery. This is a great new feature to allow guests to get the full picture of the room they will be staying at. Simply add 3 pictures at a time, save and then add more. The preferred image type is JPEG.

You may also change the ‘room alias’. The default is ‘room’, but other options can be ‘bed’ or ‘site’ for hostels and campgrounds respectively. IBE will replace the word ‘room’ with the chosen room alias in IBE. Be aware that the title, description, max occupancy, default occupancy, and selected amenities are all displayed by IBE.

**Stay Restrictions:** (under 'Rates') Set special stay restrictions for your online booking guests. Typically, this is used for minimum night stays but can also advertise promotions. Simply enter a start and end date for the period and a message to your guests.

**Close Out Periods:** Use the ‘Stay Restrictions’ option under the Rates tab to close out the dates that people can book rooms for your property online. These close out periods may be for as little as one night or for several months at a time. Create a period by selecting a date range and select the room type(s) to close for that period. An optional description for your reference may be added.

**Published Rooms:** (under 'Rooms') This feature closes out or “protects” a room type from being booked by IBE and the OTA/GDS services.
A value of 0 will free sell all available rooms each night.
A value equal to the total number of rooms in a room type will close it from being sold online.
A value in between 0 and the total for a room type will stop selling that room type when your room availability is down to the number entered.

**Categories:** (under POS) Define the categories that will be displayed on IBE for POS items. Only categories that have POS items that are assigned to be shown on IBE will be displayed.

**Products:** (under POS) Any POS item that will be included in IBE should be accompanied by an image that illustrates the item for sale. You must keep POS item descriptions under 255 characters long.

**Guest Messages:** (under 'General') IBE uses three of the guest messages during the booking process.

- **Invoice message:** shown to the guest on the booking page, confirmation page and sent in the confirmation email

- **Cancellation Policy:** shown to the guest on the booking and confirmation pages.

- **Terms & Conditions:** Shown in a separate window that the guest must click on a link to open. Guests must check a box stating they agree to the terms prior to the booking being made.


##**Publishing the IBE Site**  

Publishing your IBE site is easy to do and requires very little HTML skills. We offer IBE 3.5 in a responsive format that will automatically adjust the width down to 320 pixels.  IBE’s responsiveness works well for mobile devices and embedding into websites ensuring a smooth booking process no matter what the platform.

There are two easy ways to add IBE to your site:

- **Button link (recommended):** Place a link on your website that takes people directly to your IBE page.  Since the link is responsive, the booking engine will be optimized for a variety of mobile devices. This is the recommended option as guests will have the optimal booking experience through using a button link.

- **Iframe:** You can embed your IBE page within your website using an iframe. There are many tutorials online to show you how to do this. Your webmaster can do this is in just a matter of a few minutes. We do NOT recommend iframes for mobile websites because it creates a much clumsier user experience as well as possibly interfering with some of the responsiveness of the site.

Below is an example iframe code for embedding IBE on your website. Replace the XXXXXXX in the URL with your account ID.
```
	<iframe src="https://bookings.frontdeskanywhere.net/#account/XXXXXXXX/"style="border: none;" frameborder="0" width="100%" height="700px" scrolling="no"></iframe>
```

Be sure to place the link to your booking page prominently on every page of your site!

**SSL Features**
Your IBE booking engine is protected by SSL encryption, which means you and your guests’ data is secure during transmission. If you use an embedded iframe, your guests will not be aware that their data is protected. You may wish to purchase an SSL certificate for your website so that these guests have even further reassurance that their information is safe.

##**IBE Booking Link Parameters**

There are several parameters that can be used with IBE in order to give a more customized experience to your guests. Used in conjunction with a calendar picker booking widget this enables you to provide a highly customized experience for your users. With the link parameters you can:

- Display only desired room types for a given promotion

- Display only the rate available for a promotion

- Bypass the calendar page and skip to the available rooms

- Display the rates and associated rooms tied to a promo code

- Define a specific source, for example if you embed IBE on your Facebook Business page

**IBE Link Parameter**

IBE uses the following URL parameters to restrict the results offered to the user.

rt= Shows only the room type(s) selected. Use commas to separate multiple room types.

rate= Shows only the rate(s) selected. Use commas to separate multiple rates.

checkin= Use for the arrival date. Format is YYYY-MM-DD

checkout= Use for the departure date. Format is YYYY-MM-DD

promocode= Pass the promo code entered by the user

source= Use the source name. The source will automatically be entered into the folio

**Example Link**

https://bookings.frontdeskanywhere.net/#account/XXXXXXXX?rt=1,2,3,4&rate=285,286&checkin=2012-12-14&checkout=2012-12-15&promocode=test&source=facebook

When the guest is sent to the above link for your property it will take them directly to the available rooms page and show only rates 285 and 286 for room types 1, 2, 3 and 4 for the night of December 14, 2012. The source on the reserved folio will automatically be set to facebook.

Only the checkin and checkout parameters must be used together. The other options may be excluded or used separately as desired.
