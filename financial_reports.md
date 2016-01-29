---
title: Financial Reports
tags: 
  - Reports
  - Financial
keywords: reports
last_updated: "December 29th, 2015"
summary: A description of the financial reports in FDA.
published: true
---















#**Financial Reports**
     
       
       
The Financial Reports include all those reports that have to do with daily transactions performed at your property, and they offer a precise understanding of all financial operations. For this reason, these will mostly important to your Accounting Department. These include:  
  
  
 - **Additional Revenue Report**  
 - **Adjustments Report**  
 - **Applied Advanced Deposits Report** 
 - **Bill Add-on Charges Report**
 - **Cashier Report Detail**  
 - **Daily Balancing Audit Report**  
 - **Open Balance Report**
 - **Production Report**  
 - **Room Revenue Breakdown Report** 
 - **Total Revenue Breakdown Report**
 - **Trial Balance Report**
 - **Trial Balance With Range Report**


##**Additional Revenue Breakdown**

This report includes information about posted POS items and Add-Ons. There are a variety of filters that will allow you to choose how you want the results to displayed. This report is useful for many reasons: it allows the Accounting department to follow up with  how many actual extra charges have been sold for a certain date range, and it allows them to include a folio breakdown where you can see where in the system the charges have been posted. As results can also be organized around the user who posted the item, it comes handy if your hotel needs to calculate commission based on upsell items. 

{{site.data.alerts.important}} Additional revenue is <span style="color:red;">independent</span> of room type and folio status, that is, there is currently no link in the reporting system between an add-on/POS item and Room Type or Folio Status. This means that all additional revenue will be included every time, regardless of the Room Types, Folio Status and Sources/Markets selected. {{site.data.alerts.end}}


- In the reports list, click on the link _Additional Revenue Breakdown_:  

![Finacial_reports_1.png]({{site.baseurl}}/images/Finacial_reports_1.png)   

- Select your filters. Choose whether you wish to include POS items or/and Add-ons, Revenue Categories or/and Labels, user/s who posted the items, and whether you wish the results to include a folio breakdown. When done, clcik on the blue button _Run Report_:  

![Finacial_reports_2.png]({{site.baseurl}}/images/Finacial_reports_2.png)

- Here is an exmaple of the report:  

![Finacial_reports_3.png]({{site.baseurl}}/images/Finacial_reports_3.png)


###**Fields Legend**  

**Charge Type**: displays the type of Item that has been posted.  
**Revenue Category**: shows the Revenue Category associated with the item.  
**Revenue Label**: shows the Revenue Label associated with the item.  
**Charge Name**: displays the charge name.  
**Folio No**: Folio number associated with the charge.  
**User**: User who posted the charge.  
**Count**: Number of times the charge has been aplied to that reservation folio.  
**Avg Price**: Average charge price.  
**Non-Taxable Revenue**: sum of items where no tax is applied.  
**Taxable Revenue**: sum of items subject to tax.  
**Total Revenue**: sum of non-taxable and taxable revenue.
**Tax name**: list of applied taxes.  
**Total Taxes**: sum of all applicable taxes.  
**Total**: sum of Total Revenue and Total taxes.    

{{site.data.alerts.important}} It might happen that you see the tag _Undefined_ in your results. This simply means that there are Revenue Categories or Labels that have not been assigned to a certain item. Learn how to fix this by going into section **Admin Settings** - **Accounting** of this manual. {{site.data.alerts.end}}

  
  
##**Adjustments Report**

The _Adjustment Report_ gives you a summary of all adjustments made on each folio for a selected date range. Along with the adjustment amount, it gives information of the Department that has allowed it and the reason why it has been given out. If you want to keep track of reasons and departments, make sure to configure those in the Admin Settings, section **Accounting**: check out the configuration part of this manual to learn how to!   

- In the report list, click on the link _Adjustment Report_:  

![Finacial_reports_4.png]({{site.baseurl}}/images/Finacial_reports_4.png)

