---
title: Reports
tags: [Reports]
keywords: "reports"
last_updated: "December 29th, 2015"
summary: Explanations, tips and tricks for the FDA Analytics Work Area.
published: true
---


#**Reports** 

The purpose of this set of pages is to describe what each report does and how it works, potential benefits of each report to a hotel user and outline some troubleshooting techniques for end users.

{{site.data.alerts.important}} As of December 2015 there is approximately a 30 minute delay between changes made to a folio and those changes being reflected on the reports. This is because the reporting database is on a separate server and it syncs once every 30 minutes. {{site.data.alerts.end}}

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

##**Important Things to Note**

- Both Additional Revenue and Payments are <span style="color:red;">INDEPENDENT</style> of Room Type and Folio Status. What this means is that there is currently no link in the reporting system between an Add-on/POS Item and the Room Type or Folio Status. So for e.g. on the LSR, ALL Additional Revenue will be included every time regardless of the Room Types, Folio Statuses and Sources/Markets selected. The same thing goes for the DBA - ALL Additional Revenue and Payments (Settlements) are returned regardless of Folio Statuses selected.

- In V2 there is NO LINK between payments and the charges they are applied to. There is nothing to say that this payment of $X was made against a guest’s restaurant bill but this payment of $Y was for their night’s stay..

- Payments are entered into the system TODAY. There’s nothing that allows you to enter a payment today and post it in 6 month’s time on the check-in date.

- Similarly, revenue is counted on the night it is consumed - i.e. if there’s a reservation that is made today for 6 months in the future, that revenue will only show up on reports 6 months down the line. There is no report that lets you count revenue on the same night that a deposit was entered for example.

- The Manager’s Report Day, Period TD (ie Month TD) and Year TD columns.
Day = the date entered in the Run For Date field
Period TD = from the start of the current month up to and including the Run For Date date
Year TD = from the Fiscal Year Start up to and including Run For Date
However, if Fiscal Year Start = Run For Date then all 3 columns will be equal.
The Period TD column counts values from the 1st day of the month selected in the Run For Date up to and including the Run For Date date.
Some examples:
If I run the report with a Fiscal Year Start of 2015-01-01 and a Run For Date of 2015-06-25 we have….
Day = 2015-06-25
Period TD = 2015-06-01 -> 2015-06-25
Year TD = 2015-01-01 -> 2015-06-25
BE CAREFUL THOUGH, if the following parameters are selected:
Fiscal Year Start of 2015-05-04
Run For Date of 2015-05-25 
Then we have:
Day = 2015-05-25
Period TD = 2015-05-04 -> 2015-05-25

Year TD = 2015-05-04 -> 2015-05-25

In this case then the Period TD = Year TD
Some customers may have issues where Additional Revenue shows up on reports as something like “Incidental” or “Not defined”. This is because they have not set up revenue categories/labels correctly. To fix this, they have to create the labels and/or categories as required in v2 and then apply them to charges. This will not automatically fix historical data. If they want labels and categories applied to historical data then you will have to ask either me or Shane to ‘resync their transactions’.

One thing that should not ever be done in V2 is renaming labels/categories. If a customer wants a different label then they should deactivate the old one and create a new label. Renaming them will break the link between charges and labels/categories and cause them to be sent as ‘Not Defined’.
