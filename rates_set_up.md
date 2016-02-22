---
title: Rates Set Up
tags: 
  - rate set up
keywords: "rates, taxes, add-ons, master rates, derived rates, duplicate rates, daily rate grid, season periods"
last_updated: "November 17th, 2015"
summary: "This section covers everything you need to know about rates set-up, taxes, fees and add-ons. We will start with tax and fee creation before going into the different ways you can reproduce your rate structure into Frontdesk Anywhere."
published: true
---






##**Taxes and Fees**
  
As a first thing, you will need to set up all applicable fees and taxes.  


 - In the Admin Settings, click on the link **Taxes** under section _Rates_:  

![Taxes_1.png]({{site.baseurl}}/images/Taxes_1.png)



You will see a list of the existing taxes in the system: your Frontdesk Anywhere comes with three default taxes. At the moment although it is possible to deactivate a tax, it is not possible to erase it: hence, we advise to edit the existing ones, before creating new ones, as this will help keep your account cleaner.


 - To edit a tax, click on the blue link _Edit_ on the right hand side of the tax you want to amend:  
 
![Taxes_2.png]({{site.baseurl}}/images/Taxes_2.png)


 
 - Insert all information requested: the _Tax Title_ will appear in each reservation where the tax is applied, so we advise it to keep the name simple.   
You will need to choose whether to make the tax a fixed amount or a percentage by clicking on the right circle box. If you choose to make the tax a flat fee to be added, specify whether the amount has to be added on a per reservation or per night basis:  
 
![Taxes_3.png]({{site.baseurl}}/images/Taxes_3.png)



 
 - If you are creating an inclusive tax, tick the box with the tag _Inclusive Tax_: if this box is checked, the tax will only appear when reporting, and it won't show anywhere in reservations. 
 
![Taxes_4.png]({{site.baseurl}}/images/Taxes_4.png)




 - Once you have done, click on the _Save_ button: if you need to create a new tax, click on the blue button _Add a Tax_; the process is the same as editing one:  

![Taxes_5.png]({{site.baseurl}}/images/Taxes_5.png)


 

###**Tax Operations**  

<span class="label label-info">Deactivate</span> to make a tax inactive, simply uncheck the box under column _Status_, on the right hand side of the relevant tax:  


![Tax_6.png]({{site.baseurl}}/images/Tax_6.png)


{{site.data.alerts.note}} As mentioned before, it is not possible to erase a tax: however, making a tax inactive will ensure that the tax won't show up anywhere in the system.  {{site.data.alerts.end}}



##**Rates Set-Up**  

There are different ways you can create and operate on a rate in Frontdesk Anywhere, but before starting it would be good to spend a few words on our terminology: this will make you become more familiar with the instructions written below.  

A **Rate Class** is the heart of your rate configuration: from here you can define the type of rate you want to create, decide the channels on which it is to be distributed, apply taxes, and create _Season Periods_. 

A **Season Period** is the area of the Rate Class where you place the actual price for your rooms and charges for extra occupancy. As the name suggests, Season Periods are intended to be used to set up rates for extended periods of time, like for high/low season. You will still be able to change the price on a daily basis by using the _Daily Rate Grid_.

The **Daily Rate Grid** is where you can view and perform adjustments on the rate for any day of the year.


###**Rate Classes**

Although the system comes with a couple of rates already built-in, it will be good to start by creating a brand new rate.  

 - In the Admin Settings, click on the blue link **Rate Classes** under section _Rates_ and click on the blue button _NEW_ at the bottom of the page:  


![Rate_Classes_1.png]({{site.baseurl}}/images/Rate_Classes_1.png)



 
 - You are now in the heart of a rate configuration, and you will see different information to fill in. Let's start by placing a name for your new rate, next to the tag _Rate Code_, and a brief description of the rate:  
 

![Rate_Classes_2.png]({{site.baseurl}}/images/Rate_Classes_2.png)


  
 
 If you are using the Frontdesk Anywhere booking engine, you will see the description show up underneath the name of the rate, when a guest is trying to make reservation online: for this reason, we advise to keep the description simple.
 
 - Check the box _Active_ if you want the rate to be enabled upon creation, and check the box _Allow Override_ if you want to enable the possibility to edit the rate on a reservation basis. Also, check the boxes for all the rate's applicable taxes:  
 

![Rate_Classes_3.png]({{site.baseurl}}/images/Rate_Classes_3.png)


 
If you choose to check the _Allow Override_ box, the rate will become editable on the reservation folio. This means that the _Edit Rate_ link will become clickable.  


![Rate_Classes_4.png]({{site.baseurl}}/images/Rate_Classes_4.png)



For more information on how to edit a rate on a per reservation basis, click here.  

- Specify the type of rate you are creating by selecting the right option in the scroll down menu, next to the tag _Rate Type_:  

![Rate_Classes_5.png]({{site.baseurl}}/images/Rate_Classes_5.png)



If you choose the option _Nightly_ rate, the value you will insert will be considered as the nightly price.  
If you choose the option _Multiple Nights_, you will need to specify how many nights the rate is valid for. You can place a numeric value in the box _Rate Is Valid For_. The value you insert will be considered as the total price for the number of nights you define in that box.   