- Select the account you wish to run the report for, the date range, and click on the blue button _Run Report_:  

![Finacial_reports_5.png]({{site.baseurl}}/images/Finacial_reports_5.png)

- Here is an example of the report:  

![Finacial_reports_6.png]({{site.baseurl}}/images/Finacial_reports_6.png)
 

###**Fields Legend**    

**Folio No**: Folio hwere the adjustment was performed.  
**Date&Time**: Time and date when the adjustment was performed.  
**User**: User who performed the adjustment.  
**Reason**: Reason associated with the adjustment.  If none has been configured/chosen, then the field will show as a _Not Defined_. 
**Department**: Departement associated with the adjustment. If none has been configured/chosen, then the field will show as a _Not Defined_. 
**Quantity**:  Number of same-type adjustments performed.  
**Non-Taxable Revenue**:  value of the adjustment performed on non-taxable revenue. This field will be empty in case you have performed adjustments only on revenue where tax is applied.  
**Taxable Revenue**: value of the adjustment performed on taxable revenue. This field will be empty in case you have performed adjustments only on revenue where no tax is applied.  
**Tax/es**: total amount of tax adjusted.  
**Total Taxes**: sum of all taxes adjusted.  
**Total**: total amount of revenue and taxes adjusted.  
  
  
##**Applied Advanced Deposits Report**  
 
The _Applied Advanced Deposit Report_ shows all payments taken for a selected date range and provides general information about the associated reservation folios. The report also applies those payments against accrued revenue (Applied Deposit) and against revenue that has not yet been accrued (Advanced Deposit): for this reason, you will see a _Run for Date_ filter which will be used to calculate how much deposit has been applied and how much is advanced.  
 
- In the report list, click on the link _Applied Advanced Deposits Report_: 
 
![Finacial_reports_31.png]({{site.baseurl}}/images/Finacial_reports_31.png)
  
- Select your filters: please note that the report will show all Payments for your chosen date range (_Start Date_ and _End Date_), while the _Run for Date_  will be used by the system as the day against which to check whether a payment has been applied or is advanced.  
 
![Finacial_reports_32.png]({{site.baseurl}}/images/Finacial_reports_32.png)
 
 
In the example above, I am taking all payments posted between 01/20 through 01/31 and I am comparing it with accrued/unaccrued revenue up to 01/27.  
 
- Here is an example of this report:  
 
![Finacial_reports_33.png]({{site.baseurl}}/images/Finacial_reports_33.png)
 
 
###**Fields Legend**  
 
**Name**: guest name.  
**Room Number**: number of room associated with the reservation folio.  
**Room Type**: room type associated with the room number.  
**Check-In**: guest's arrival date.  
**Check-Out**: guest's departure date.  
**Folio No**: reservation folio number.  
**Reservation Status**: status of the reservation at the time the report was run.  
**Room Revenue**:  room charges.  
**Additional Revenue**: sum of all Add-ons and POS posted in the folio.  
**Total Revenue**: sum of the _Room Revenue_ plus the _Additional Revenue_.
**Payments**: sum of all payments posted on the folio for the selected date range. 
**Applied Deposit**: amount of payment applied to accrued revenue.  
**Advanced Deposit**: amount of payment not yet applied to revenue (deposit).  
 
 






##**Bill Add-On Charges Report**  

The _Bill Add-On Charges Report_ shows detailed information about Add-Ons items posted for a selected date range. This report also displays information about the reservation folios associated with the charge. Differently from the _Additional Revenue Breakdown_ report, the Bill Add-On report won't provide a breakdown of taxable, non-taxable revenue and taxes, as it is supposed to provide more general information about additional revenue. 

- In the report list, click on the link _Bill Add-On Charges Report_:  

![Finacial_reports_28.png]({{site.baseurl}}/images/Finacial_reports_28.png)  

- Select your filters and click on the blue button _Run Report_:  

