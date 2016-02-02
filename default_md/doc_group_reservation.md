---
title: Group Reservations
tags: 
  - formatting
keywords: "labels, buttons, bootstrap, api methods"
last_updated: "August 12, 2015"
summary: Labels are just a simple Bootstrap component that you can include in your pages as needed. They represent one of many Bootstrap options you can include in your theme.
published: true
---



#** MULTIPLE ROOMS RESERVATION ** 
Creating a multiple rooms reservation for small or large groups is easy in Frontdesk Anywhere: from only one panel you are able to streamline the reservation process, manage booking status, set up payment rules and print/send group messages.       
##**Step 1. New Group**      
  - Begin by clicking on the blue button _NEW GROUP_ on top of your Tape Chart:   
  
![group_reservation_1.png]({{site.baseurl}}/images/group_reservation_1.png)
   
  
  - A new window will pop up: insert the Group Name in the first field, and select the Source and Market from the available options in the second and last field. Once done, click on the blue button _NEXT_:      
  
![group_reservation_2.png]({{site.baseurl}}/images/group_reservation_2.png)
   
 
##**Step 2. Choose the group’s stay date and the room information**     


   - Using the two scroll down calendars, select the check-in and check-out dates of the group. If you need shoulder dates, or if part of the group is staying longer/shorter, you will be able to adjust details in the next step.   
   
![group_reservation_3.png]({{site.baseurl}}/images/group_reservation_3.png)

   
   - Choose the room type of your choice by selecting the right option from the respective scroll down menu: if the group has booked more than one room type, you will be given the option to add more rooms once _**Step 2**_ is completed:   
   
![group_reservation_4.png]({{site.baseurl}}/images/group_reservation_4.png)
 
 
When you choose a room type, the scroll down menus with the tags _Rates_ and _No. Rooms_ will automatically update to give you the number of available rooms and rates for the dates of your choice.   
- If you wish to customize the rate for the group, you can  do this by clicking on the blue link **Edit Rate**, next to the _Rate_ scroll down menu.
You will have two options: you can either edit the daily rate by clicking on the circle box _Daily Price Edit_:   
 
![group_reservation_5.png]({{site.baseurl}}/images/group_reservation_5.png)

 
or you can click on the circle box _Fixed Price Edit_ to change the total rate for each room:   
 
![group_reservation_6.png]({{site.baseurl}}/images/group_reservation_6.png)

     
Click on the yellow button **Update** to save your changes.   
 
   - Choose how you want to assign rooms for this group.   
   You will have three options:    
![group_reservation_7.png]({{site.baseurl}}/images/group_reservation_7.png)


**Auto Assign** will have the system automatically assign the rooms among the ones available.   
**Unassign** will create the group without any room assignment.   
**Manual Assign** will enable you to choose the rooms among the ones available.   

Select your option and click on the blue button **Add Rooms**.   

##**Step 3. Manual Assignment (skip to Step 4 if not applicable)**   
- If you chose the Manual Assignment option, the following panel will pop-up:   
![group_reservation_8.png]({{site.baseurl}}/images/group_reservation_8.png)
 

Make your choice and click on the button **Select** when done:   

![group_reservation_9.png]({{site.baseurl}}/images/group_reservation_9.png)


Click on the blue button **Add Rooms*.   

##**Step 4. Select Group Reservation Status**   

- Once the rooms are added, there will appear a brief summary of the group details: you will now need to choose the group reservation status.   

![group_reservation_10.png]({{site.baseurl}}/images/group_reservation_10.png)


Choose:   

**Reserve** if you want to finalize the reservation as reserved   
**Hold** if you want to hold rooms for the group without fully reserving them      
**Block / DNR** if you want to take the rooms out of your current inventory   

- If you choose to hold rooms, you will be given two options:   
![group_reservation_11.png]({{site.baseurl}}/images/group_reservation_11.png)


If you select a _Manual Release_ for the rooms, the rooms will stay in a Hold status until you manually change the status within the Group Folio.   

If you select _Automatic Release_ you will need to choose a certain date from the scroll down calendar: the system will automatically release the rooms on that date, if the latter have not been reserved up to then.   

##**Step 5. Removing a room from the Room Queue**   
- If you made a mistake and reserved too many rooms, you can remove the extra ones by clicking on the button _Remove_:‘Remove’:   
![group_reservation_12.png]({{site.baseurl}}/images/group_reservation_12.png)
 

- Select the number of rooms you wish to remove and click on the blue button **Save**.   

When ready, you can click on the button **Next** to go to the next step.   

**NOTE**: If you wish to add more room types to the reservation, you will need to repeat **Step 2**.   

##**Step 6. Group Rules**   

Group Rules are used to set up group payments: you can decide to transfer charges to an onsite or offsite payer, split the payment among the reservations that are part of the group, group chargestogether, and so on. When a group is created, all charges are by default transferred to one reservation folio, which represents the group's leader. If you want to distribute charges differently, you will need to modify the Group Rules.   