In the example below I am creating a weekly rate: 

![Rate_Classes_6.png]({{site.baseurl}}/images/Rate_Classes_6.png)


 

Keep in mind that if you create a multiple nights rate, the latter will not show up anywhere unless the minimum number of nights are selected.  

{{site.data.alerts.important}}  If you create a Nightly rate, you will still be given the option to place a minimum night stay requirement: {{site.data.alerts.end}}

 
![Rate_Classes_7.png]({{site.baseurl}}/images/Rate_Classes_7.png)

 

However, note that differently from the Multiple Nights Rate, the value you place for the rate will be the nightly price.  

 - Select the right Revenue Label in the drop down menu next to the tag _Revenue Label_:  
 
![Rate_Classes_8.png]({{site.baseurl}}/images/Rate_Classes_8.png)


###**Season Periods**
 
 - It is now time to set up the _value_ for your rate. This will be done via the _Season Periods_: a Season Period is what allows you to build different rates for different times of the year within one rate, and also to create prices for different days of the week. Think of a Season Period as correspondent with seasons rates, as for example 'High Season', 'Low Season', etc. 
 You can start by clicking on the little icon next to the tag _Add Period_:  

![Rate_Classes_9.png]({{site.baseurl}}/images/Rate_Classes_9.png)



 - Insert all information requested: use the scroll down calendars to select the starting and ending date for the rate, place a description if necessary, select the days of the week you want the value to be valid for, and finally place the value for the rate in the first box:  
 
![Rate_Classes_10.png]({{site.baseurl}}/images/Rate_Classes_10.png)




You can add additional charges in the relevant boxes, if applicable. In the example above the base rate will be $100, there is no extra charge for the second occupant, but an extra $10 for any additional person and $5 for any child.
Click on the button _Save_ when done.

 -  You will now see your Season Period saved:  
 
![Rate_Classes_11.png]({{site.baseurl}}/images/Rate_Classes_11.png)



 
The three icons that appear under the column _Action_ are used to visualize/edit the season period, cancel it and duplicate it. Hovering on the icon will also explain to you what each one does:  

![Rate_Classes_12.png]({{site.baseurl}}/images/Rate_Classes_12.png)




 - Duplicating a season period comes handy when you are building a weekend rate that is different from the weekly one: indeed, the starting/ending date for the season period will be the same, what is different is the value and the days of the week to which the rate applies. Hence, click on the icon to duplicate the season period and amend the relevant fields:  
 
![Rate_Classes_13.png]({{site.baseurl}}/images/Rate_Classes_13.png)



 
 Click on _Save Period As Duplicate_ when finished.
 
 - You can continue to create more Season Periods by clicking on the button _Add Period_:  
 
![Rate_Classes_14.png]({{site.baseurl}}/images/Rate_Classes_14.png)


  
 
 - Finally, you will need to choose what are the room types to which the rate will be applied to, and the channels on which it will be available:  
 
![Rate_Classes_15.png]({{site.baseurl}}/images/Rate_Classes_15.png)





You will see a list of available channels (IBE, Frontdesk, Innlink, Zen, etc.): most of these channels are only available for integration purposes, hence you can ignore them as they require the assistance of one of our integration member team. You can take care of the first two, _IBE_ and _FRONTDESK_: the first box will enable the rate on your online booking engine, the second will enable it for your Tape Chart
 
 - Once all information are placed, you can save the rate. There are different ways you can save a rate: clicking on the button _Save_ will save the rate and remind you to the list of existing rates; clicking on the button _Save & Duplicate Rate_ will save the rate and create a duplicate one.  
 
 
##**Duplicate a Rate**  
 
 Duplicating a rate will come handy when you are trying to set up different rates for different room types. We are starting from the idea that although the value of the rate will be different, your Season Periods will probably be the same: a High Season, for example, is defined by the starting/ending date. Hence, instead of having to re-build all Season periods for each of your room type, you can duplicate an existing Rate Class with all its Season Periods, and simply place a different value in it!
 
 - In the _Rate Classes_, click on the button **Duplicate** on the right hand side of the relevant rate: 
 
 
![Rate_Classes_16.png]({{site.baseurl}}/images/Rate_Classes_16.png)



 
 - You will now need to amend all the information that is different from the rate you are duplicating from: commonly these are _Rate Code_, _Rate Description_, vlaue in each _Season Period_ and _Room Type_ applied:  
 
![Rate_Classes_17.png]({{site.baseurl}}/images/Rate_Classes_17.png)





##**Daily Rate Grid**  

The Rate Grid is the tool via which you can see and change the rates on a daily basis. It is also a great tool to change rates for shorter time frames like 'New Years Eve'!  

 - In the _Rate Classes_, click on the blue link **View** on the right hand side of any rate:  

![Rate_Classes_18.png]({{site.baseurl}}/images/Rate_Classes_18.png)




 - You will see a daily breakdown of the rate you have set up in the corresponding Rate Class:  

![Rate_Classes_19.png]({{site.baseurl}}/images/Rate_Classes_19.png)




 - All the boxes are editable, so you can just amend the rate by inserting a new value for any day:  
 
