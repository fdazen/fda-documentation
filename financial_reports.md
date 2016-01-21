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
 - **Cashier Report Detail**  
 - **Daily Balancing Audit Report**  
 - **Production Report**  
 - **Production Report By Month**  
 - **Rate Discrepancy Report** 
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



   
##**Cashier Report Detail**   

The _Cashier Report Detail_ will provide you with detailed payment information made on a selected date range. You will have the ability to filter by the user who posted the payment and also to show refunds. All payments are broken out into Payment Type and reservation Folio number.  


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

- 


##**Production Report (PR)**

- Breaks down Occupancy, PAX and Room Revenue by Source or Market. Also shows how much of the total Occupancy/PAX/Room Revenue the Source or Market is responsible for. It is also possible to filter by Room Types.

##**Production Report By Month (PRM)**

- A breakdown of the arrivals, rooms occupied or PAX by month and Source/Market. A line chart of the information is also supplied as a visual aid to help the user see how Source/Market information changes on a monthly basis.

- Bookings = number of folios <br />
 Room Nights = occupancy <br />
 Unique Guests = number of guests per folio <br />
 PAX = guests/night <br />

##**Rate Discrepancy Report (RDR)**

- The Rate Discrepancy Report shows any Folios that have a Price Discrepancy (i.e. the price paid differs from the default price of the rate selected). This report can also be filtered to display discounts only. Price Discrepancy is shown on a nightly basis.

- This report is on the PostgreSQL DB so accounts will not be added by default. Request "Advanced Reports" if access is necessary (will take some time to sync across)

- <span style="color:red;">This report is currently hidden from view as there's some disagreement with what it's purporting to show.</span>

##**Room Revenue Breakdown Report (RRB)**

- Gives a Folio-by-Folio breakdown of all Room Revenue that falls in between the date range selected. Revenue is broken out by category (Taxable, Non-Taxable, Tax Exempt) and also by tax label.

- There is no guest information on this report yet (only folio numbers)

##**Total Revenue Breakdown Report**

- Shows a breakdown of all Revenue and Taxes by Charge Name, Revenue Label or Revenue Category for the date range selected.

##**Trial Balance Report (TB)**

- Provides a summary of the financial transactions for a specific date. Adds the Net Transactions to the previous date's Closing Balance to give the overall balance from the Fiscal Year Start.

- i.e. You pick a Fiscal Year Start date and then a date you want to see your revenue, taxes and payments for. The Opening Balance is the total sum of all your revenue and taxes minus payments taken from the Fiscal Year Start until the day BEFORE the Run For Date.

- It then shows the total transactions for the Run For Date (ie all revenue, taxes and payments) and then adds the Net Transactions (ie sum of all transactions) to the Opening Balance to get the Run For Date's Closing Balance.

- The Opening Balance should be identical to the previous date's Closing Balance (ie the Closing Balance for running the report for one day earlier).

##**Trial Balance With Range Report (TBWR)**

- Provides a summary of the financial transactions over a date range. Adds the Net Transactions to the previous date's Closing Balance to give the overall Closing Balance from the fiscal year start.

- This report is the same as the Trial Balance Report but the Net Transactions are calculated over a date range instead of a single date (Run For Date).
