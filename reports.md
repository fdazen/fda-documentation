---
title: Reports
tags: 
  - Reports
keywords: reports
last_updated: "December 29th, 2015"
summary: "Explanations, tips and tricks for the FDA Analytics Work Area."
published: true
---



#**Reports** 


In this section, we will guide you through all the reports that are available on your account. You can find here a brief description of what each report does and how it works, so as to facilitate your information search.   
We will also describe the potential benefits that each report brings to a hotel user and we will also outline some easy troubleshooting tecniques for end users.


{{site.data.alerts.important}} As of December 2015 there is approximately a 30 minute delay between changes made to a folio and those changes being reflected on the reports. Our report database is located on a separate server that syncs once every 30 minutes. {{site.data.alerts.end}}


Our reports are located in the _Analytics_ tab, accessible from the top of your Tape Chart:  


![Reports_general_1.png]({{site.baseurl}}/images/Reports_general_1.png)



##**Report List**  

    
    
- Additional Revenue Breakdown Report (ARB)
- Adjustments Report (ADJ)
- Arrivals: Detailed Report (ARR)
- Cashier Report Detail (CRD)
- Daily Balancing Audit Report (DBA)
- Departures Report (DEP)
- Detailed Availability (DA)
- Guest List (GL)
- Guest Overnight By Country Of Origin (GON)
- Guests In House (GIH)
- House Count Report (HCR)
- Housekeeping Status Report (HSR)
- Lodging Statistics Report (LSR)
- Manager's Report (MR)
- Pace Report (PAC)
- Production Report (PR)
- Production Report By Month (PRM)
- Rate Discrepancy Report (RDR)
- Room Revenue Breakdown Report (RRB)
- Total Revenue Breakdown Report (TRB)
- Trial Balance Report (TB)
- Trial Balance With Range Report (TBWR)  



##**Before Starting**  


Our reports are organized around _Revenue Account Labels_ and _Revenue Account Categories_. Before inserting any information in your system, you should set those up in your account. To learn how to do this, go to section **Admin Settings** in this manual and check out the _Accounting_ section.
 
 
 
##**Important Things to Know**
  
  
1. Payments are entered into the system **today**. There’s nothing that allows you to enter a payment today and post it in 6 month’s time or on the guest's check-in date.  
  
2. Both additional revenue and payments are <span style="color:red;">**independent**</span> of room type and folio status, that is, there is currently no link in the reporting system between an add-on/POS item and Room Type or Folio Status. For example, on the Lodging Statistics Report, **all** additional revenue will be included every time, regardless of the Room Types, Folio Statuses and Sources/Markets selected. The same thing goes for the Daily Balancing Audit Report - **all** additional revenue and payments (Settlements) are returned regardless of Folio Statuses selected.

3. There is <span style="color:red;">**no link**</span> between payments and the charges to which they are applied. Although the payments are linked to the folios, they are not connected to a _specific_ charge on that folio. 

4. Revenue is counted on the night it is consumed - i.e. if there’s a reservation that is made today for six months in the future, that revenue will show up on reports that will be run for that time frame, and not today.

5. In the **Manager’s Report** there appear columns _Day_, _Period TD_ (ie Month TD) and _Year TD_.

  **Day**: it is the date entered in the Run For Date field among the filters.  

  **Period TD**: period that goes from the start of the current month up to and including the _Run For Date_ date.   

  **Year TD** = period that goes from the beginning of the Fiscal Year up to and including _Run For Date_ date. 

However, if the starting date of the Fiscal Year is equal to the Run For Date date, then all 3 columns will be equal. 

Some examples:  

6. If you run the report with a Fiscal Year Start of 2015-01-01 and a Run For Date of 2015-06-25, assuming we are in June, the results will be:
    
	**Day** = 2015-06-25  
    
	**Period TD** = from 2015-06-01 to 2015-06-25   
    
	**Year TD** = from 2015-01-01 to 2015-06-25  
    
 **Be careful though**, if the Fiscal Tear Start date is 2015-05-04 and the Run For Date is 2015-05-25, the Period TD won't be starting from the beginning of the month, but the beginning of the Fiscal Year:

	**Day** = 2015-05-25 
	**Period TD** = 2015-05-04 -> 2015-05-25 
	**Year TD** = 2015-05-04 -> 2015-05-25 
    
 In this case then the Period TD is equal to the Year TD.



7. You might incur into an issue where add-ons/POS items shows up on reports as _Incidental_ or _Not defined_. This will only happen if the right Revenue Labels/Categories have not been correctly set up. Look up section _Accounting_ of this manual to learn how to do that.
Note, however, that this will not automatically fix past data, and for this reason we strongly recommend to set those up before inserting any reservation in your account. If you did not do that, and wish to apply newly created labels/categories to historical data then please notify us by sending an email to _help@frontdeskanywhere.com_ and ask to resync your transactions.

8. We strongly discourage renaming Revenue Account Labels and Categories, in order to avoid situations in which report results will show up with the tag _Not Defined_. If you wish to substitute old Labels/Categories, please deactivate them and create new ones. 
