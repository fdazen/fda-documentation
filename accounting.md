---
title: Accounting
tags:
  - accounting
keywords: >-
  reports, payments, currency, pay types, credit card, invoices, discount
  reasons, Revenue Labels, Revenue Categories, security deposit
last_updated: 'November 25th, 2015'
summary: >-
  The Accounting section is about all of those settings that have to do payments
  and accounting.
published: true
---











#**Accounting**  

The Accounting section is the place here you configure all those settings that have to do with payments, currencies, credit cards, fiscal year, etc. Most importantly it is home to Revenue Management: you can build Revenue Labels and Categories around which your reports are organized.  

##**Currency**  

During the intial system set-up it is important for you to configure the right currency, as this will be displayed in all guest communications and if applicable, on IBE.  

- Click on the blue link **Currency** under section _Accounting_:


![accounting1.png]({{site.baseurl}}/images/accounting1.png)



 

- Select the right currency among the ones available in the scroll down menu:  

![Accounting_2.png]({{site.baseurl}}/images/Accounting_2.png)


{{site.data.alerts.note}} If your currency is not listed in the drop down menu, please contact our Support Team at help@frontdeskanywhere.com and ask them to have the currency added to your account!  {{site.data.alerts.end}}


 - Choose whether to enable security deposits on your reservation folios by clicking on the relevant circle box.

![Accounting_3.png]({{site.baseurl}}/images/Accounting_3.png)



Activating the security deposit will enable you to record payments as deposits rather than payments proper. When deposits are enabled, there will be track of them in each reservation folio:  

![Accounting_4.png]({{site.baseurl}}/images/Accounting_4.png)



##**Fiscal Year**  

Each property has a different starting date for their Fiscal Year, depending on applicable governmental laws: for this reason we advise you to set this up during the intial configuration of your account.  

- Click on the blue link **Fiscal Year** under section _Accounting_:  



![accounting_3_1.png]({{site.baseurl}}/images/accounting_3_1.png)




 - Select the month and the year of your fiscal year by following the format below: your current fiscal year is also displayed, in case you forgot!  
 
![Accounting_6.png]({{site.baseurl}}/images/Accounting_6.png)


##**Pay Types**

 
 Selecting the pay types that are accepted at your property is important to avoid the margin of human error of your front desk staff when they collect payments, it is also good when auditing and run reports!  
 
 - In the Admin Settings, click on the blue link **Pay Types** under section _Accounting_:  
 

![accounting_5_1.png]({{site.baseurl}}/images/accounting_5_1.png)



 
 - You will see a list of some defaulted pay types already enabled for your account:  
 
![Accounting_8.png]({{site.baseurl}}/images/Accounting_8.png)


 
 - To **Add** a Pay Type, click on the blue button _Add a Pay Type_:  
 
![Accounting_9.png]({{site.baseurl}}/images/Accounting_9.png)


 
 - A new row will appear along with an editable text box where you will need to insert the name of the new type of payment you want to add. Click on the button _Save_ when finished: 
 
![Accounting_10.png]({{site.baseurl}}/images/Accounting_10.png)


 
 - To **Delete** a Pay Type, select it by checking the box on its left side and click on the blue button _Delete Selected Pay Types_:  
 
![Accounting_11.png]({{site.baseurl}}/images/Accounting_11.png)



##**Credit Card Types**

Along with Pay Types you can also configure all credit cards accepted at your property. Note that all accepted cards will show on your booking engine as available payment methods for your guests, and it is for this reason important to have them up to date.


- Click on the blue link **Credit Card Types** under section _Accounting_:  



![accounting_7_1.png]({{site.baseurl}}/images/accounting_7_1.png)


  

- You will see a list of some credit card types that by default are already active on your account:  

![Accounting_13.png]({{site.baseurl}}/images/Accounting_13.png)

 

- To **Add** a credit card type, click on the blue button _Add a Card Type_: a new row will appear with an editable text box; insert the name for your card type and click on the blue button _Save Changes_:  

![Accounting_14.png]({{site.baseurl}}/images/Accounting_14.png)



- To **Deactivate** a credit card type, uncheck the box under column status on the right hand side of the type you want to make inactive:  

![Accounting_15.png]({{site.baseurl}}/images/Accounting_15.png)



##**Payment Processing**  

Your PMS can integrate with many secure payment gateways that will make charging a guest's card much faster and your check-in process much easier! 


- In the Admin Settings, click on the link **Payment Processing** under section _Accounting_:  


![accounting_16_1.png]({{site.baseurl}}/images/accounting_16_1.png)





- To add your Payment Gateway, click on the blue button _Add Payment Gateway_:  

![Accounting_17.png]({{site.baseurl}}/images/Accounting_17.png)



- Find your gateway among the ones in the list. 

![Accounting_18.png]({{site.baseurl}}/images/Accounting_18.png)



- Scroll all the way down and go to the bottom of the page: type in the gateway name in the _Payment Gateway Label_ textbox. Enter the username and password for the gateway and click on the blue button _Add Gateway_:


