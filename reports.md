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

Our reports are organized around _Revenue Account Labels_ and _Revenue Account Categories_. Before inserting any information in your system, you should set those up in your account. To learn how to do this, go to section **Admin Settings** and check out the _Accounting_ section.

##**Important Things to Note**

- Both Additional Revenue and Payments are <span style="color:red;">**independent**</span> of Room Type and Folio Status. What this means is that there is currently no link in the reporting system between an Add-on/POS Item and the Room Type or Folio Status. So for e.g. on the LSR, **all** Additional Revenue will be included every time regardless of the Room Types, Folio Statuses and Sources/Markets selected. The same thing goes for the DBA - **all** Additional Revenue and Payments (Settlements) are returned regardless of Folio Statuses selected.

- In V2 there is <span style="color:red;">**no link**</span> between payments and the charges they are applied to. There is nothing to say that this payment of $X was made against a guest’s restaurant bill but this payment of $Y was for their night’s stay.

- Payments are entered into the system **today**. There’s nothing that allows you to enter a payment today and post it in 6 month’s time on the check-in date.

- Similarly, revenue is counted on the night it is consumed - i.e. if there’s a reservation that is made today for 6 months in the future, that revenue will only show up on reports 6 months down the line. There is no report that lets you count revenue on the same night that a deposit was entered for example.

- <p>The Manager’s Report Day, Period TD (ie Month TD) and Year TD columns. <br />
Day = the date entered in the Run For Date field <br />
Period TD = from the start of the current month up to and including the Run For Date date <br />
Year TD = from the Fiscal Year Start up to and including Run For Date <br />
However, if Fiscal Year Start = Run For Date then all 3 columns will be equal. <br />
The Period TD column counts values from the 1st day of the month selected in the Run For Date up to and including the Run For Date date. <br />
Some examples: <br />
	- If I run the report with a Fiscal Year Start of 2015-01-01 and a Run For Date of 2015-06-25 we have... <br />
	Day = 2015-06-25 <br />
	Period TD = 2015-06-01 -> 2015-06-25 <br />
	Year TD = 2015-01-01 -> 2015-06-25 <br />
	- **Be careful though**, if the following parameters are selected:
	Fiscal Year Start of 2015-05-04 <br />
	Run For Date of 2015-05-25 <br />
	Then we have: <br />
	Day = 2015-05-25 <br />
	Period TD = 2015-05-04 -> 2015-05-25 <br />
	Year TD = 2015-05-04 -> 2015-05-25 - In this case then the Period TD = Year TD <br />
</p>

- Some customers may have issues where Additional Revenue shows up on reports as something like “Incidental” or “Not defined”. This is because they have not set up revenue categories/labels correctly. To fix this, they have to create the labels and/or categories as required in v2 and then apply them to charges. This will not automatically fix historical data. If they want labels and categories applied to historical data then you will have to ask either me or Shane to ‘resync their transactions’.

- One thing that <span style="color:red;">**should not**</span> be done in V2 is renaming charges and labels/categories. If a customer wants a different charge name or label then they should deactivate the old one and create a new label. Renaming them will break the link between charges and labels/categories and cause labels and categories to be sent as ‘Not Defined’.
