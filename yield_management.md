---
title: Yield Management
tags:
  - yield management
keywords: 'yield management, yield rules, yield settings'
last_updated: 'November 18th, 2015'
summary: >-
  The Yield Management is a powerful tool of your PMS: it triggers automatic
  rate changes based on the occupancy level of a room type or your run of house.
  The price change is governed by rules that you will have to configure in the
  system, in order to define how the rates should change when certain conditions
  apply. 
published: true
---






##**Yield Management Rules**  

Let us start by defining what rules you want the system to follow.  

  - Click on the blue link **Yield Managament Rules** under section _Rates_:  
  

![yield_1.png]({{site.baseurl}}/images/yield_1.png)




  
  - You will notice that your account comes with a few rules already embedded. Click on the blue button _New_ to create your own rule:  
  
![Yield_2.png]({{site.baseurl}}/images/Yield_2.png)


  
  - Type in a name for the rule, and select the date range for which you want the rule to apply:  
  
![Yield_3.png]({{site.baseurl}}/images/Yield_3.png)


 {{site.data.alerts.note}} Choosing '1' as a starting day **does not** mean that the Yield Manager will run on the current day, but on the following one. We currently do not support same-day yielding. {{site.data.alerts.end}} 
  
  - Choose your conditions by selecting the relevant choices from the scroll down menus:  
  
![Yield_4.png]({{site.baseurl}}/images/Yield_4.png)

 
  
  In the example above, I have set up a rule so that if my availability is more than 80% for the date range I have selected, the system will automatically decrease the price of 20%.  
  
  - You will be able to place different rules and also different conditions within the same rule, so long as they are not conflicting with one another. For this reason, we advise to keep these rules as straightforward as possible:  
  
![Yield_5.png]({{site.baseurl}}/images/Yield_5.png)

  
  
  - Once you set up your conditions, you will need to define the room types and the rates that are to be subject to those rules: check the appropriate boxes, as in the picture below. Note that you will need to use the option _Select All_ if you want the conditions to take into account a Run of House rather than a certain room type:  
  
![Yield_6.png]({{site.baseurl}}/images/Yield_6.png)

  
  It is important to understand that the availability value you place in the conditions is defined by what room types/rates the rule appiied to: in the example below, the occupancy conditions _80 %_ and _10%_ refer to the Run of House availability level; if I had chosen one room type, they would have only referred to that specific room type:  
  
![Yield_7.png]({{site.baseurl}}/images/Yield_7.png)



 - If you wish to remove a condition, click on the blue button _Remove_ on the right side:  
 
![Yield_8.png]({{site.baseurl}}/images/Yield_8.png)

 
 
 To <span class="label label-info">DEACTIVATE</span> a Yield Management Rule, go back to the rule list and un-check the box under the column _Status_ on the right hand side of the rule you want to make inactive: 
 
![Yield_9.png]({{site.baseurl}}/images/Yield_9.png)



To <span class="label label-default">EDIT</span> a rule, click on the blue link _Edit_ oin the rule list panel:  

![Yield_10.png]({{site.baseurl}}/images/Yield_10.png)


 

##**Yield Management Settings**  

Once the Yield Management Rules are created, you will need to specify how often you want the system to check and apply those rules.  

 - Click on the link **Yield Management Settings** under section _Rates_:  
 

![yield_11.png]({{site.baseurl}}/images/yield_11.png)



 
 - Using the scroll down menu, select the right time frame among the ones available, and click on the blue button _Save_ when finished:  
 
![Yield_12.png]({{site.baseurl}}/images/Yield_12.png)




 
##**Running the Yield Manager**  

The time frame you choose in the Yield Management Settings will ensure that the system periodically updates price according to occupancy levels. However, there might be times at which you may want to manually run the Yield Manager.

 - To manually run the Yield Manager, click on link _Yield Management Rules_:  
 

![yield_1.png]({{site.baseurl}}/images/yield_1.png)



 
 - Click on the blue button _Run Yield Management_:  
 
![Yield_13.png]({{site.baseurl}}/images/Yield_13.png)


 
 - To see rate changes being effective, you will need to go into the _Daily Rate Grid_: you will be able to notice the rate changes, as the latter will appear in a different color from the Base Rate.  
 
![Yield_14.png]({{site.baseurl}}/images/Yield_14.png)


{{site.data.alerts.important}} The Yield Manager won't override rates that have been manually changed in the <em>Daily Rate Grid</em>, so make sure that the rate has not been previously edited on the grid, otherwise the Yield won't work!{{site.data.alerts.end}}