![Accounting_19.png]({{site.baseurl}}/images/Accounting_19.png)


{{site.data.alerts.note}} the username and password might not be called 'username' and 'password'. Each gateway has its own name for API credentials. We advise you to speak to your gateway;s representative if you are unable to find this information. If you have any questions or issues during the set up of Payment Processing, send an email to help@frontdeskanywhere.com  {{site.data.alerts.end}}



- You will now be able to see the payment gateway:  


![Accounting_20.png]({{site.baseurl}}/images/Accounting_20.png)

 

- All is left to do is enable the gateway on both/either the Frontdesk area and/or your Booking Engine. Enabling the gateway on work area Frontdesk means guests' cards can be charged directly from the folio. Enabling the gateway on IBE means credit cards can be authenticated and processed when guests book online on your website:  

![Accounting_21.png]({{site.baseurl}}/images/Accounting_21.png)




Learn how to configure the way the system is to charge your guests' cards on IBE by reading chapter [IBE](http://docs.frontdeskanywhere.net.s3-website-us-west-1.amazonaws.com/build/IBE_general.html), section _Payment Collection Rules_.

##**Credit Card Purge**


As a security measure Frontdesk Anywhere enables automatic erasing on a regular basis, the details of your guests’ credit card stored in your account.  

 - In the Admin Settings, click on the blue link **Credit Card Purge** under section _Accounting_:  
 

![accounting_22.png]({{site.baseurl}}/images/accounting_22.png)



 
 - Type in the textbox with a number by keeping in mind that all credit card stored for more than the time frame you set, will be automatically erased. Click _Save_ when finished:
 
![Accounting_23.png]({{site.baseurl}}/images/Accounting_23.png)



- The system will run once a day and erase all credit card information stored in the system, for the time frame you set up: if you wish to manually do this process, click on the blue button _Purge Credit Card Numbers_:  

![Accounting_24.png]({{site.baseurl}}/images/Accounting_24.png)




##**Invoices**

You can check the number of your invoices with a simple click!

 - Click on the link **Invoices** under section _Accounting_:  
 
 
![accounting_25.png]({{site.baseurl}}/images/accounting_25.png)




 
  - The number of your Invoices will show at the center of the panel:  
  
![Accounting_26.png]({{site.baseurl}}/images/Accounting_26.png)


  
  
##**Discount Reasons List **


You may want to set up a list of reasons for those discounts/adjustments that your hotel happens to give out regularly. Setting them up  allows you to keep track of the reasons why discounts are given.  

- In the Admin Settings, click on the link **Discount Reasons List**, under section _Accounting_:  
 


![accounting_27_1.png]({{site.baseurl}}/images/accounting_27_1.png)



 
 - Click on the blue button _Add an Adjustment Reason_:  
  

![accounting_28.png]({{site.baseurl}}/images/accounting_28.png)


  
 - Type in the name of the Discount Reason and a short code for it, if applicable otherwise simply re-type in the Discount name. Once ready, click on the blue button _Save Changes_ when finished:  
 
![accounting_29.png]({{site.baseurl}}/images/accounting_29.png)


 
 - To **DELETE** a Discount Reason, select it by checking the box on the left hand side and click on the blue button _Delete Selected Adjustment Reason_:  
 
![accounting_30.png]({{site.baseurl}}/images/accounting_30.png)


{{site.data.alerts.note}} Make sure that you have at least one Adjustment Reason built in your account, as the system won't allow you to erase all of them.  {{site.data.alerts.end}}
  

- You can **UN-DELETE** a previously deleted Adjustment Reason: on the top right hand side, select _Deleted_ from the scroll down menu with the written _Active_.  

![accounting_31.png]({{site.baseurl}}/images/accounting_31.png)



- Select the Adjustment Reason you want to re-activate by checking the box on the left  side of the panel; then click on the blue button _Undelete Selected Adjustment Reason_:  

![accounting_32.png]({{site.baseurl}}/images/accounting_32.png)



Your active Adjustment Reasons will appear on each reserved folio, under section _Adjustments_:  

![acounting_33.png]({{site.baseurl}}/images/acounting_33.png)



Scroll down the menu with the tag _Select Adjustment Reason_:  

![accounting_34.png]({{site.baseurl}}/images/accounting_34.png)

 


##**Discount Reasons: Department Options**  



You can create Department options for the Adjustment reasons you created, to make sure that all your discounts are approved and listed under the right department.  

 - In the Admin Settings click on the blue link **Discount Reasons: Department Options** under section _Accounting_:  
 


![accounting_35.png]({{site.baseurl}}/images/accounting_35.png)



 
 - To add a Department, click on the blue link _Add Department_:  
 

![Accounting_36.png]({{site.baseurl}}/images/Accounting_36.png)


- Insert the Department Code and the name of the Department: the first will appear in each reservation folio as an option to select. Click on the blue button _Save_ when finished:  

