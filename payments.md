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

##**Payment Operations**  


- To perform operations on submitted payments, click on the Payments drop down menu, and under column _Type_ click on the green box _Payment_ for the payment you wish to perform your operations:  


![payments_21.png]({{site.baseurl}}/images/payments_21.png)


**Convert to Deposit** will move the payment from being recorded as a payment proper and it will turn it into a Security Deposit.  
**Void** will annul the payment.  
**Refund** will enable you to refund part or the whole of the payment. If you wish to partially refund your guests, fill in the box with the amount you wish to refund and click on the box _Refund_.

  
  
###**Recording a Security Deposit**  


- You can record security deposits directly from the same Payment screen. Choose the Pay Type and insert the amount you want to have recorded as a deposit:  


![payments_11.png]({{site.baseurl}}/images/payments_11.png)


- Check the box with the tag _Take as Deposit_ and click on the button _Pay Now_:  


![payments_12.png]({{site.baseurl}}/images/payments_12.png)



- If you open the _Payments_ drop down menu, you will see that the sum is recorded in the system as a _Deposit_, and not under _Amount_:  


![payments_13.png]({{site.baseurl}}/images/payments_13.png)

  


- In the folio screen, the amount submitted as deposit will appear in the field _Security Deposits_:  


![payments_14.png]({{site.baseurl}}/images/payments_14.png)

  
  
###**Turning a Security Deposit into a Payment**  

- It might often happen that your guests will want to turn their security deposits into payments to set their bills. This is easily done! As a first thing, click on the _Payments_ scroll down menu:  


![payments_17.png]({{site.baseurl}}/images/payments_17.png)



- Under column _Type_, click on the box _Payment_ green box, corresponding to the security deposit:  


![payments_18.png]({{site.baseurl}}/images/payments_18.png)


- This will bring up information about the payment, and all possible operations that are available to perform:  



 **Convert To Payment** will turn the security deposits into a payment.
 **Void** will annul the payment.  
 **Refund** will allow you to record a refund: note that there is an editable box next to the green button _Refund_ where you can choose the amount to refund:  
 
 
 
![payments_20.png]({{site.baseurl}}/images/payments_20.png)

 

- If you select the items to charge directly by choosing them from the _Uninvoiced Transactions_ drop down menu, you will be able to refund an amount corresponding to the items. As mentioned, start by choosing what charges you want the guest to pay off:  


![payments_53.png]({{site.baseurl}}/images/payments_53.png)  


- Choose your payment type and click on the button _Pay Now_:  


![payments_54.png]({{site.baseurl}}/images/payments_54.png)  



- If you click on the _Payments_ drop down menu, and then you click on the green button _Payment_ corresponding to the action you just performed, you will be able to see another panel called _Applied to Transactions_:  

![payments_55.png]({{site.baseurl}}/images/payments_55.png)


There will be one line for each of the charge items.

- You can refund the payment for a specific charge item by clicking on the red button _Remove_:  


![payments_56.png]({{site.baseurl}}/images/payments_56.png)




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

- To process a payment, click on the blue link _Payments_ in the folio, and select **Credit card** from the Payment Type drop down menu:  


![payments_22.png]({{site.baseurl}}/images/payments_22.png)



- Enter the credit card type from the _Card Type_ drop down menu. Note that if the guest has a credit card loaded in the folio, there will be an option to select that card:  


 ![payments_23.png]({{site.baseurl}}/images/payments_23.png)



In the case you select the existent card, all relevant fields will be automatically filled in; otherwise, you can select the card type and insert the card number and the expiration dates.  

- Place the amount you want to charge the guest:  

 ![payments_24.png]({{site.baseurl}}/images/payments_24.png)



- When Payment Gateway is active you will have the option to either charge the card, or authorize it:  


![payments_25.png]({{site.baseurl}}/images/payments_25.png)



**Authorizing** the card will place a hold on the guest's card for the amount you selected.  
**Pay Now** will automatically charge the guest's card for the selected amount.  


- If you choose to authorize the card, you will receive a _Payment Successful_ message on the screen. You can open the Payments drop down menu to look up the authorization:  



![payments_26.png]({{site.baseurl}}/images/payments_26.png)


As you can see from the example above, the amount corresponding to the Authorization appears in light grey, and the balance is not being affected by it.  

- If you click on the _Authorization_ blue button, you will be able to access the details and see the available actions that you can perform:  


![payments_27.png]({{site.baseurl}}/images/payments_27.png)



- If you need to release the authorized amount, simply click on the red button _Release_:  

 ![payments_28.png]({{site.baseurl}}/images/payments_28.png)



- If you want to capture the amount, or part of the authorized amount (held), insert the relevant value in the box and click on the blue button _Capture_:  

![payments_29.png]({{site.baseurl}}/images/payments_29.png)



 - You will see two options: to capture the chosen amount and retain the rest of the authorized amount (hold), click on the button _Capture and Retain_:  


![payments_30.png]({{site.baseurl}}/images/payments_30.png)


Note that the Authorized Amount will be, in this case, reduced by the amount captured. In the example above, the original amount authorized was $70, we have decided to capture $50 and retain the rest, so the current hold is of $20.  


