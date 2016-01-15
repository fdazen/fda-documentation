---
title: Operation Reports
tags: 
  - Reports
  - Operations
keywords: reports
last_updated: "December 29th, 2015"
summary: FDA Operational Reports.
published: true
---



#**Operation Reports**
   
The Operation Reports include all those reports that are mostly important for Front Desk daily operational tasks. These include:  

 - **Arrivals: Detailed Report (ARR)**  
 - **Departures Report (DEP)**  
 - **Detailed Availability (DA)**  
 - **Guest List (GL)**  
 - **Guest Overnight By Country Of Origin (GON)**  
 - **Guests In House (GIH)**  
 - **House Count Report (HCR)**  
 - **Housekeeping Status Report (HSR)**  
 
 

##**ARRIVALS: Detailed Report (ARR)**

- This report will display all reservations meeting the specified criteria for the selected date range. One of the benefits of using this report is that it allows the flexibility of selecting a range of arrival dates or a range of stay dates.

- This report is on the PostgreSQL DB so accounts will not be added by default. Request "Advanced Reports" if access is necessary (will take some time to sync across)

##**Departures Report (DEP)**

- The Departures Report lists all departure rooms scheduled for a specified date. Can be sorted Alphabetically or by Room Number.

- This report is on the PostgreSQL DB so accounts will not be added by default. Request "Advanced Reports" if access is necessary (will take some time to sync across)

##**Detailed Availability (DA)**

- The Detailed Availability Report displays availability based on room types for a specified date range. The report can reflect either Availability or Occupancy.

- This report is basically a display of the Tape Chart that shows either Occupancy or Availability and can be filtered by Room Type.

- This report is on the PostgreSQL DB so accounts will not be added by default. Request "Advanced Reports" if access is necessary (will take some time to sync across)

##**Guest List (GL)**
- Lists the guests who Arrived, Departed and/or were a Stayover for a specified date range.

- It's basically the guest contact report from v2 (includes emails etc) but lets you filter for Arrivals/Departures/Stayovers. You can run for multiple stay statuses at once so for the minute this report (with all Arrivals, Departures and Stayovers selected) and the Manager's Report should replace the Night Audit Report in v2.

- If Additional Guests are selected then the Primary Guest is displayed in bold text.

- This report is on the PostgreSQL DB so accounts will not be added by default. Request "Advanced Reports" if access is necessary (will take some time to sync across)

##**Guest Overnight By Country Of Origin (GON)**

- Breaks down Bookings, Room Nights and Unique Guests by Country over a user selected date range.

- Bookings = number of folios <br />
Room Nights = occupancy <br />
Unique Guests = number of guests per folio <br />
PAX = guests/night <br />

##**Guests In House (GIH)**

- The Guests in House by Room Number/Alpha Report displays a variety of information for guests in house and sorts by room number. Change the sort order to display alphabetically by guest last name instead of sequencing by room number.

- This report includes both Primary and Additional Guests and Primary Guests are in bold. Adults, Children, Revenue, Tax and Total values are only displayed for the Primary Guest

- This report is on the PostgreSQL DB so accounts will not be added by default. Request "Advanced Reports" if access is necessary (will take some time to sync across)

##**House Count Report (HCR)**

- The House Count Report provides a count of both guests and assigned rooms broken down by date and folio status. The guest count is based on the occupancy field in the reservation screen.

- It's basically a daily break out of rooms and guests by folio status.

- Confirm this - multiple properties are shown consecutively.

- This report is on the PostgreSQL DB so accounts will not be added by default. Request "Advanced Reports" if access is necessary (will take some time to sync across)

##**Housekeeping Status Report (HSR)**

- The Housekeeping Status Report displays the status for all activity in every room in the hotel. This report provides details on the Reservations that the Housekeeping department might find useful in scheduling of service.

- Note - Housekeeping Statuses are **not** sent to the Reporting Server yet so this report will only display Reservation Status.

- This report is on the PostgreSQL DB so accounts will not be added by default. Request "Advanced Reports" if access is necessary (will take some time to sync across)
