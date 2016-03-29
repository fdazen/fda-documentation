---
title: Payments
tags: 
  - Payments
keywords: "payments, recording a payment, swiping credit card, processing credit cards, transferring charges, transfers to folio, transfers to profile"
last_updated: "February 22nd, 2016"
summary: "This section will guide you through how to perform basic and advanced payment operations: you will learn about how our payment screen is organized, how to record payments, how to transfer charges and, if applicable, how to capture credit card details. If you are integrated with a payment gateway and/or a credit card swiper, this will also be the place where you can learn how to process your guests' credit cards directly from your Frontdesk Anywhere account."
published: true
---





   
##**The Payment Panel**  

 - The payment section is located on the right column of the folio, right under the summary of all charges, and it is accessible by clicking on the blue _Payment_ link:  

![payments_1.png]({{site.baseurl}}/images/payments_1.png)  


 - Clicking on the link will bring up a pop up panel from where you can perform all operations related to payments:  
 
 
![payments_2.png]({{site.baseurl}}/images/payments_2.png)
 
   
   
The Payment panel can be separated into three main sections:     
 
 - The **Uninvoiced Transactions** drop down menu contains a list of all uninvoiced charges broken down by charge type. You can visualize them by clicking on the small arrow on the left hand side of the tag _Uninvoiced Transactions_:  
 
 
![payments_3.png]({{site.baseurl}}/images/payments_3.png)
  


In the example above, the guest is being charged for one Add-Ons item, one POS item and one Room Charge. 


 - The **Payments** drop down menu lists all payment details and operations recorded for the folio. It also brings information about what payments have been applied to certain charges, and what not: indeed, the **U/A** tag means **Unapplied** (Payments) and reminds to the amount of payments that have not or not yet been applied to charges.  


![payments_4.png]({{site.baseurl}}/images/payments_4.png)




 - The **Payment Type** section is where you actually submit the payments:    
 
 
![payments_5.png]({{site.baseurl}}/images/payments_5.png)



##**Recording a Payment**


###**Recording a Payment Without Applying it to a Charge**    
  
  

 - To record a payment, first select the _Payment Type_ by choosing the appropriate choice from the ones available in the drop down menu:    
  
  
![payments_6.png]({{site.baseurl}}/images/payments_6.png)


- Place the amount the guest is paying in the box on the left:   


![payments_7.png]({{site.baseurl}}/images/payments_7.png)




- If applicable, write down the receipt number in the _Receipt Number_ box and a description in the box with the tag _Description_:  


![payments_8.png]({{site.baseurl}}/images/payments_8.png)



- To record the transaction, click on the green button _Pay Now_:  


![payments_9.png]({{site.baseurl}}/images/payments_9.png)




- You will see the message _Payment Successful_ once the action has been finalized:  



![payments_10.png]({{site.baseurl}}/images/payments_10.png)


- You will be able to see the payment details by clicking on the _Payments_ drop down menu. From this panel you can see the type of operation performed, the type of payment used and the date and time when the operation was successfully recorded in the system:  


![payments_10_1.png]({{site.baseurl}}/images/payments_10_1.png)



Note that if the recorded payment has not been or not yet been applied to a specific charge, the amount the guest paid will also appear under column _Unapplied Payment_:  


![payments_11.png]({{site.baseurl}}/images/payments_11.png)




###**Recording a Payment and Apply it to a Selected Charge**  


- If your guest wants to pay for certain items only instead of a fixed amount, the system can calculate the sum of those items and apply the payment only to those charges. Click on the scroll down _Uninvoiced Transactions_ to visualize all items on the guest's bill and select the items the guest wishes to pay for, by checking the box on the left hand side of each item:  


![payments_16.png]({{site.baseurl}}/images/payments_16.png)




- As items are being selected, the sum will change in the _Amount_ field where payments are recorded: in the example above, the guest is only paying for the POS charge, for a total sum of $8.80:  


![payments_17.png]({{site.baseurl}}/images/payments_17.png)




