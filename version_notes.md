---
title: Version Notes
tags: 
  - Version Notes
keywords: "version, notes, enhancement"
last_updated: "February 26th, 2016"
summary: "In this section you will find notes about any enhancement made to the software and the corresponding version!"
published: true
---

  
  
  
  
**v3.2.21.3**  
Enhancement | Description  
--------|----------  
Improvement - Server Optimization | Our server has been optimized to enhance the speed of the application.  
Bug Fix - Ability to load and print POS receipt | Pos receipts are now correctly loading and printing.
Improvement - Currency Display  | The display of the user's selected currency is now consistent on all work area of the application.
Bug Fix - Typos appearing in Templates  | Templates have been improved to display the correct values when more than four decimals appear in the folio balance.


**v3.2.17.1**  
 
Enhancement | Description     
--------|----------          
Improvement - Email Rules Functionality Rebuild | The email rules functionality that handles scheduled emails has been rebuilt to diminish the chance of issues when multiple rules are configured.   
Bug Fix - Released Folios appearing on Tape Chart as Hold | A case where released reservations appeared on the Tape Chart was reported. The issue has now been fixed, and we placed some checks to prevent these cases from happening in the future.  
Bug Fix - Issue in saving details to Travel Agent/Company profiles | Details saved to TA or Company profiles types were not showing in the profile tab, causing issues with operations performed on those profiles.
Bug Fix - Failed IBE reservations appearing as Hold rooms on the Tape Chart | Reservations that failed on IBE were appearing as Hold rooms on the Tape Chart. We have placed checks and improved handling of these cases.
Improvement - Improved consistency across Email Templates | Templates previously appeared in two forms, we have now built consistency around the template type.
  


**v3.2.15.1**  
 
Enhancement | Description   
--------|----------      
Improvement - Order Floors in Housekeeping Tab | Floors in the Housekeeping Tab are now organized in a progressive order if the floors are numbered, or in alphabetican order, if the floos names are spelled out.
Improvement - Clean Up Payment Gateway Authorization Capture | Users are not anymore allowed to perform an authorization on a credit card with a $0 amount; we have also implemented error messages that will inform users of errors that might come up when transactions fail on payment gateway. These messages are feeding from the payment gateway response to the user's transaction.    
  
**v3.2.14.1**  
 
Enhancement | Description   
--------|----------    
Bug Fix - Display Issue | Display Issues in the Special request page under the Admin Setting Section _IBE_ has been corrected.  
Enhancement - Currency | The Moroccan currency Dirham (D) has been added to the system.  

**v3.2.12.3**  
 
Enhancement | Description   
--------|----------  
Improvement - Ability to Edit Rooms | Ability to deactivate rooms containing cancelled reservations | Cancelled reservations were previously preventing users from deactivate room types: we have amended this, and enable room type/room deactivation where cancelled reservations are present.  
Bug Fix - Room Order Link | Room Order link in the Admin Settings got previously broken but it has ow been fixed!  
Bug Fix - Ability to apply _Authorizations_ to folio charges | Authorization cannot be applied anymore to room charges: if they are, they do not count towards the balance of the invoice containing the charges.  
Improvement - IBE showing **Sold Out** message | When looking for rooms on your IBE, your guests will now be able to see all room types available at the property: the ones with no availability will appear with a _Sold Out_ message!  


**v3.2.11.1**  

Enhancement | Description   
--------|----------  
Bug Fix - Alerts | Alerts functionality scope has been limited to pre-defined cases: the user is now able to define exactly what housekeeping status should trigger a certain alert.
Improvement - Housekeeping Colors Legend | The slide panel for color legend has been updated with the Housekeeping colors.  
Improvement - Templates Optimization | Optimization on templates has been performed: all templates are now rendering good when sent via email.  


**v3.2.9.1**   
 
Enhancement | Description  
--------|----------  
Bug Fix - No Rate Error coming up in Group Reservation module | Room types that have no rates assigned are now appearing with an _No Rate Available_ error before the user can complete the action.  
Bug Fix - No Rooms Left Error coming up in Group Reservation module | Implemented an automatic error _No Rooms Left_ to show in the Group module for users trying to book room types with no inventory available.  
Improvement - Ability to add extra items with a 0 quantity | Extra Items with zero quantity will now figure in the Invoices with a $0 value.
Enhancement - New Payment Screen | We have implemented a new payment screen, to keep track of applied and unapplied payments. We are also showing the remaining balance in the Payment module, as well as in the reservation folio.  



**v3.2.6.1**   

Enhancement | Description  
--------|----------  
Improvement - Housekeeping Tab | We have enhanced the Housekeeping tab to be fully functionable: the _Daily Check-list_ link has disappeared, and it has been replaced by a full printable module. Check-out the _Housekeeping Tab_ section of this manual to get all information on how to use our Housekeeping module.  
Improvement - Order Rooms Link | You can now order your rooms on your Frontdesk Module and decide room assignment priority for all reservations coming from third-parties sited and your booking engine.   
Improvement - Check-in List Loading Graphic | We have improved our graphic for loading information: the display now gives you a hint that the search is being undergone.  
Bug Fix - Filters in the Reservation Lists | Our room types filters are now working correctly for the Check-in/out lists and the Reservation List.  
Bug Fix - Comments do not impact Reservation List | Comments placed in reservation folios were updating the date the reservation was made to the date the comment was inserted.  
Bug Fix - Frontdesk User Defined Colors Reverting to Default Colors | We found that certain system configuration types were causing Frontdesk User Defined Colors to change overnight. We have enlarged the scope to include al types of configuration and ensured that colors that are user defined will not revert to the original color.


**v3.2.4.1** 

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
