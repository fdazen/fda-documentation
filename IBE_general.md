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


###**Promo Code List**

IBE allows you to create special promotions that will only be visible to certain customers. For example, you may want to create a special rate valid only for returning customers: giving them a promo code will enable these guests to access a discounted or specific negotiated rates. 

Setting up a promo code is a three-step process.

1. [Set-up the rate](http://docs.frontdeskanywhere.net/build/rates_set_up.html) for your promotion, making sure to tag it as available on the IBE channel. 


![IBE_2.png]({{site.baseurl}}/images/IBE_2.png)


2. Click on the link _Promo Code List_ under section **IBE**:


![IBE_3.png]({{site.baseurl}}/images/IBE_3.png)



- Click on the blue button _Add a Promo Code_:  


![IBE_4.png]({{site.baseurl}}/images/IBE_4.png)


- Enter the promo code keeping in mind that the promo code is case sensitive and that there should not be any spaces. Using the scroll down calendars, select the start and end date for the promotion:  


![IBE_5.png]({{site.baseurl}}/images/IBE_5.png)



{{site.data.alerts.tip}} The start/end date does not need to coincide with the rate availability dates. For example, you can offer an Early Bird discount for people researching in the month of March for a stay in August. The promo code would be invalid if used in any time outside the promo code calendars scope, and in that case, your guests would only see the normal rates available during that time. {{site.data.alerts.end}} 


- Place a title and a descriptin and finally, select the rates that will be applicable for the Promo Code:  

![IBE_6.png]({{site.baseurl}}/images/IBE_6.png)


Click on the button _Save Promo Code_ when finished.


3. Go back to the Admin Settings, and to the _Rate Edit_ panel for the rates applied to the Promo Code:  


![IBE_7.png]({{site.baseurl}}/images/IBE_7.png)


- Scroll down at the bottom and you will now see a check-box allowing you to hide this rate from general availability unless the guest enters the promo code:  


![IBE_8.png]({{site.baseurl}}/images/IBE_8.png)


{{site.data.alerts.warning}} If this is left unchecked, the rate will be searchable by anyone on IBE regardless of whether they entered the correct promo code. {{site.data.alerts.end}}


###**Guest Requests**

You can set up pre-defined options to offer your guests. These options will conveniently appear at the time the guest finalizes their reservation, and they will be delivered in each folio's _Comment_ box.


###**Confirmation Type**

IBE gives you the ability to choose whether you want reservations get confirmed as either Email or Credit Card. With either selection the email is required but you can choose to omit the requirement of providing a credit card so the guest is not charged immediately. 

- To choose your online reservation confirmation type, click on the link _Confirmation Type_ in the Admin Settings, under section**IBE**:  

![IBE_9.png]({{site.baseurl}}/images/IBE_9.png)

- Select your choice using the scroll down menu, and when finished, click on the blue button _Save Changes_:


![IBE_10.png]({{site.baseurl}}/images/IBE_10.png)


###**Assign Room Logic** 

You can choose if and how you want to assign rooms for reservations coming from your IBE.  


- In the Admin Settings, click on the link _Assign Room Logic_:  


![IBE_11.png]({{site.baseurl}}/images/IBE_11.png)


You will see different option:

_Assign Rooms to IBE Bookings_: if this option is turned on (ON), the system will automatically assign rooms to incoming reservations. If the option is turned off (OFF), all bookings will come in _Unassigned_ status.

{{site.data.alerts.note}} Unassign bookings are not overbookings. An Unassign booking is a booking that does not have any room assigned to it, yet. {{site.data.alerts.end}}

_Enable Split IBE Bookings_: if one single room is not available for the entire reservation duration, but some other room is, the option **ON** will split the reservation into whatever rooms are available. Disabling this feature (OFF) will prevent splits, but will also prevent bookings even though there may still be availability at the property across rooms.

Click on the button _Save Changes_ once all selection has been made:  

![IBE_12.png]({{site.baseurl}}/images/IBE_12.png)


###**Advanced Booking Period**

You can configure how many months in advance you want your inventory to be available online for sale. 

- Click on the link _Advanced Booking Period_ under section **IBE**:  

![IBE_13.png]({{site.baseurl}}/images/IBE_13.png)

- Choose your selection from the scroll down menu. Values between 2 and 36 months are allowed. When finished, click on the button _Save_.   

![IBE_14.png]({{site.baseurl}}/images/IBE_14.png)



###**Upsell Items** 

You can sell any active POS item on your IBE. Items will appear on the guest’s confirmation email, and they will appear in each folio, under the POS section.
You can also add pictures to be uploaded for each POS item. This is a great way to illustrate what’s on offer and incentivize the guest to purchase.

Before starting, click [here](http://docs.frontdeskanywhere.net/3_1_27_3/point_of_sale.html) to learn how to set up your POS items.  


- To add POS items to your IBE, click on the link _Upsell Items_:  


![IBE_15.png]({{site.baseurl}}/images/IBE_15.png)

- Click on the check-box _Allow Packages_ to enable upselling extra items on IBE: 


![IBE_16.png]({{site.baseurl}}/images/IBE_16.png)


- You can amend the text that will be shown on IBE in the Upsell Items section, when a guest is reserving their room:  


![IBE_17.png]({{site.baseurl}}/images/IBE_17.png)  


- Check the box next to the item you want to offer on IBE, and when finished, click on the blue button _Save Changes_.     


![IBE_18.png]({{site.baseurl}}/images/IBE_18.png)



###**Advanced Options**

There are many different advanced options that may be configured for IBE!

_Background Image_: Upload an image to use as the background for IBE (JPEG only). Click on the button _Choose File_ to browse one from your PC.    

_Background Image Options_: Decide whether to display the background image only on the first page of IBE or throughout the whole booking process (default is first page only).

![IBE_19.png]({{site.baseurl}}/images/IBE_19.png)


_Promo Code Field_: You can make the _Promo Code_ field dynamic, meanining that IBE can display that field only if there is anactive promo code in your account.


_Google Analytics ID_: Use this to add in your Google Analytics ID to enable Google Analytics tracking on IBE. Click on the word **here** to have more information about Google Analytics:  

![IBE_20.png]({{site.baseurl}}/images/IBE_20.png)



_Button Color_: Choose the color for IBE buttons as well as  for the IBE calendar. Customers usually match or find a complementary color to their logo color.


##**Payment Collection Rules**   


Payment Collection Rules only work if you have already a [payment gateway setup](http://docs.frontdeskanywhere.net/build/accounting.html#payment-processing) which is also active for IBE. The confirmation type for IBE also is to be set to _Credit Card_.
These rules are to set up the system to automatically charge your guests when they finalize their reservations. 


- Click on the link _Payment Collection Rules_ under section IBE:  


![IBE_21.png]({{site.baseurl}}/images/IBE_21.png)


- You will need to choose your option from the ones available ont he screen. Here is a breakdown:  


_Collect First Night Rent_: choose this option if you want to charge your guests only on the price of the first night of their booking. You will need to specify either a percentage or an amount: the latter will be calculated on the first night rent only:  

![IBE_22.png]({{site.baseurl}}/images/IBE_22.png)


_Collect Sum of Entire Stay_: this option will have the system charge the guest a specific percentage which is calculated on the sum of their entire stay.   


![IBE_23.png]({{site.baseurl}}/images/IBE_23.png)


_Collect Higher Amount From Options Above_: selecting this option will have the system charge whichever total amount is higher among the options defined before. Hence, if you choose to go for this option, make sure the previous two are defined.  


_Authorize Only_: If you do not want to charge your guests, bu you only want to authorize theirt card, then you will need to choose this option. This comes handy if your only goal is to make sure that the guest is using a valid credit card for their booking. The authorization that will be processed is of $1.00 and it will not be charged on your guest's bill or credit card bill.


 - You will also need to choose the time period within which the rule will remain active as well as create multiple rules. For example, you may wish to create one rule which collects 100% of the entire stay that is enforced only if the arrival date is within one week of the booking date, and a second rule which simply authorizes the card for bookings farther than a week away.

{{site.data.alerts.note}} Payment Collection rules are only checked once at the time the booking is made. {{site.data.alerts.end}}



##**Other Options**

Additional settings that are used by IBE can be found in other areas of the Admin Settings.

**Logo** (under section _Property Info_). In order to create the best appearance, you should upload a company [logo](http://docs.frontdeskanywhere.net.s3-website-us-west-1.amazonaws.com/build/property_info.html) for IBE. 

{{site.data.alerts.important}} Any logo used should have a white background color and be in JPEG format. {{site.data.alerts.end}}

**Room Types Pictures** (under section _Rooms_). You may add as many images to IBE as you like, and they will display in a gallery. This is a great new feature to allow guests to get the full picture of the room they will be staying at. Simply add 3 pictures at a time, save and then add more. The preferred image type is JPEG.

You may also change the _Room Alias_. The default is ‘room’, but other options can be ‘bed’ or ‘site’ for hostels and campgrounds respectively. IBE will replace the word ‘room’ with the chosen room alias in IBE. Be aware that the title, description, max occupancy, default occupancy, and selected amenities are all displayed by IBE.

**Stay Restrictions** (under section _Rates_). Set special restrictions for IBE.


**Published Rooms:** (under section _Rooms_). You can check how to hide inventory from your online booking engine by clicking [here](http://docs.frontdeskanywhere.net.s3-website-us-west-1.amazonaws.com/build/rooms_set_up.html)


**Guest Messages** (under section _General_) IBE uses three of the [guest messages](http://docs.frontdeskanywhere.net.s3-website-us-west-1.amazonaws.com/build/messages_and_emails.html) during the booking process. 

**Invoice message:** shown to the guest on the booking page, confirmation page and sent in the confirmation email

**Cancellation Policy:** shown to the guest on the booking and confirmation pages.

**Terms & Conditions:** Shown in a separate window that the guest must click on a link to open. Guests must check a box stating they agree to the terms prior to the booking being made.