**Important**: charges and applied payments are _not linked in the reporting engine_: this means that reports won't record that a certain payment has been submitted for a certain charge.  


###**Applying an Existent Payment to a Selected Charge**  

You can apply an existent payment to a selected charge.  


- Expand both _Uninvoiced Transactions_ and _Payments_ tab and select the payment line and the charge you wish to link together:  

![payments_18.png]({{site.baseurl}}/images/payments_18.png)


- On the Payment tab, click on the icon with three horizontal lines, on the left hand side: select _Apply Payments_:  


![payments_19.png]({{site.baseurl}}/images/payments_19.png)  


- You will notice that the payment amount disappeared from column _Unapplied Payment_: this is because that payment is now, indeed, applied!  

![payments_20.png]({{site.baseurl}}/images/payments_20.png)


- Note also that the balance from _Uninvoiced Transactions_ has also diminished by the amount applied to the charge; the same goes for the charge to which the payment has been applied:  

![payments_21.png]({{site.baseurl}}/images/payments_21.png)


###**Undo/Change the Payment Amount Applied to a Charge**  

If you made a mistake, you can amend the amount of payment that has been applied to a certain charge.  
  
  
- Expand the _Payment_ tab to visualize all payments made:  
  
  
![payments_22.png]({{site.baseurl}}/images/payments_22.png)


- Click on the green button _Payment_ to visualize detailed information about the
 selected payment:  
 
 
 
 ![payments_23.png]({{site.baseurl}}/images/payments_23.png)  
 



- The section _Applied to Transactions_ bears information about payments that have been applied to charges:   



![payments_24.png]({{site.baseurl}}/images/payments_24.png)  



- To change the amount applied, just edit the _Applied Amount_ box with the new value and click on the green button _Update_:  


![payments_25.png]({{site.baseurl}}/images/payments_25.png)


  
- To undo the action altogether and revert an applied payment back to an unapplied payment status, simply click on the red button _Remove_ :  


![payments_26.png]({{site.baseurl}}/images/payments_26.png)  


All changes will be reflected both in the Payment section and in the relevant Invoice containing the charge where the payment had been previously applied.
  
  
  
  
##**Invoices in the Payment Screen**  

You can create different invoices within the same folio, directly in the Payment screen. This is extremely handy when having to isolate charges or split bills for your guests, along with printing the associated receipts.  
In the _Payment_ screen of each reservation folio there will alwasy be an _Uninvoiced Transactions_ default invoice that will bear all charges and record applied payments if no charge gets moved to another folio. If you do need to isolate any of the charges and associated payments, just follow these simple instructions!  


###**Create a New Invoice**  

In order to transfer charges/applied payments, you will first need to create a new invoice.  

- In the _Payment_ tab, click on the button _Create Invoice_:  


![payments_27.png]({{site.baseurl}}/images/payments_27.png)

  
- You will see a new invoice appearing below the _Uninvoiced Transaction_ drop down menu:    



![payments_28.png]({{site.baseurl}}/images/payments_28.png)


- To change the name of the newly created invoice, simply click on the written _New Invoice_, and the field will become editable. Insert the new name and **click on the button Enter on your keyboard**:  
  
  
  
![payments_29.png]({{site.baseurl}}/images/payments_29.png)
  
  
{{site.data.alerts.warning}} Before you proceed to transfer charges, allow the system to refresh with the new changes: simply close the whole Payment Tab and open it again.  {{site.data.alerts.end}}


- Expand the invoice that currently lists the charges you wish to transfer and proceed to select the relevant ones by checking the boxes on the left side. In the example below, I am transferring charges from the _uninvoiced Transactions_ invoice to the _Test Invoice_:   


![payments_30.png]({{site.baseurl}}/images/payments_30.png)


- Click on the button _Transfer Charges_ on the right corner of the screen: you will see a list of all the invoices created in the folio. In the example below, we have only created the _Test Invoice_ in the folio, and this is indeed the only one that there appears:  


