tags:
  - Stay Restrictions
keywords: 'stay restrictions, maximum/minimum stay requirement, close out'
last_updated: 'January 27th, 2017'
summary: >-
  Learn how to restrict availability or rates on Frontdesk Anywhere!
 
 
#**Stay Restrictions**  

  
##**What Are Stay Restrictions**
  
  
Stay Restrictions is the place in your Frontdesk Anywhere account where you will be able to place minimum or maximum stay requirements and close outs.
These actions are all on rate level: for any configured rate, you can define a minimum stay lenght for guests booking it or prevent guests from booking that rate altogether.  


- In the _Admin Settings_, click on the link **Stay Restrictions** under section RATES:  


![stay1.png]({{site.baseurl}}/images/stay1.png)


##**Add Min/Max Stay Requirement**  


- To add a minimum stay restriction or to limit the amount of consecutive days guests can stay at your property, click on the blue button **Add Min/Max Requirement**:  

![stay_2.png]({{site.baseurl}}/images/stay_2.png)
  
  
 - Start inserting the information requested:
 
 ![stay_3.png]({{site.baseurl}}/images/stay_3.png)
 
 
The _Description_ will appear on the booking engine as a guidance as to why guests cannot book, if their search does not meet the right criteria. Hence, we advise to keep the description straightforward, in order not to confuse your guests.  

If not sure about what days of the week the period corresponds to, select them all. The restriction will only pick up on the dates specified by the scroll down calendars.  


{{site.data.alerts.warning}}Important: restrictions work **inclusively**. This means that the restriction will be effective not only for the specific calendar/weekday you have chosen, but also for any reservation that includes those dates.  {{site.data.alerts.end}}  


Here is what this means: in the example above, I have set-up a minimum stay restriction of 2 nights for 12/22-26. The restriction will prevent guests from booking a one-night stay on those specific dates, but it will also prevent them from booking a one night stay on 12/21: this is because the check-out date would be 12/22, which is a day that is included in the restriction.  

If you want to allow a one night reservation for 12/21, then date 12/22 should not be included in the restriction. 

- Choose how the system should enforce the restriction:  
![stay_4.png]({{site.baseurl}}/images/stay_4.png)
  
  
If you want the restriction to limit guest stay if their arrival date falls within the selected period range, click on _Arrival must be within period_; if you want the restriction to limit guest stay if their departure falls within the period, choose the box _Departure must be within period_. You may also leave both boxes unchecked if you want the restriction to be applied to both arrival and departure date.  

Proceed to select the channels where the restriction should be applied to.  
  

- Finally, for each room type select the rate that should be restricted:  

![stay_5.png]({{site.baseurl}}/images/stay_5.png)
  
  
When finished, click on the blue button **Save** at the bottom of the page.


###**Important - Overlapping Minimum Stay Restrictions on Channel Integration**    

If you have multiple minimum stay restrictions enabled for the same dates like in the following example, it is important to understand how the channel manager receives the updates when one of those restriction is made inactive:

![stay_6.png]({{site.baseurl}}/images/stay_6.png)  

In the above example, there is one stay restriction (Maximum Stay 30 days) which overlaps with the other two minimum nights requirement.

If you deactivate any of the minimum stay requirements, please note that this **will also affect the maximum stay requirement**.  Here is how it works:

- When you deactivate a stay requirement, the value we send to the channel manager for those dates is of '1'. For example, if I have a 3 Nights minium stay on the nights of February 9th, 10th and 11th, the value we send to the channel manager for those dates is '3'.  
If you deactivate this stay restriction, the PMS will automatically send an update to the channel manager that for those nights the minimum stay requirement is '1', instead of '3'.

![stay_7.png]({{site.baseurl}}/images/stay_7.png)

In the example above, I have the 3 Nights minimum stay deactivated but there is still the Maximum Stay requirement set to 30 days which overlaps with those three February days.    
Since we have deactivated the 3 night minimum stay, the value that will be sent to the channel manager is now '1': **this value will automatically cancel out the 30 day Maximum Stay requirement**. In order to avoid any issues, we strongly advise to resave the Maximum Stay Requirement.  

Hence, before deactivating any stay restriction, please take a moment to check if you have any overlapping restriction active: if so, you will need to either extend the active stay restriction or create a new one. If you have any doubts, please contact our Customer Support team via email at **help@frontdeskanywhere.com**.


##**Setting up a Close-out**   

  
- In the Stay Restriction panel, click on the button **Add Close-Out Period**:  

![stay_8.png]({{site.baseurl}}/images/stay_8.png)  

- Place a brief description for the close-out. Note: this will be displayed on your booking engine as a reason why guests cannot book.  

![stay_9.png]({{site.baseurl}}/images/stay_9.png)  

  
Select the date range, relative days of the week and choose whether to limit arrivals, departures or both for the selected date range.  

- Check the **Status** box to activate the restriction upon saving the page. Also select the applicable channels and rates you want to have closed.     

![stay_10.png]({{site.baseurl}}/images/stay_10.png)