- Open your group reservation:   
![group_reservation_13.png]({{site.baseurl}}/images/group_reservation_13.png)


- Click on **Group Rules** on the top of the panel:   
![group_reservation_14.png]({{site.baseurl}}/images/group_reservation_14.png)

As mentioned above, all charges are transferred to the first reservation folio. This default rule is called _Rule Set 1_, and the specific settings are displayed below it:   
 ![group_reservation_16.png]({{site.baseurl}}/images/group_reservation_16.png)


**Folio(s) to Transfer Charges From**: the option _All Folios_ is selected in the default rule, meaning that charges from all the group reservation folios will be transferred. Unchecking the box will enable you to select the charges of those folio(s) you want to transfer:   

![group_reservation_17.png]({{site.baseurl}}/images/group_reservation_17.png)


**Folio to Transfer Charges to**: from the scroll down menu, sleect what folio is to receive the charges:   

![group_reservation_18.png]({{site.baseurl}}/images/group_reservation_18.png)


**Percentage to Be Paid**: insert the percentage you wish to transfer from the selected folios:   

![group_reservation_20.png]({{site.baseurl}}/images/group_reservation_20.png)


- Click on the button _Save_ to save your work. You will be prompted to choose whether to override the existing rule (_Rule Set 1_), or to simply save the new rule:   

![group_reservation_21.png]({{site.baseurl}}/images/group_reservation_21.png)
 

Overriding past transactions will wipe out existing rules and substitute them with the newly created one; simply saving the rule will add a new one to the existing rules, without amending the latter.  

#**Step 7. Transferring Charges to a Company (Direct Billing)**  

You can transfer charges to any Guest or Company profile. This is a step-by-step process, and you will need to make sure that the profile you wish to transfer charges to is currently existing in the system. Also, you will need to make sure that an Invoice is created for that profile.  

 1. Transfer the charges you wish to one reservation folio. If you do not remember how to, check out section **Group Rules**.  

 2. Access the folio that bears all charges to transfer by clicking on the correspondent folio number in the panel _Details_ :  
 
![group_reservation_22.png]({{site.baseurl}}/images/group_reservation_22.png)

 
 3. Go into the _Payments_ section of the folio that received all the charges to transfer:  
 
![group_reservation_23.png]({{site.baseurl}}/images/group_reservation_23.png)
 

 4. In the payments panel, click on the scroll down menu _Uninvoiced Transactions_ and select all charges you wish yo transfer:  
 
![group_reservation_24.png]({{site.baseurl}}/images/group_reservation_24.png)

 
 5. On the top right hand side, click on the button _Transfer Charges_; a small search box will appear: type in the name of the Guest Profile you wish to transfer charges to:  
 
![group_reservation_25.png]({{site.baseurl}}/images/group_reservation_25.png)

 
 6. For that profile, select the invoice you want to use:  
 

![group_reservation_26.png]({{site.baseurl}}/images/group_reservation_26.png)


#**Step 8. Group Operations**   

From the group folio, you are able to perform bulk operations, like change the status of the group reservation or edit the name for individual reservations.  

###**BULK UPDATES**
- In the Group Folio, click on the tab _Details_:   

![group_reservation_27.png]({{site.baseurl}}/images/group_reservation_27.png)


- Depending on the current status of the group reservation, there will be different actions you are able to perform. Those available operations are displayed on the top of the folio list:   

![group_reservation_28.png]({{site.baseurl}}/images/group_reservation_28.png)
 

In the example, the current folios status is _Reserved_; hence the available operations are _Check-in_ and _No-Show_ (if the group's arrival is today's date), and _Cancel_. If the current status of the folio was _Hold_, then there would also be a _Reserved_ option, if the current status was _Checked-in_, then a _Check-out_ option would be there, and so on.   

- To perform a bulk operation, select the folios by checking the boxes on the left side, and click on the operation you would like to perform:   

![group_reservation_29.png]({{site.baseurl}}/images/group_reservation_29.png)


###**EDIT/CHANGE A RESERVATION FOLIO THAT IS PART OF A GROUP FOLIO**  

- If you want to assign names to the single reservations that are part of the group, you can click on the button _Edit_ on the right hand side of each folio:  

![group_reservation_30.png]({{site.baseurl}}/images/group_reservation_30.png)


- If you want to change an existing guest (i.e. substitute an existing guest profile), then click on the button _Change_ on the right hand side of a folio.  

###**ACCESS SINGLE FOLIO WITHIN A GROUP**

You can easily access each of the folios that are part of a group directly from the Group Reservation folio.  

- To access a reservation that is part of a group, click on the reservation number on the left hand side of each folio:  

![group_reservation_31.png]({{site.baseurl}}/images/group_reservation_31.png)