![Finacial_reports_29.png]({{site.baseurl}}/images/Finacial_reports_29.png)


- Here is an example of this report:  
  
![Finacial_reports_30.png]({{site.baseurl}}/images/Finacial_reports_30.png)  

###**Fields Legend**  

**Name**: guest name associated with the folio number.  
**Room Number**: room number associated with the reservation folio.  
**Room Type**: room type associated with the room number.  
**Check-In**: guest's arrival date.  
**Check-Out**: guest's departure date.  
**Folio Status**: displays the status of the reservation folio at the time the report is run.  
**User**: name of the user who posted the charge.  
**Charge Type**: type of charge for which information is displayed.  
**Revenue Category**: Revenue Category associated with the charge.  
**Count**: number of items charged.  
**Total Revenue**: sum of all taxable/non-taxable revenue associated with the charge (takes account of the count number).  
**Total Taxes**: sum of all taxes applied to the posted charge.  
**Total**: sum of the _Total Revenue_ and the _Total Taxes_.  




  




   
##**Cashier Report Detail**   

The _Cashier Report Detail_ will provide you with detailed payment information made on a selected date range. You will have the ability to filter by the user who posted the payment and also to show refunds. The option _IBE_ is available to retrieve information about payments processed by your Payment Gateway by those bookings made on your Internet Booking Engine. All payments are broken out into Payment Type and reservation Folio number.  


{{site.data.alerts.important}}  
1. Payments are entered into the system today. There’s nothing that allows you to enter a payment today and post it in 6 month’s time or on the guest's check-in date.{{site.data.alerts.end}}  

{{site.data.alerts.important}}
2. Payments are <span style="color:red;">independent</span> of room type and folio status, that is, there is currently no link in the reporting system between payments and folio statuses selected.{{site.data.alerts.end}}    

{{site.data.alerts.important}}
3.There is <span style="color:red;">no link</span> between payments and the charges to which they are applied. Although the payments are linked to the folios, they are not connected to a _specific_ charge on that folio.{{site.data.alerts.end}}   

{{site.data.alerts.important}}
4. Revenue is counted on the night it is consumed - i.e. if there’s a reservation that is made today for six months in the future, that revenue will show up on reports that will be run for that time frame, and not today.{{site.data.alerts.end}}


- In the report list, click on the link _Cashier Report Detail_:  

![Finacial_reports_7.png]({{site.baseurl}}/images/Finacial_reports_7.png)  


- Select your filters, and click on the blue button _Run Report_:  

![Finacial_reports_8.png]({{site.baseurl}}/images/Finacial_reports_8.png)  


- Here is an example of the report:  

![Finacial_reports_9.png]({{site.baseurl}}/images/Finacial_reports_9.png)  


###**Fields Legend**  

**Payment Type**: The report is broken down by pay type, which will be listed on the top of the results. In the example above, there are two payment types showing, Cash and Visa.  
**Payment Date**: Date and time where the payment was posted.  
**Folio No**: Reservation Folio where the payment was posted.  
**Processed By**: User who posted the payment.  
**Amount**: Payment Amount.    




##**Daily Balancing Audit Report**

The _Daily Balancing Audit Report_ provides a breakdown of each folio and compares charges with payments posted. Charges include additional revenue. This report is really the Trial Balance report but with a folio breakdown, so we advise to run it from the beginning of your fiscal year. The Daily Balancing Audit Report is mostly useful when trying to find errors/discrepancies directly in the folio where the charges/settlements have been processed.
  
- In the report list, click on the link _Daily Balancing Audit Report_:  

![Finacial_reports_10.png]({{site.baseurl}}/images/Finacial_reports_10.png)

- Select your filters and click on the blue button _Run Report_. As mentioned above, we advise to run it from the beginning of the fiscal year, in order to have precise information:  

![Finacial_reports_11.png]({{site.baseurl}}/images/Finacial_reports_11.png)  

