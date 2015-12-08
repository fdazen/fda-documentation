---
title: Yield Management
tags: 
  - formatting
keywords: "yield management, yield rules, yield settings"
last_updated: "November 18th, 2015"
summary: Labels are just a simple Bootstrap component that you can include in your pages as needed. They represent one of many Bootstrap options you can include in your theme.
published: true
---



  

#**Yield Management**  

The _Yield Management_ is a powerful tool of your PMS: it triggers automatic rate changes based on the occupancy level of a room type or run of house. The price change is governed by rules that you will have to place in the system, in order to define how the rates should change when certain conditions apply.  

##**Yield Management Rules**  

Let us start by defining what rules you want the system to follow.  

  - Click on the blue link **Yield Managament Rules** under section _Rates_:  
  
  ![60.png]({{site.baseurl}}/images/60.png)

  
  - You will notice that your account comes with a few rules already embedded. Click on the blue button _New_ to create your own rule:  
  
![61.png]({{site.baseurl}}/images/61.png)

  
  - Type in a name for the rule, and select the date range for which you want to apply the rule:  
  
  ![62.png]({{site.baseurl}}/images/62.png)

  
  **NOTE**: Choosing '1' as a starting day does not mean that the Yield Manager will run on any current day, but on the following one. We currently do not support yielding on day '0'.
  
  - Choose your conditions by selecting the relevant choices from the scroll down menus:  
  
![64.png]({{site.baseurl}}/images/64.png)
 
  
  In the example above, I have set up a rule so that if my availability is more than 80% for the date range I have selected, the system will automatically decrease the price of 20%.  
  
  - You will be able to place different rule, so long as they are not conflicting with one another. For this reason, we advise to keep these rules as straightforward as possible:  
  
![65.png]({{site.baseurl}}/images/65.png)
  
  
  - Once you set up your conditions, you will need to define the room types and the rates that are to be subject to those rules: check the appropriate boxes, as in the picture below. Note that you will need to use the option _Select All_ if you want the conditions to take into account a Run of House rather than a certain room type:  
  
![66.png]({{site.baseurl}}/images/66.png)
  
  It is important to understand that the availability value you place in the conditions is defined by what room types/rates the rule appiied to: in the example below, the occupancy conditions _80 %_ and _10%_ refer to the Run of House availability level; if I had chosen one room type, they would only refer to that specific room type:  
  
![67.png]({{site.baseurl}}/images/67.png)


 - If you wish to remove a condition, click on the blue button _Remove_ on the right side of the relevant rule:  
 
![68.png]({{site.baseurl}}/images/68.png)
 
 
 To **DEACTIVATE** a Yield Management Rule, un-check the box under the column _Status_ for the relevant rule"  
 
![69.png]({{site.baseurl}}/images/69.png)


To **EDIT** a rule, click on the blue link _Edit_ on the right hand side of the rule list:  

![70.png]({{site.baseurl}}/images/70.png)
 

##**Yield Management Settings**  

Once the Yield Management Rules are created, you will need to specify how often you want the system to perform the rate change.  

 - Click on the link **Yield Management Settings** under section _Rates_:  
 
![80.png]({{site.baseurl}}/images/80.png)

 
 - Using the scroll down menu, select the right time frame:  
 
![71.png]({{site.baseurl}}/images/71.png)

 
##**Running the Yield Manager**  

The time frame you have chosen in the Yield Management Settings will ensure that the system periodically updates price according to occupancy levels. However, there might be times at which you may want to manually run the Yield Manager.

 - To manually run the Yield Manager, click on link _Yield Management Rules_:  
 
![72.png]({{site.baseurl}}/images/72.png)

 
 - Click on the blue button _Run Yield Management_:  
 
![73.png]({{site.baseurl}}/images/73.png)

 
 - To see how the Yield is changing the rates, you will need to go into the _Daily Rate Grid_: you can see what has been changed from the different color the rates will have.  
 
![74.png]({{site.baseurl}}/images/74.png)
  
 
 **NOTE**: the Yield Manager won't override rates that have been manually changed in the  _Daily Rate Grid_, so make sure that the rate has not been edited on the grid, otherwise the Yield won't work!