![Accounting_37.png]({{site.baseurl}}/images/Accounting_37.png)




 - To **Delete** a Discount Department, select it by checking the box on the left hand side and click on the blue button _Delete Selected Department_:  
 
![Accounting_38.png]({{site.baseurl}}/images/Accounting_38.png)


{{site.data.alerts.note}} Make sure that you have at least one Department Option built in your account, as the system won't allow you to erase all of them. {{site.data.alerts.end}}
  
 
 - You can make active those Department Options that have been previously deleted. Select the option _Delete_ from the scroll down menu on the right hand side of the Department Option panel:  

![Accounting_39.png]({{site.baseurl}}/images/Accounting_39.png)

 

 - Select it by checking the box on the left hand side of the item and click on the blue button _UnDelete Selected Department_:  
 
![Accounting_40.png]({{site.baseurl}}/images/Accounting_40.png)


 
 You will be able to find and select your active Discount Department Options in any reservation folio, under section _Adjustment_:  
 
![Accounting_41.png]({{site.baseurl}}/images/Accounting_41.png)


 
 Click on the scroll down menu _Select Department_ to choose the right option:  
 
![Accounting_42.png]({{site.baseurl}}/images/Accounting_42.png)



 
 
  ##**Revenue Account Labels**  
 
 
 Revenue Account Labels are customizable tags that will help you organizing your reports. Thanks to these Labels you can group together similar items you are selling at your property (where _item_ is understood here as anything that produces revenue), and have a much better overview of where your earnings come from.  
 
 - In the Admin Settings, click on the blue link **Revenue Account Labels**:  
 
 

![accounting_45_1.png]({{site.baseurl}}/images/accounting_45_1.png)



 
 - To add a new Label, click on the blue link _Add Label_:  
 
![Accounting_44.png]({{site.baseurl}}/images/Accounting_44.png)

 
 
 - Another editable row will appear; insert the name for the new label, and click on the blue button _Save Changes_:  
 
![Accounting_45.png]({{site.baseurl}}/images/Accounting_45.png)

 
  - To **Deactivate** a Revenue Label, simply uncheck the relevant box under section _Status_:  
  
![Accounting_46.png]({{site.baseurl}}/images/Accounting_46.png)


  
  - To **Edit** a Label, click on the blue link _Edit_ on the right hand side of any label: the text in the panel will become editable, so you can amend the label name. When done, click on the blue button _Save Changes_:  
  
![Accounting_47.png]({{site.baseurl}}/images/Accounting_47.png)


  
  You Revenue Labels will appear as filters in some of your Reports. Below is an example of a report you can organize by Revenue Label:   
  
![Accounting_48.png]({{site.baseurl}}/images/Accounting_48.png)




##**Revenue Account Categories**  


Revenue Account Categories are used to group together Revenue Account Lables.

-  In the Admin Settings, click on the blue link **Revenue Account Categories**, under section _Accounting_:  



![accounting_49_1.png]({{site.baseurl}}/images/accounting_49_1.png)





- To add a new Category, click on the blue link _Add Category_:  

![accounting_49_2.png]({{site.baseurl}}/images/accounting_49_2.png)

 

- You will see appearing a new editable row; insert the name for the new category, and click on the blue button _Save Changes_:


![Accounting_51.png]({{site.baseurl}}/images/Accounting_51.png)



- To **Deactivate** a Revenue Category, simply uncheck the relevant box under section _Status_: 

![Accounting_52.png]({{site.baseurl}}/images/Accounting_52.png)



- To **Edit** a Category, click on the blue link _Edit_ on the right hand side of any row: the text in the panel will become editable, so you can amend the category name. When done, click on the blue button _Save Changes_:  

![Accounting_53.png]({{site.baseurl}}/images/Accounting_53.png)



You Revenue Categories will appear as filters in some of your Reports. Below is an example of a report you can organize by Revenue Category:  

![Accounting_54.png]({{site.baseurl}}/images/Accounting_54.png)


##**Revenue Account Manager**  


The Revenue Account Manager helps you associating the irght Revenue Label and Category to whatever item you are selling at your property. If you have taken care to set up your account by associating the right Category and Label to each item, you will see all ifnormation displayed correctly in this page. If you have not, this page will help you make the right association in a quick and easy way!   


-  In the Admin Settings, click on the blue link **Revenue Account Manager**, under section _Accounting_:    


![accounting_50_1.png]({{site.baseurl}}/images/accounting_50_1.png)




- On the left hand side, you will see a column with all the items that you have created in the system, and that you are currently selling. For each of those, choose the right Label and Category by looking up the right option in the scroll down menus:  


![Accounting_56.png]({{site.baseurl}}/images/Accounting_56.png)


- Note that the column that describes what kind of item it is, is not editable: it just serves as a reminder of what type of item it is!   

![Accounting_57.png]({{site.baseurl}}/images/Accounting_57.png)


- When finished, click on the button _Save Labels_:   

![Accounting_58.png]({{site.baseurl}}/images/Accounting_58.png)