- Here is an example of the report:  

![Finacial_reports_12.png]({{site.baseurl}}/images/Finacial_reports_12.png)


###**Fields Legend**  
  
**Folio No**: Reservation folio Number.  
**Taxable Revenue**: Sum of all charges subject to tax. Note that if applicable, another column with the sum of all _Non-Taxable Revenue_ will appear.  
**Total**: Sum of taxable and non-taxable revenue.  
**Tax**: Name of the tax and corresponding value.  
**Total**: Total of all tax.
**Settlement**: Payment value.  
**Total**: Total sum of all payments applied.  
**Total Balance**: Displays the value of charges minus the value of settlements.  




##**Production Report**  

The _Production Report_ provides you with information about Occupancy and Revenue. This information is shown both as a numeric value and a percentage value. You can decide to organize the results of this report by Source or Market, filter them by room type and/or reservation folio status. This report also displays the average daily rate for the selected date range.  

- In the report list, click on the link _Production Report_:  

![Finacial_reports_13.png]({{site.baseurl}}/images/Finacial_reports_13.png)  

- Select your filters and click on the blue button _Run Report_:  

![Finacial_reports_14.png]({{site.baseurl}}/images/Finacial_reports_14.png)


- Here is an example of this report:  

![Finacial_reports_15.png]({{site.baseurl}}/images/Finacial_reports_15.png)
 


###**Fields Legend**  
  
**Source/Market**: Depending on your filter, this field will show the name of the source/market from/for which revenue has been produced. Note that in the example there is an _Undefined_ market: this means that the revenue values are showing for those reservations for which no market has been specified.  
**Occupancy**: Number of people.  
**PAX**:  Number of people per night.
**Total Revenue**: total revenue for the selected market and date range.  
**ADR**: Average Daily Rate.  
**Occupancy %**: Percentage of occupancy level.  
**% PAX**: Percentage of people staying at the property for the selected date range.  
**% of Revenue**: Percentage of total revenue for the selected market and date range.  



##**Room Revenue Breakdown Report**

The _Room Revenue Breakdown_ report gives you information about Room Revenue broken down  by reservation folio. The Revenue is furthermore grouped by Taxable, Non-Taxable and Tax Exempt category. The report also offers a breakdown by tax label. This is report is useful if you are looking to trace back a particular set of information to a certain reservation folio, but most importantly it offers precise infromation on how much revenue is taxable/non-taxable, and it helps understanding the total amount of each tax for the sleected date range.  

- In the reports list, click on the link _Room Revenue Breakdown_:  

![Finacial_reports_19.png]({{site.baseurl}}/images/Finacial_reports_19.png)  

- Select your filters and click on the blue button _Run Report_ when ready:  

![Finacial_reports_20.png]({{site.baseurl}}/images/Finacial_reports_20.png)  

-Here is an example of this report:  

![Finacial_reports_21.png]({{site.baseurl}}/images/Finacial_reports_21.png)
  


  
###**Fields Legend**  
  
**Folio No**: lists the folio number associated with the information shown on the other columns.  
**Check-In/Check-out Dates**: shows the arrival and departure date associated with the reservation folio.  
**Source**: displays the name of the source associated with the folio.  
**Market**: displayes the name of the Market associated with the folio.  
**Revenue Label**: lists the Revenue Label associated with the charge.  
**Taxable Revenue**: displays the amount of all revenue on which tax is applied.  
**Non-Taxable Revenue**: displays the amount of revenue not subject to any tax.  
**Total Revenue**: sum of _Taxable_ and _Non-Taxable_ columns.  
**Tax Name**: Lists the amount of each tax applied to the reservation folio.  
**Total Taxes**: sum of all applicable taxes.  
**Total**: Sum of _Total Revenue_ and _Total Taxes_ columns.





##**Total Revenue Breakdown Report**
  