![Rate_Classes_20.png]({{site.baseurl}}/images/Rate_Classes_20.png)



 
 - Once you amend and save the rate, you will see that the adjusted rate appears ina different color; the rate will be green if you are going over the rate set up in the Rate Class:  
 
![Rate_Classes_21.png]({{site.baseurl}}/images/Rate_Classes_21.png)



 
 - It will show in red, if instead you are going below your base rate:  
 
 
![Rate_Classes_22.png]({{site.baseurl}}/images/Rate_Classes_22.png)


 
 
 - In order to see what was the rate set up in your Rate Class, just hover the mouse over the boxes:  
 
![Rate_Classes_23.png]({{site.baseurl}}/images/Rate_Classes_23.png)


 - Use the scroll down calendar to move across dates:  
 
![Rate_Classes_24.png]({{site.baseurl}}/images/Rate_Classes_24.png)



 
 - You can also move across rate classes by selecting another rate from the scroll down calendar on the right hand side of the screen:  
 
![Rate_Classes_25.png]({{site.baseurl}}/images/Rate_Classes_25.png)




- If your rate is applied to different room types, you will have a row for each of those types, so that you can easily edit them:  

![Rate_Classes_26.png]({{site.baseurl}}/images/Rate_Classes_26.png)





- If the rate you are viewing has a derived rate linked to it, the latter will automatically change accordingly any time that the Master rate is changed,:  

![Rate_Classes_27.png]({{site.baseurl}}/images/Rate_Classes_27.png)




- If you do not wish the derived rate to be changed, you can un-check the box with the tag _Apply to Derived Rates_:  

![Rate_Classes_28.png]({{site.baseurl}}/images/Rate_Classes_28.png)




- If your the derived rate is applied to different room types, note that the rate will change only for those Derived Rates applied to the same room type as the Master Rate; if you want it to apply to all room types, then check the box next to the tag _Apply to All Room Types_:  

![Rate_Classes_29.png]({{site.baseurl}}/images/Rate_Classes_29.png)




##**Deriving a Rate**  
 
 You can create a new rate by applying a certain discount/premium on the value of an existing Rate Class: the new rate is called a _Derived Rate_. Derived rates are linked to the master rate (the one you are deriving them from) in virtue of a certain adjustment you set up. For example, if you are running a 10% promotion for returning guests, you can create these promotional rates by deriving it from the master rate and set an adjustment of a 10% discount. Every time you change the master rate, the derived rate will also be automatically calculated.
 
 - In the _Rate Class_ list, click on the blue link **Derive** under column _Action_:  
 
![Rate_Classes_30.png]({{site.baseurl}}/images/Rate_Classes_30.png)



 
 - Type in a name for the new rate and a new description, and select the type of adjustment you want to make:  
 
![Rate_Classes_31.png]({{site.baseurl}}/images/Rate_Classes_31.png)


 
 
 You can either discount a rate or increase it (_Premium_), and you can select whether the adjustment has to be a percentage or a fixed value over the Master Rate.  

 - Select the rooms to which the rate is to be applied and the channels and click on the blue button _Save_ when finished:  
 
![Rate_Classes_32.png]({{site.baseurl}}/images/Rate_Classes_32.png)




 
 - If you go back to the _Rate Class_ List, you will notice that the derived rate appears in that list marked with a capital, bold **D** and an arrow. The latter points to the Derived Rate's Master Rate:  
 
![Rate_Classes_33.png]({{site.baseurl}}/images/Rate_Classes_33.png)



 
##**Making a Rate Inactive**
 
As for rooms, rates cannot be completely erased from the system; however, you can make them inactive by unchecking the box under the column _Status_ for any row:  
 
![Rate_Classes_34.png]({{site.baseurl}}/images/Rate_Classes_34.png)




##**Rate Priority**  

If you are building different rates for the same room type, you may want to control what is the default rate that comes up when an agent is making a reservation.

When you open a folio, all applicable rates for the room type appear in the scroll down menu on the right hand side of the panel:  

![Rate_Classes_35.png]({{site.baseurl}}/images/Rate_Classes_35.png)




Unless you order your rates, they will appear randomly in the folio: for example, in the picture above my AAA rate shows up before the BAR rate.

  - In the Admin Settings, click on **Rate Priority** under section _Rates_:  
 
![Rate_Classes_36.png]({{site.baseurl}}/images/Rate_Classes_36.png)



 
 - You will see a list of all the rates you have created in the system, independently of the room types where they are applied:  
 
![Rate_Classes_37.png]({{site.baseurl}}/images/Rate_Classes_37.png)



 
 - Replace the _999_ number with a progressive numeric order: in the example below I am setting my BAR rates to show up first:  
 
![Rate_Classes_38.png]({{site.baseurl}}/images/Rate_Classes_38.png)



 
 - Click on the blue button _Save_, and you will see your rates in the order you placed.  
 
![Rate_Classes_39.png]({{site.baseurl}}/images/Rate_Classes_39.png)



 
 Remember to log out and log back in into the system in order to see changes being effective!