![payments_31.png]({{site.baseurl}}/images/payments_31.png)  


- Select that invoice by clicking on the name:  


![payments_32.png]({{site.baseurl}}/images/payments_32.png)


- The charge will now appear on the new invoice: you can expand the invoices to see all changes being reflected. Note that if payment had been previously applied to the charge you moved, that payment also will be moved and reflected in the new invoice:  


![payments_34.png]({{site.baseurl}}/images/payments_34.png)


###**Printing an Invoice**  

Each invoice has its own balance, corresponding to the charges it contains and the payment that have been applied to those charges. From time to time you might need to separate the bills and print receipts that will only show certain charges/payments.  

- To print a receipt, simply click on the three horizontal bars, next to the right invoice:    


![payments_35.png]({{site.baseurl}}/images/payments_35.png)  


- Click on the option _Invoice_ to bring up the printable receipt:  


![payments_36.png]({{site.baseurl}}/images/payments_36.png)


{{site.data.alerts.note}} If you do not see any template in the pop-up panel, contact your manager and make sure that the right template has been enabled for the Profile Documents. You can click [here](http://docs.frontdeskanywhere.net.s3-website-us-west-1.amazonaws.com/build/messages_and_emails.html) to get more information! {{site.data.alerts.end}}  


###**Deleting an Invoice**  

- To delete an Invoice, click on the three horizatal bars on the left hand side of the relevant Invoice, and select the option _Delete Invoice_:  


![payments_37.png]({{site.baseurl}}/images/payments_37.png)  



{site.data.alerts.warning}} You cannot delete an Invoice that contains charges. If the Invoice you are trying to delete contains charges, you will see the following message: {{site.data.alerts.end}}  


![payments_38.png]({{site.baseurl}}/images/payments_38.png)


You will need to first move all charges to another invoice, and then proceed to delete the invoice.




##**Payment Operations**  


- To perform operations on submitted payments, click on the Payments drop down menu, and then on the green box _Payment_ for the payment on which you wish to perform your operations:  


![payments_39.png]({{site.baseurl}}/images/payments_39.png)



**Convert to Deposit** will change the payment from being recorded as a payment proper into a Security Deposit.  
**Void** will annul the payment.  
**Refund** will enable you to refund part or the whole of the payment. If you wish to partially refund your guests, fill in the box with the amount you wish to refund and click on the box _Refund_.

  
  
###**Recording a Security Deposit**  


- You can record security deposits directly from the same Payment screen. Choose the Pay Type and insert the amount you want to have recorded as a deposit:  


![payments_40.png]({{site.baseurl}}/images/payments_40.png)



- Check the box with the tag _Take as Deposit_ and click on the button _Pay Now_:  


![payments_41.png]({{site.baseurl}}/images/payments_41.png)




- If you open the _Payments_ drop down menu, you will see that the sum is recorded in the system as a _Deposit_, and not under _Amount_:  



![payments_42.png]({{site.baseurl}}/images/payments_42.png)

  


- In the folio screen, the amount submitted as deposit will appear in the field _Security Deposits_:  


![payments_43.png]({{site.baseurl}}/images/payments_43.png)


  
  
###**Turning a Security Deposit into a Payment**  


- It might often happen that your guests will want to turn their security deposits into payments to set their bills. This is easily done: expand the _Payment_ tab to individuate the deposit:    


![payments_44.png]({{site.baseurl}}/images/payments_44.png)


- Expand the payment to visualize the details and operations available by clicking on the green button associated with the deposit:


![payments_45.png]({{site.baseurl}}/images/payments_45.png)



- Click on the green button _Convert To Payment_:  


 
 ![payments_46.png]({{site.baseurl}}/images/payments_46.png)



##**Capturing Credit Card Details With Credit Card Swiper**  
    
    
Your Frontdesk Anywhere account can be integrated with any _Credit Card Swiper_ that uses **Keyboard Emulation** tool. A credit card Swiper will enable you to capture your guests' credit card numbers and expiration date in an automatic fashion, thus making the reservation process much quicker and reducing the possiblity of human error.  


