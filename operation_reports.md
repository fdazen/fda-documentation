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
  
  
 

##**Arrivals: Detailed Report (ARR)**
     
     
  
The _Arrivals Detailed Report_ displays all reservations that meet all criteria you choose, for the a certain date range. One of the main benefits of this report is that it allows you to have consolidated information for those reservations appearing in the report's results, for example your guest's first and last name, the folio number and the group folio number, in case the reservation is part of a group; it also shows reservation and payment details.   

  
- Click on the link _Arrivals Detailed Report_, in the Reports' List:    

 
![Operational_reports_1.png]({{site.baseurl}}/images/Operational_reports_1.png)  

 
  
- Choose your filters and click on the blue button _Run Report_:    


![Operational_reports_2.png]({{site.baseurl}}/images/Operational_reports_2.png)

   

The report will offer you a daily breakdown of all reservations.    
    
![Operational_reports_3.png]({{site.baseurl}}/images/Operational_reports_3.png)
    





###**Field Legend**  




**Name**: Guest name and last name.  
**Source/Market**: it shows the Source Category and the Market associated with the reservation listed.  
**Group Folio Number/Reservation Number**: Reservation and Group Reservation folio number.   
**Room Type/Room Number**: Room type and room number where reservation resides.  
**Check-in/Check-out Date**: Reservation arrival and departure date.  
**Adults/Children**: Number of adults and children as they appear in the reservation folio.   
**Folio Status**: It displays the status of the reservation.  
**Total Rent/Pay mth**: It shows the total lodging charges and the payment method used (if a deposit has been applied).  
**Deposit**: It shows the amount of deposit paid by the guest.  
**Balance**: It shows the remaining, actual balance for the guest.  





You may export the report in many different formats: choose the right one by selecting it in the scroll down menu with the tag _Download Report As_:    

   
![Operational_reports_4.png]({{site.baseurl}}/images/Operational_reports_4.png)
   

   


##**Departures Report (DEP)**   



The _Departures Report_ lists all of the reservation due to check-out for a particular date. It can be sorted alphabetically or by room number. This report will come useful to understand the volume of departures for a selected date or date range.   







##**Detailed Availability (DA)**

The _Detailed Availability Report_ shows information about availability based on room types. You can choose to display results according to Occupancy or Vacancy, thus making it easy to foresee when demand is increasing/decreasing.
   
   

##**Guest List (GL)**
- Lists the guests who Arrived, Departed and/or were a Stayover for a specified date range.

- It's basically the guest contact report from v2 (includes emails etc) but lets you filter for Arrivals/Departures/Stayovers. You can run for multiple stay statuses at once so for the minute this report (with all Arrivals, Departures and Stayovers selected) and the Manager's Report should replace the Night Audit Report in v2.

- If Additional Guests are selected then the Primary Guest is displayed in bold text.


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
