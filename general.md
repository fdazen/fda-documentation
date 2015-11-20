---
title: General
tags: 
  - formatting
keywords: "guest messages, automated emails, email templates, email rules, languages, modes of arrival, identification types, sources of business, markets, display colors, guest information, reservation information, custom fields, alerts, tape chart."
last_updated: "November 19th, 2015"
summary: Labels are just a simple Bootstrap component that you can include in your pages as needed. They represent one of many Bootstrap options you can include in your theme.
published: true
---

  

#**General**  

The _General_ section of your Frontdesk Anywhere helps you personalize your account, set up hotel messages and configure automatic emails. You will also be able to decide which fields are to be mandatory in any reservation folio, and if necessary you will be given the option to create new ones.  

##**Guest Messages**  

The Guest Messages are messages that will appear in some areas of your Frontdesk Anywhere Online Booking Engine (for example Terms and Conditons) and on your Email Templates. You can think of them as _snippet_ messages that will then be applied to all communications you will set up to have with your guests.  

 - In the Admin Settings, click on the link **Guest Messages** under section _General_:  
 
 ![](1.png]({{site.baseurl}}/images/1.png)  
 
 - You will see different panels, each one editable and with a title on the top that should give you some guidance on what sort of information you should type in the editable box:  
 
 ![](2.png]({{site.baseurl}}/images/2.png)  
 
 - The first one is the _Invoice Message_: this is a message that will appear in each of your property invoices:    
 
 ![](3.png]({{site.baseurl}}/images/3.png)  
 
 - Proceed to edit the _Terms and Conditons_ message: the latter will show up on your Online Booking Engine, and your confirmation email:  
 
 ![](4.png]({{site.baseurl}}/images/4.png)  
 
 - The third message will be the _Room Cancellation_ message: as the text in the box says, this will appear both on your Booking Engine and in your cancellation email:  
 
 ![](5.png]({{site.baseurl}}/images/5.png)  
 
 - Finally, edit your _Guest Receipt_ and your _Registration Card_ messages:  
 
 ![](7.png]({{site.baseurl}}/images/7.png)  
 
 - When finished, scroll at the bottom of the page and click on the blue button _Save_:  
 
 ![](8.png]({{site.baseurl}}/images/8.png)  
 
 ##**Email Templates**  

Frontdesk Anywhere allows you to customize all communications with your guests: all templates are in a html format, and they can be easily editable; however, your account already comes with some defaults templates that you can enable and start using.  

 - In the Admin Settings, click on the blue link **Email Templates** under section _General_:  
 
 ![](9.png]({{site.baseurl}}/images/9.png)  
 
 - You will see a list of all the types of templates that the system offers: the name of each template appears on the top left hand side of each message panel.
 
 ![](11.png]({{site.baseurl}}/images/11.png)  
 
 - Under each section you will see one disabled template already listed: these templates are only used as a guidance, and they are non-editable:  
 
 ![](12.png]({{site.baseurl}}/images/12.png)

 - To create a new template, click on the button _New template_ on the top left hand side of the screen:  
 
 ![](13.png]({{site.baseurl}}/images/13.png)  
 
 - Select the template you want to create by clicking on the right option in the scroll down menu:  
 
 ![](14.png]({{site.baseurl}}/images/14.png)
 
 - Give a name to the template and click on the blue button _Create and Edit_:  
 
 ![](15.png]({{site.baseurl}}/images/15.png)
 
 - The template you have just created will appear as the first template in the apposite panel:  
 
 ![](16.png]({{site.baseurl}}/images/16.png)
 
 - Once the template has been created, it also needs to be enabled. Click on the yellow button _Edit_ on the right hand side of the newly created template:  
 
 ![](17.png]({{site.baseurl}}/images/17.png)
 
 - Enable the template by checking the box next to the tag _Template Enabled_:  
 
 ![](18.png]({{site.baseurl}}/images/18.png)
 
 - Select where you want the template to apply and appear, by checking the right boxes under the written _System Section Filters_:  
 
 ![](19.png]({{site.baseurl}}/images/19.png)  
 
Here is a quick breakdown of what ach box means:  

If you check the box _Invoices_, your template will show up in any reservation folio, by clicking on the blue link _Invoice_:  
 
 ![](20.png]({{site.baseurl}}/images/20.png)  
 
If you check the box _POS_, the template will show up as a Receipt in the _Point of Sale_ area of your PMS:  

 ![](21.png]({{site.baseurl}}/images/21.png)