- To start using the credit card Swiper, click on the folio you want to record the card details:  


![profiles_35.png]({{site.baseurl}}/images/profiles_35.png)



- Scroll down to the Credit Card panel at the center of the folio, and clik on the link _Add Card_:  


![profiles_36.png]({{site.baseurl}}/images/profiles_36.png)  


- You will see the button _Swipe Credit Card_: click on it:  


![profiles_37.png]({{site.baseurl}}/images/profiles_37.png)  


- Once you click the button, the written _Swipe Card_ will start flashing: swipe the credit card using the card Swiper:  


![profiles_38.png]({{site.baseurl}}/images/profiles_38.png)  


- You should hear a beeping sound when the card details get captured, and you will be able to see those details in the relevant fields:  


![profiles_39.png]({{site.baseurl}}/images/profiles_39.png)



- You will be able to find the _Swipe Card_ function that enables you to capture the card details in the _Payment Screen_:   


![profiles_40.png]({{site.baseurl}}/images/profiles_40.png)


You can use the Swiper in the _Profile_ tab, in the relevant Payment section:  


![profiles_41.png]({{site.baseurl}}/images/profiles_41.png)  




##**Processing Payments with Payment Processing**  


If your account is integrated with a Payment Gateway, you will be able to _process_ payments for credit cards directly into the Payment screen.  


- To process a payment, select **Credit card** from the Payment Type drop down menu:  



![payments_47.png]({{site.baseurl}}/images/payments_47.png)



- Enter the credit card type from the _Card Type_ drop down menu. Note that if the guest has a credit card loaded in the folio, there will be an option to select that card:  


![payments_48.png]({{site.baseurl}}/images/payments_48.png)  



In the case you select the existent card, all relevant fields will be automatically filled in; otherwise, you can select the card type and insert the card number and the expiration dates.    



- Place the amount you want to charge the guest:  


![payments_49.png]({{site.baseurl}}/images/payments_49.png)



- When Payment Gateway is active you will have the option to either charge the card, or authorize it:  


![payments_50.png]({{site.baseurl}}/images/payments_50.png)



**Authorizing** the card will place a hold on the guest's card for the amount you selected.  
**Pay Now** will automatically charge the guest's card for the selected amount.  



- If you choose to authorize the card, you will receive a _Payment Successful_ message on the screen. You can open the _Payments_ drop down menu to look up the authorization: the latter will appear in a blue color:  


![payments_51.png]({{site.baseurl}}/images/payments_51.png)



The amount corresponding to the authorization appears in light grey, and the overall balance is not affected by it.  


- If you click on the _Authorization_ blue button, you will be able to access the details and see the available actions that you can perform:  


![payments_52.png]({{site.baseurl}}/images/payments_52.png)



- If you need to release the authorized amount, simply click on the red button _Release_:  


![payments_53.png]({{site.baseurl}}/images/payments_53.png)



- If you want to capture the amount, or part of the authorized amount, insert the relevant value in the box and click on the blue button _Capture_:  


![payments_54.png]({{site.baseurl}}/images/payments_54.png)


- There will be two available options:

**Capture and Release**: the amount specified in the editable box will be turned into a payment proper, while the rest will be released.  
**Capture and Retain**: the amount specified in the editable box will be turned into a payment proper, and the rest will remain as an authorization.  



{{site.data.alerts.important}}  When connected to a Payment Gateway, you will still able to convert payments to deposit, void them or refund them. However, the refund option is only available for charges that have already been processed by the merchant account; if you have only just processed a payment and you want to refund it, you can void it and re-place the charge. Charges voided within the day of charge won't be processed by the merchant account.{{site.data.alerts.end}}



##**Transferring Charges**      

You have the ability to transfer all or part of a folio charges either to another folio or to a Profile.  
  
  
  