- To capture the selected amount and release the rest of the authorized amount, click on the button _Capture and Release_:    

![payments_31.png]({{site.baseurl}}/images/payments_31.png)

  
  
 The _Authorization_ has disappeared, as we have released the held on the sum selected.  


{{site.data.alerts.important}}  When connected to a Payment Gateway, you will still able to convert payments to deposit, void them or refund them. However, the **refund option is only available for charges that have already been processed by the merchant account**; if you have only just processed a payment and you want to refund it, you can void it and re-place the charge. Charges voided within the day of charge won't be processed by the merchant account.{{site.data.alerts.end}}


##**Transferring Charges**      

You have the ability to transfer all or part of a folio charges either to another folio or to a Profile.  

  
  
  
###**Transferring Charges from Folio to Folio**  


Before you follow the instruction below, make sure you note down the folio number you wish to send the charges **to**.  


- Pull up the folio you want to transfer all charges and click on the blue link _Transfers Sent_, on the right hand column:  


![payments_32.png]({{site.baseurl}}/images/payments_32.png)  


- Another panel will pop-up, and you will see a breakdown of all charges by night. Note that the column _Amount_ will list the charges with not taxes, while the column _Total Amount_ will list the same charges with the total amount of taxes.  


![payments_33.png]({{site.baseurl}}/images/payments_33.png)    


- Using the check-boxes on the left hand side of each charge, select the ones you wish to transfer:  


![payments_34.png]({{site.baseurl}}/images/payments_34.png)  


- Insert the folio number where you want those charges to be sent and click on the blue button _Transfer_:  


![payments_35.png]({{site.baseurl}}/images/payments_35.png)  


- Once the Transfers have been sent out, you can undo your action by clicking on the red buttons _Undo_:  


![payments_36.png]({{site.baseurl}}/images/payments_36.png)  


- If you now go back to the folio screen, you will see that the sum you chose to transfer will now appear next to the link _Traansfer Sent_:  


![payments_37.png]({{site.baseurl}}/images/payments_37.png)  


- Similarly, the folio that has received the charges, will have the corresponding amount appearing next to the link _Transfers Received_:  


![payments_38.png]({{site.baseurl}}/images/payments_38.png)



###**Transferring Charges from Folio to a Profile** 
 

You will be able to send charges from a folio to a Profile invoice. Before you follow the instructions below, make sure that the Profile you want to send charges to has at least one invoice created; if it does not, you will need to create one. To do so, follow the instructions on the _Profile_ section of this manual. It is also recommendable having the Profile ID number handy, in order to avoid confusion in case there are multiple profiles with the same name.    


- In the folio, click on the link _Payments_:  

![payments_39.png]({{site.baseurl}}/images/payments_39.png)




- Click on the drop down menu _Uninvoiced Transactions_: there will appear a list of all those transactions that need to be invoiced:  

![payments_40.png]({{site.baseurl}}/images/payments_40.png)




- Select the charges you want to transfer to the Profile:  


![payments_41.png]({{site.baseurl}}/images/payments_41.png)



- Click on the button _Transfer Charges_ on the top right corner:  


![payments_42.png]({{site.baseurl}}/images/payments_42.png)

 


- In the _Profile Search_ field, insert the Profile ID number: all available invoices for that profile will appear. Select the one of your choice:  


![payments_43.png]({{site.baseurl}}/images/payments_43.png)


  
  
- You will be able to see the charges transferred by going into the relevant profile and select the Invoice where you transferred those charges:  


![payments_44.png]({{site.baseurl}}/images/payments_44.png)


  
  
##**Adjustments**  


You will be able to perform adjustments to charges, directly from each folio:  


- Click on the blue link _Adjustments_ on the right hand side of the reservation folio:  


![payments_45.png]({{site.baseurl}}/images/payments_45.png)



- Another panel will pop up: you will be able to see a list of all charges.  



![payments_46.png]({{site.baseurl}}/images/payments_46.png)  


- Select the charges on which you want to perform the adjustment:  

![payments_47.png]({{site.baseurl}}/images/payments_47.png)  

- Choose whether to adjust a percentage or a fixed amount by clicking on the right circle-box:  

![payments_48.png]({{site.baseurl}}/images/payments_48.png)  

- Select a Department, if applicable, and place the adjustment amount (fixed or percentage). If you give a discount, be advised you need to place a '-' sign in front of the value.  The amount you set will be taken off from each of the charge item you chose to adjust:  


![payments_49.png]({{site.baseurl}}/images/payments_49.png)
  
  
- Select the Adjustment Reason, if applicable, and check the box next to the tag _Adjust Taxes_ if you wish to have the tax value adjusted, too. When finished, click on the green button _Adjust_: 


![payments_50.png]({{site.baseurl}}/images/payments_50.png)  


- Adjustments will be shown in the folio, in the apposite area:


![payments_51.png]({{site.baseurl}}/images/payments_51.png)  



###**Balance Display**  


On your Tape Chart, all reservation folios with an outstanding balance will appear with an exclamation point:  

![payments_52.png]({{site.baseurl}}/images/payments_52.png)  


This will enable you to have a good understanding of outstanding balances just by looking at your Tape Chart.