If the box _Group Messages_ is checked, the newly create template will appear in any Group Folio, at the bottom:  

 ![](22.png]({{site.baseurl}}/images/22.png)  
 
 If you check the box _Reservation Messages_, the template will appear on the bottom left side of each reservation folio:  
 
 ![](23.png]({{site.baseurl}}/images/23.png)  
 
 Finally, if you check on the _Profile Documents_, the template will show in the _Profiles_ area:  
 
 ![](24.png]({{site.baseurl}}/images/24.png)  
 
 - When finished, click on the button _Save_ at the bottom of the screen.
 
 **NOTE**: if you wish to have customized guest messages, please contact our support team at support@frontdeskanywhere.com  


##**Automated Emails**  
 
Once your _Email Templates_ are set up, you can configure the system to automatically send those templates to your guests at key points during their reservation process and stay.  

 - In the Admin Settings, click on the link **Automated Emails** under section _General_:  
 
 ![](25.png]({{site.baseurl}}/images/25.png)  
 
 - The first column _Folio Status Action_ defines what change in the status of any reservation folio will trigger the automatic email

 ![](26.png]({{site.baseurl}}/images/26.png)  
 
 - Under column _Automated E-mail Status_ check the box corresponding to the action you want the system to perform. In the example below I am choosing to have the system to send an automatic email any time a reservation is created:  
 
 ![](28.png]({{site.baseurl}}/images/28.png)  
 
 - Select what email template you want to use by choosing one in the scroll down menu: 

![](29.png]({{site.baseurl}}/images/29.png)  

 - When finished, click on the blue button _Save_ at the bottom of the page:  
 
 ![](30.png]({{site.baseurl}}/images/30.png)  
 

##**Email Rules**  

_Email rules_ is the tool that enables you to send automatic emails outside the sphere of any key event proper of a guest’s stay (reservation confirmation, check-in, check-out, and cancellation). Differently from the _Automated Emails_ where those emails are triggered by some change in the status of a reservation folio, _Email Rules_ do not have any constrain in terms of the time at which the email is sent: you simply set the condition yourself! This comes useful when you want to send a remainder to your guests for their upcoming arrival or at times when you want to send a "thank you" message to your guests after their stay.  

**Note**: you will have to have both _Email Templates_ enabled and _Guest Messages_ set up before placing Email Rules. 

 - In the Admin Settings, click on the link **Email Rules** under section _General_:  
 
 ![](31.png]({{site.baseurl}}/images/31.png)  
 
 - Start by clicking on the blue button _Add Rule_:  
 
 ![](!32.png]({{site.baseurl}}/images/32.png)  
 
 - Fill in all the information: place a title, and select the right options from the scroll down menus:  
 
 ![](33.png]({{site.baseurl}}/images/33.png)  
 
  - Select the email template you want to send among the ones you have previously created. You will also need to select what room type and rates you want to enable for this rule:  
  
  ![](34.png]({{site.baseurl}}/images/34.png)

 - When finished, click on the blue button _Add Rule_ at the bottom of the page:  
 
 ![](35.png]({{site.baseurl}}/images/35.png)  
 

##**Languages**  

Frontdesk Anywhere comes with a few optional languages that you can set up as default for both your OBE and your PMS.

 - In the Admin Settings click on the link **Languages** under section _General_:  
 
 ![](40.png]({{site.baseurl}}/images/40.png)

 - You will see that English, Spanish and French are already loaded in the system: you can select which of these you want to have as default for your Online Booking Engine and for your system by checking the relevant boxes:  
 
 ![](41.png]({{site.baseurl}}/images/41.png)  
 
 - You can also add different languages for some of the items in the system; to do this, click on the blue button _Add a Language_ and fill in all the fields with the appropriate translation:   
 
 ![](42.png]({{site.baseurl}}/images/42.png)  
 
 - When finished, click on the blue button _Save Language_ at the bottom of the page:  
 
 ![](43.png]({{site.baseurl}}/images/43.png)  
 
 **NOTE** Making a certain language the default one does not mean that all users will have the same language upon log-in. Each user can choose a different language for the same account and they can set this up on the _Preferences_ area:  
 
 ![](45.png]({{site.baseurl}}/images/45.png)
 
 Setting up a default language only means that all _new_ users will see the system in that language upon their first log-in.   


##**Modes Of Arrival**  

Create your guest's modes of arrival to keep track of how they come to your property!  

 - In the Admin Settings, click on the link **Modes of Arrival** under section _General_:  
 
 ![](46.png]({{site.baseurl}}/images/46.png)  
 
 - The system comes with a few modes of arrival defaulted in the system:  
 
 ![](47.png]({{site.baseurl}}/images/47.png)


 





 








 
 
 
 

 