The _Total Revenue Breakdown_ report shows information on all revenue, broken down by Renue Labels or Categories. Differently from the _Room Revenue Breakdown_ report, it includes information about all items for sale at your property, including Add-ons and POS. This report is useful to have precise information on revenue and taxes applicable at your property. Information will be grouped by charge type (Add-on, Lodging, Pos, etc.) and you will also be able to look into the relevant Revenue Category/Label associated with each charge.  

- In the reports list, click on the link _Total Revenue Breakdown Report_:  

![Finacial_reports_22.png]({{site.baseurl}}/images/Finacial_reports_22.png)  

- Choose your filters and click on the blue button _Run Report_:  

![Finacial_reports_23.png]({{site.baseurl}}/images/Finacial_reports_23.png)  

- Here is an example of this report:  

![Finacial_reports_24.png]({{site.baseurl}}/images/Finacial_reports_24.png)  


###**Fields Legend**:  

**Charge Type**: lists whether the charge reported on is an Add-on, a POS, or a Room Revenue.  
**Revenue Category/Revenue Label**: lists the name of either the Revenue Category or Label, depending on what you have selected as your fitler.  
**Taxable Revenue**: displays the amount of revenue subject to tax. Note that column _Non-Taxable Revenue_ will also appear, in case there are items sold at your property that are not subject to any tax application.
**Total Revenue**: sum of _Non-Taxable Revenue_ and _Taxable Revenue_. If one of these column is missing, then the Total Revenue will be the same as the column displayed.  
**Tax**: diplays a breakdown of each tax applied.  
**Total Taxes**: sum of all taxes applied.  
**Total**: sum of the _Total Revenue_ and _Total Taxes_ columns.  




##**Trial Balance Report (TB)**
  
The _Trial Balance Report_ provides a summary of all financial transactions for a specific date, and compares it with information from the beginning of the fiscal year. It displays three important pieces of information: the _Opening Balance_, the _Transaction Net_ and the _Closing Balance_.
The Opening Balance is the sum of the Total Revenue plus all Taxes minus all Payments, from the beginning of the fiscal year up to the day prior to running the Trial Balance report.
You will need to choose a date on which to run the Trial Balance: for that selected date, the report will show a summary of all revenue broken down by charge type, all tax and also a summary of all payments recorded for that date, thus giving what we call a Transaction Net.  
The Transaction Net will then be summed up to the Opening Balance, thus giving what we call the Closing Balance, which is the resulting balance for the hotel for the beginning of the fiscal year. 
Remember that you will need to manually select the starting date of your Fiscal Year, by choosing the report filters!  
Note that the Opening Balance should always be identical to the previous date's Closing Balance.  

- In the reports list, click on the link _Trail Balance Report_:  

![Finacial_reports_25.png]({{site.baseurl}}/images/Finacial_reports_25.png)  

- Select your filters and click on the blue button _Run Report_. Be careful to choose the correct starting date for your Fiscal Year:  

![Finacial_reports_26.png]({{site.baseurl}}/images/Finacial_reports_26.png)

- Here is an example of this report:  
  
![Finacial_reports_27.png]({{site.baseurl}}/images/Finacial_reports_27.png)
 


###**Fields Legend***:  

**Opening Balance**: Total Revenue plus Taxes, minus Payments from the Fiscal Year Start until the day before the Run For Date.  
**Revenue and Taxes**: displays a breakdown of Total Revenue, broken down by revenue and applicable taxes.  
**Payments**: shows the total payments recorded for the selected date and it breaks information down by payment types.
**Transaction net**: the day’s Net Transactions (Total Revenue plus Total Taxes minus Total Payments).
**Closing Balance**: Opening Balance plus Transaction Net.  




##**Trial Balance With Range Report**

The _Trial Balance With Range Report_ provides a summary of all financial trnasaction for a selected date range. This report is the same as the _Trial Balance_, but it offers a date range, rather than a single date (Run for Date).
For instructions, read the _Trial Balance Report_ section.
