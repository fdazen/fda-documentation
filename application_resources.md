---
title: Application Resources
tags:
  - application resources
keywords: "guest messages, guest documents"
summary: Learn how to populate your custom message document with information regarding a folio.
published: true
---




| Hotel Information Variables                                               |  Information                       |
|---------------------------------------------------------------------------|:-----------------------------------|
| ``` {fda module="hotel"}email{/fda}  ```                                  | Hotel E-Mail                       |
| ``` {fda module="hotel"}phone{/fda}  ```                                  | Hotel Phone                        |
| ``` {fda module="logo"}url{/fda}  ```                                     | Hotel Logo Url                     |
| ``` {fda module="hotel"}hotel_address{/fda}  ```                          | Hotel Address (Street)             |
| ``` {fda module="hotel"}city{/fda}  ```                                   | Hotel City                         |
| ``` {fda module="hotel"}state{/fda}  ```                                  | Hotel State                        |
| ``` {fda module="hotel"}country{/fda}  ```                                | Hotel Country                      |
| ``` {fda module="hotel"}zip{/fda}  ```                                    | Hotel Zip                          |
| ``` {fda module="hotel"}hotel_name{/fda}  ```                             | Hotel Name                         |


| Guest Information Variables                                               |  Information                       |
|---------------------------------------------------------------------------|:-----------------------------------|
| ``` {fda module="guest"}full_name{/fda}  ```                              | Full Name                          |
| ``` {fda module="guest"}first_name{/fda} ```                              | First Name                         |
| ``` {fda module="guest"}last_name{/fda}  ```                              | Last Name                          |
| ``` {fda module="guest" type="profile"}id{/fda}  ```                      | Profile ID                         |
|                                                                           |                                    |


| Inventory Information Variables                                              | Information                  |
| -----------------------------------------------------------------------------|:-----------------------------|
| ``` {fda module="inventory"}total{/fda}        ```                           | Inventory Total              |
| ``` {fda module="inventory"}date_rate_change{/fda} ```                       | Date Rate Change List        |
| ``` {fda module="inventory"}rate_average{/fda} ```                           | Rate Average                 |



| Folio Information Variables                                                  | Information             |
| -----------------------------------------------------------------------------|:------------------------|
| ```` {fda module="folio"}reservation_folio{/fda}  ````                       | Reservation Folio Number|
| ```` {fda module="folio"}reservation_date{/fda}   ````                       | Reservation Date        |
| ```` {fda module="folio"}number_adults{/fda}      ````                       | Number Of Adults        |
| ```` {fda module="folio"}number_children{/fda}    ````                       | Number Of Children      |
| ```` {fda module="folio"}room_no{/fda}            ````                       | Room Number             |
| ```` {fda module="folio"}comments{/fda}           ````                       | Folio Comments          |
|                                                                              |                         |


| Arraival Departure Detail Variables                                          | Information        |
|------------------------------------------------------------------------------|:-------------------|
| ```  {fda module="arrdep"}checkin{/fda}   ```                                | Check In           |
| ```  {fda module="arrdep"}checkout{/fda}  ```                                | Check Out          |
|                                                                              |                    |


| System Variable                                                              | Information        |
|------------------------------------------------------------------------------|:-------------------|
| ```  {fda module="system"}current_time{/fda}   ```                           | Current Time       |
| ```  {fda module="system"}current_date{/fda}   ```                           | Current Date       |
