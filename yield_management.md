---
title: Yield Management
tags: [formatting]
keywords: yield management, yield rules, yield settings
last_updated: November 18th, 2015
summary: "Labels are just a simple Bootstrap component that you can include in your pages as needed. They represent one of many Bootstrap options you can include in your theme."
---  

#**Yield Management**  

The _Yield Management_ is a powerful tool of your PMS: it triggers automatic rate changes based on the occupancy level of a room type or run of house. The price change is governed by rules that you will have to place in the system, in order to define how the rates should change when certain conditions apply.  

##**Yield Management Rules**  

Let us start by defining what rules you want the system to follow.  

  - Click on the blue link **Yield Managament Rules** under section _Rates_:  
  
  ![](60.png]({{site.baseurl}}/images/60.png)  
  
  - You will notice that your account comes with a few rules already embedded. Click on the blue button _New_ to create your own rule:  
  
  ![](61.png]({{site.baseurl}}/images/61.png)  
  
  - Type in a name for the rule, and select the date range for which you want to apply the rule:  
  
  ![](62.png]({{site.baseurl}}/images/62.png)  
  
  **NOTE**: Choosing '1' as a starting day does not mean that the Yield Manager will run on any current day, but on the following one. We currently do not support yielding on day '0'.
  
  - Choose your conditions by selecting the relevant choices from the scroll down menus:  
  
  ![](64.png]({{site.baseurl}}/images/64.png)  
  
  In the example above, I have set up a rule so that if my availability is more than 80% for the date range I have selected, the system will automatically decrease the price of 20%.  
  
  - You will be able to place different rule, so long as they are not conflicting with one another. For this reason, we advise to keep these rules as straightforward as possible:  
  
  ![](65.png]({{site.baseurl}}/images/65.png)  
  
  - Once you set up your conditions, you will need to define the room types and the rates that are to be subject to those rules: check the appropriate boxes, as in the picture below. Note that you will need to use the option _Select All_ if you want the conditions to take into account a Run of House rather than a certain room type:  
  
  ![](66.png]({{site.baseurl}}/images/66.png)  
  
  It is important to understand that the availability value you place in the conditions is defined by what room types/rates the rule appiied to: in the example below, the occupancy conditions _80 %_ and _10%_ refer to the Run of House availability level; if I had chosen one room type, they would only refer to that specific room type:  
  
  ![](67.png]({{site.baseurl}}/images/67.png)

 - If you wish to remove a condition, click on the blue button _Remove_ on the right side of the relevant rule:  
 
 ![](68.png]({{site.baseurl}}/images/68.png)  
 
 To **Deactivate** a Yield Management Rule, un-check the box under the column _Status_ for the relevant rule"  
 
![](69.png]({{site.baseurl}}/images/69.png)








