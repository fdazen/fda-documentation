---
title: Publish IBE
tags: 
  - publish IBE
keywords: "publish, IBE, website"
last_updated: "March 14th, 2016"
summary: "Follow these simple instructions to embed your IBE in your website and start receiving bookings!"
published: true
---





##**Publishing IBE on your Website**  

Publishing your IBE site is easy to do and requires very little HTML skills. We offer IBE 3.5 in a responsive format that will automatically adjust the width down to 320 pixels.  IBE’s responsiveness works well for mobile devices, and embedding it into websites ensures a smooth booking process, no matter what platform you are using!

There are two easy ways to add IBE to your site:

- **_Book Now_ link (recommended):** Place a link on your website that will take your guests directly to your IBE. Since the link is responsive, the booking engine will be optimized for a variety of mobile devices. This is our recommended option as guests will have the optimal booking experience through using a button link.

- **I-frame:** You can embed your IBE within your website using an i-frame. There are many tutorials online to show you how to do this. Your webmaster can do this in just a matter of a few minutes.   

{% include warning.html content="We do NOT recommend i-frames for mobile websites because it creates a much clumsier user experience as well as possibly interfering with some of the responsiveness of the site." %}

Below is an example i-frame code for embedding IBE on your website. Replace the XXXXXXX in the URL with your account ID.
```
	<iframe src="https://bookings.frontdeskanywhere.net/#account/XXXXXXXX/"style="border: none;" frameborder="0" width="100%" height="700px" scrolling="no"></iframe>
```

Be sure to place the link to your booking page prominently on every page of your site!

**SSL Features**  


Your IBE booking engine is protected by _SSL encryption_, which means you and your guests’ data is secure during transmission. If you use an embedded iframe, your guests will not be aware that their data is protected. You may wish to purchase an SSL certificate for your website so that these guests have even further reassurance that their information is safe.
  
  
##**IBE Booking Link Parameters**

There are several parameters that can be used with IBE in order to give a more customized experience to your guests. Used in conjunction with a calendar picker booking widget this enables you to provide a highly customized experience for your users.  
With the link parameters you can:

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
