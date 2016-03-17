---
title: Version Notes
tags: 
  - Version Notes
keywords: "version, notes, enhancement"
last_updated: "February 26th, 2016"
summary: "In this section you will find notes about any enhancement made to the software and the corresponding version!"
published: true
---




**v3.2.3.1** 
Enhancement | Description  
--------|----------  
Improvement - Clean CSS font | Improvement made on CSS for font.



**v3.2.3.1** 

Enhancement | Description  
--------|----------  
Bug Fix - Housekeeping Checklist printing Extra Pages | We have taken off the number of extra pages that were being printed with the Housekeeping Checklist.  
Bug Fix - Ability to Save Templates | All templates can now be saved in the _Admin Settings_, including the InvoiceBaseTemplate.  
Improvement - New Credit Card Swiper Panel in POS tab | Credit Card Manager in the POS tab has now been improved to have all card fields non-editable when card information is loaded into the system via credit card swiper.  
Enhancement - Options to Push Availability to Channels | You can now decide whether to perform a simple push of information to your integrated channels, or whether you want to re-calculate the availability and push it to all channels.



**v3.2.1.2**   

Enhancement | Description  
--------|----------  
Improvement - New Availability Architecture | We have changed the way our application handles availability across channels. Sending updates on availability is now a faster process. 
Enhancement - Protecting Availability on Different Channels | You can now protect availability on different channels, for different values. Check out section _Published Roms_ of section **Rooms** in this manual.  


  

**v3.1.27.3**   


Enhancement | Description  
--------|----------  
New Feature - Reputation Tab | Reputation tab is now available for all accounts. You can find this on top of your Tape Chart. It is readily available for all users under _All Access/ Super Administrator_ User Level; all other User Levels might need to be adjusted in order include the display of this area. The Reputation tab offers the last five reviews for the property, a breakdown of the number of reviews from channels and the property's ranking. Properties will need to have at least a Tripadvisor page: before anything gets displayed in the tab, you will need to contact our Operation Team at help@frontdeskanywhere.com to place a request to retrieve the Hotel ID. The Reputation tab is powered by _Revinate_: detailed information in this manual, under section _Reputation_.
Improvement - Admin Settings Links | The _GDA/OTA_ section in the Admin Settings is now called **Integration**. _Taxes_ link has been moved under section **Accounting**.     
Improvement - Dirty Departing Housekeeping Status has been added | Housekeeping Status Dirty Departing has now been added. Rules needs to be set up in order to see the status being effective on the Housekeeping tab.  
Bug Fix - Implemented reservations fallback strategy for reservations coming from OTAs without an existent rate code in FDA | A _Reservation fallback_ strategy will ensure that bookings sent from OTAs to Frontdesk Anywhere without a valid the rate code will be accepted with an Error Code as opposed as failing.
  
**v3.1.25.3**  

Enhancement | Description  
--------|----------    
Improvement - Templates now support different combinations for Inclusive Taxes/Fees | Our Invoice Tax is now able to show Inclusive Taxes on extra items as well as room charges, and to provide different combinations between each inclusive tax and the total sum. Please contact our Support team at help@frontdeskanywhere.com to place a request for the new template.
Bug - Credit Card Swiper is now working on Mozzilla Firefox browser | Credit Card Swipers are now functioning on Mozilla Firefox!  
Enhancement - Tape Chart Status Slide panel is now supported | The _Status_ slide panel on the top right hand side of your Tape Chart is now showing values for daily check-ins/outs, and for all reservation statuses. It also contains a legend for Tape Chart colors.




**v3.1.23.1**  

Enhancement| Description
--------|----------  
New Feature - Credit Card Swiper | The Credit Card Swiper functionality is now working with any card swiper that uses a keyboard emulating credit card reader. You will be able to use this new feature from the Credit Card Manager and Payment screen in any folio, and also from the Credit Card panel in the Profile tab. 
Enhancement - Close Shift on Firefox | The Close Shift function is now working on Mozilla Firefox



**v3.1.22.1**    


Enhancement| Description
--------|----------
Templates - New Group Confirmation available | New Base Confirmation Template added for group reservations. Extra Items (POS/Add-ons) are now appearing on the template. Information typed in the **Guest Receipt Message** in the _Guest Messages_ section of the Admin Settings is now appearing on the confirmation template, thus giving the ability to fill in that space with whatever info they need. 
Off-site Payer for Group Reservations | The option to create an off-site payer for Groups, under Group Rules has been added.   
Documentation Link added to the User's drop down menu | On the top left hand side of the _Frontdesk screen_, under the User's name drop down menu there is now an extra link, called **Documentation **which will automatically re-direct you to the documentation link corresponding to the version of Frontdesk Anywhere you are on!.   



**v3.1.18.1**  

Enhancement | Description
--------|----------
Email Templates - Email Functionality| All templates have been tested on different email providers and on mobile screens: they all display correctly, except the Invoice and Registration Card which will have to be re-done and they are not, at the moment, email friendly.All other templates render good, also when content is edited.
Full CRUD Functionality Implemented| Creation, Read, Update and Deletion functionality has been implemented to al templates. This means that all account administrators have now the privilege to edit their html templates. Tests have been performed on the templates content, but **not on the design**: we remind that changing the design of the template wil most likely result in the same templates not rendering correctly with the associated email functionality.    
Ability to Email and Print Templates from the payment screen (Invoice section) implemented|It is now possible to email and print templates that have been applied to Invoices ( Payments link - Invoices ).