###**Transferring Charges from Folio to Folio**  


Before you follow the instruction below, make sure you note down the folio number you wish to send the charges **to**.  


- Pull up the folio from which you want to transfer all charges and click on the blue link _Transfers Sent_, on the right hand column:  



![payments_55.png]({{site.baseurl}}/images/payments_55.png)



- Another panel will pop-up, and you will see a breakdown of all charges by night. Note that the column _Amount_ will list the charges without taxes, while the column _Total Amount_ will list the same charges with the total amount of taxes.  


![payments_56.png]({{site.baseurl}}/images/payments_56.png)



- Using the check-boxes on the left hand side of each charge, select the ones you wish to transfer:  


![payments_57.png]({{site.baseurl}}/images/payments_57.png)



- Insert the folio number where you want those charges to be sent and click on the blue button _Transfer_:  


![payments_58.png]({{site.baseurl}}/images/payments_58.png)



- Once the Transfers have been sent out, you can undo your action by clicking on the red buttons _Undo_:  


![payments_59.png]({{site.baseurl}}/images/payments_59.png)



- If you now go back to the folio screen, you will see that the sum you chose to transfer will appear next to the link _Traansfer Sent_:  


![payments_60.png]({{site.baseurl}}/images/payments_60.png)



- Similarly, the folio that has received the charges, will have the corresponding amount appearing next to the link _Transfers Received_:  


![payments_61.png]({{site.baseurl}}/images/payments_61.png)




###**Transferring Charges from Folio to a Profile** 
 

You will be able to send charges from a folio to a Profile invoice. Before you follow the instructions below, make sure that the Profile you want to send charges to **has at least one invoice created**; if it does not, you will need to create one. You can follow instructions [here](http://docs.frontdeskanywhere.net.s3-website-us-west-1.amazonaws.com/build/profiles.html).To do so, follow the instructions on the _Profile_ section of this manual. It is also recommendable having the Profile ID number handy, in order to avoid confusion in case there are multiple profiles with the same name.    


- Access the _Payment_ panel in the folio you wish to transfer the charges from, and click on the on the drop down menu _Uninvoiced Transactions_. Select the charges you want to transfer and click on the button _Transfer Charges_:  


![payments_62.png]({{site.baseurl}}/images/payments_62.png)

 


- In the _Profile Search_ field, insert the Profile ID number: all available invoices for that profile will appear. Select the one of your choice:  



![payments_63.png]({{site.baseurl}}/images/payments_63.png)




  
  
- You will be able to see the charges transferred by going into the relevant profile and select the Invoice where you transferred those charges:  



![payments_64.png]({{site.baseurl}}/images/payments_64.png)


  
  
##**Adjustments**  


You will be able to perform adjustments to charges, directly from each folio:  


- Click on the blue link _Adjustments_ on the right hand side of the reservation folio:  


![payments_65.png]({{site.baseurl}}/images/payments_65.png)




- Another panel will pop up: you will be able to see a list of all charges. Select the charges on which you want to perform the adjustment by checking the relevant box:  


![payments_66.png]({{site.baseurl}}/images/payments_66.png)



- Choose whether to adjust a percentage or a fixed amount by clicking on the right circle-box:  


![payments_67.png]({{site.baseurl}}/images/payments_67.png)


- Select a Department, if applicable, and place the adjustment amount (fixed or percentage). If you give a discount, be advised **you need to place a '-' sign in front of the amount**.  The amount you set will be taken off from each of the charge item you chose to adjust:  



![payments_68.png]({{site.baseurl}}/images/payments_68.png)
  
  
- Select the Adjustment Reason, if applicable, and check the box next to the tag _Adjust Taxes_ if you wish to have the tax value adjusted, too. When finished, click on the green button _Adjust_: 


![payments_69.png]({{site.baseurl}}/images/payments_69.png)



- Adjustments will be shown in the folio, in the apposite area:


![payments_70.png]({{site.baseurl}}/images/payments_70.png)



