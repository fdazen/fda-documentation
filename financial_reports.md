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
     
       
       
The Financial Reports include all those reports that have to do with daily transactions performed at your property, and are mostly important for the Accounting Department. These include:  
  
  
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


##**Additional Revenue Breakdown (ARB)**

- <p>
	This report shows any add-ons and pos items posted within the query range selected. Has nested filtering - you can filter by Charge Type (Add-on/POS) then by Revenue Category and Revenue Label. Also allows for filtering of charges posted by certain users. This can be handy for hotels wanting to calculate commissions based on upsell items for example.

	Can also display a folio breakdown of charges so the user can see what folio certain charges were applied to. Again, it’s important to remember that Add-on/POS items ignore Folio Status so if the charge is undeleted and posted in the range selected then it will show in the report regardless of the folio status.
	</p>

##**Adjustments Report (ADJ)**

- This report shows any adjustments posted within the query range selected. In V2 Adjustments are only accessible after Night Audit has been run on a property whereas in V3 Adjustments have replaced discounts.

##**Cashier Report Detail (CRD)**

- Lists all Payments posted in the date range selected. Can be configured to filter by user and to show only refunds made if necessary. Payments are broken out by Payment Type and Folio No.

- It is important to note that payments are displayed based on the date they’re entered into the system. Payments entered today cannot be counted on a check in that’s 6 months in the future.

- Mention: Time Filter to filter by hour and Security Deposit Breakout for Report (needs new datafeed though)

##**Daily Balancing Audit Report (DBA)**

- Provides a folio level breakdown of every transaction (Room Revenue, Additional Revenue, Settlements) against a folio from the fiscal year start until the date it was run for.

- This report is effectively a folio breakdown of the Trial Balance. It is designed to be run from the first date of the hotel until yesterday. Otherwise numbers may be misleading (especially balances).

- Groups need to be handled better in the datafeed (future project) so folios that are part of groups are a bit confusing at the minute.

- There is no guest information on this report yet (only folio numbers)

##**Lodging Statistics Report (LSR)**

- Get a day-by-day breakdown of your lodging information and revenue over a period of your choosing. You can look at historical data and forecast future information too. Can filter on source, market and room type.

- Multiple Properties are aggregated (ie compiled together) and not shown sequentially.

##**Manager's Report (MR)**

- Intended as a quick report for a manager to look at. It shows daily, month-to-date and year-to-date information for the property's lodging statistics, revenue and settlements made. It also includes forecasting information up to 1 year in the future.

##**Pace Report (PAC)**

- Likely to be renamed something like “Business Pick Up Report”

- The Reservation Booking Pace captures how many individual and business block reservations were on the books on any specific day, and tracks booking trends to maximize revenues.

- Basically, put in a date range you want to see occupancy %/revenue/adr for and then compare those values between 2 dates. i.e. I want to see what my OTB numbers and revenue for November 01 - 30 were on October 20th and then again on October 25th so I can see how many bookings I've picked up/lost in those 5 days.

- This report is on the PostgreSQL DB so accounts will not be added by default. Request "Advanced Reports" if access is necessary (will take some time to sync across)

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
