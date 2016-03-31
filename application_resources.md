---
title: Application Resources
tags: 
  - application resources
keywords: "guest messages, guest documents"
summary: Learn how to populate your custom message document with information regarding a folio.
published: true
---


#Using Frontdesk Anywhere system variables to help use live data in your documents.


#Guest Messages Variables


##Hotel Information

| Hotel Information Variables                                               |  Information                       |
|---------------------------------------------------------------------------|:-----------------------------------|
| ``` {fda module="hotel"}email{/fda}  ```                                  | Hotel E-Mail                       |
| ``` {fda module="hotel"}phone{/fda}  ```                                  | Hotel Phone                        |
| ``` {fda module="hotel"}fax{/fda}  ```                                    | Hotel Fax                          |
| ``` {fda module="logo"}url{/fda}  ```                                     | Hotel Logo Url                     |
| ``` {fda module="hotel"}web_url{/fda}  ```                                | Hotel Web Url                      | ## not yet implemented on backend
| ``` {fda module="hotel"}hotel_address{/fda}  ```                          | Hotel Address                      | ## not yet implemented on backend
| ``` {fda module="hotel"}hotel_name{/fda}  ```                             | Hotel Name                         | ## not yet implemented on backend

##Guest Information

| Guest Information Variables                                               |  Information                       |
|---------------------------------------------------------------------------|:-----------------------------------|
| ``` {fda module="guest"}loyalty_id{/fda}  ```                             | Loyalty ID                         |
| ``` {fda module="guest"}full_name{/fda}  ```                              | Full Name                          |
| ``` {fda module="guest"}first_name{/fda} ```                              | First Name                         |
| ``` {fda module="guest"}last_name{/fda}  ```                              | Last Name                          |
| ``` {fda module="guest"}id_type{/fda}  ```                                | Guest Identification Type          |
|                                                                           |                                    |


## Inventory Information

| Inventory Information Variables                                              | Information                  |
| -----------------------------------------------------------------------------|:-----------------------------|
| ``` {fda module="inventory"}total{/fda}        ```                           | Inventory Total              |
| ``` {fda module="inventory"}date_rate_change{/fda} ```                       | Date Rate Change List        |
| ``` {fda module="inventory"}rate_average{/fda} ```                           | Rate Average                 |
| ``` {fda module="inventory"}num_rooms_total{/fda} ```                        | Number of Rooms (total)      | ## not yet implemented on backend
| ``` {fda module="inventory"}num_guests_total{/fda} ```                       | Number of Guests (total)     | ## not yet implemented on backend
| ``` {fda module="inventory"}pos_item{/fda} ```                               | Point of Sale Items (single) | ## not yet implemented on backend
| ``` {fda module="inventory"}pos_item_total{/fda} ```                         | Point of Sale Items (total)  | ## not yet implemented on backend
 


## Folio Information

| Folio Information Variables                                                  | Information             |
| -----------------------------------------------------------------------------|:------------------------|
| ```` {fda module="folio"}reservation_folio{/fda}  ````                       | Reservation Folio       |
| ```` {fda module="folio"}reserved_by{/fda}        ````                       | Reserved By             |
| ```` {fda module="folio"}checkin_by{/fda}         ````                       | Check In By             |
| ```` {fda module="folio"}reservation_date{/fda}   ````                       | Reservation Date        |
| ```` {fda module="folio"}number_adults{/fda}      ````                       | Number Of Adults        |
| ```` {fda module="folio"}number_children{/fda}    ````                       | Number Of Children      |
| ```` {fda module="folio"}room_no{/fda}            ````                       | Room Number             |
| ```` {fda module="folio"}comments{/fda}           ````                       | Folio Comments          |
| ```` {fda module="folio"}room_rate{/fda}           ````                      | Room Rate/Price         | ## not yet implemented on backend
| ```` {fda module="folio"}room_type{/fda}           ````                      | Room Type               | ## not yet implemented on backend
| ```` {fda module="folio"}confirmation_fda{/fda}           ````               | FDA Confirmation Number | ## not yet implemented on backend
| ```` {fda module="folio"}confirmation_ota{/fda}           ````               | OTA Confirmation Number | ## not yet implemented on backend
| ```` {fda module="folio"}tax{/fda}           ````                            | Tax                     | ## not yet implemented on backend
| ```` {fda module="folio"}deposit_payed{/fda}           ````                  | Deposit Payed 			 | ## not yet implemented on backend
| ```` {fda module="folio"}balance{/fda}           ````                        | Balance                 | ## not yet implemented on backend
|                                                                              |                         |

## Group Folio Information

| Group Folio Information Variables                                            | Information                   |
| -----------------------------------------------------------------------------|:------------------------------|
| ```` {fda module="group_folio"}number_adults{/fda}      ````                 | Number Of Adults In Group     |
| ```` {fda module="group_folio"}number_children{/fda}    ````                 | Number Of Children In Group   |
| ```` {fda module="group_folio"}group_name{/fda}    ````                      | Group Name                    | ## not yet implemented on backend
| ```` {fda module="group_folio"}group_folio_number{/fda}    ````              | Folio Number                  | ## not yet implemented on backend
| ```` {fda module="group_folio"}group_guest_total{/fda}    ````               | Total Amount Guests           | ## not yet implemented on backend
| ```` {fda module="group_folio"}group_checkin{/fda}    ````                   | Check In Date                 | ## not yet implemented on backend
| ```` {fda module="group_folio"}group_checkout{/fda}    ````                  | Check Out Date                | ## not yet implemented on backend
| ```` {fda module="group_folio"}group_room_type{/fda}    ````                 | Room Type                     | ## not yet implemented on backend
| ```` {fda module="group_folio"}group_room_amount{/fda}    ````               | Quantity of Room Type         | ## not yet implemented on backend
| ```` {fda module="group_folio"}group_folio_number{/fda}    ````              | Folio Number                  | ## not yet implemented on backend
| ```` {fda module="group_folio"}group_rate{/fda}    ````                      | Rate                          | ## not yet implemented on backend
| ```` {fda module="group_folio"}group_total_room_charge{/fda}    ````         | Room Charge (total)           | ## not yet implemented on backend
| ```` {fda module="group_folio"}group_pos_total{/fda}    ````                 | POS (total)                   | ## not yet implemented on backend
| ```` {fda module="group_folio"}group_tax{/fda}    ````                       | Group Tax                     | ## not yet implemented on backend
| ```` {fda module="group_folio"}group_deposit{/fda}    ````                   | Group Deposit                 | ## not yet implemented on backend
| ```` {fda module="group_folio"}group_balance{/fda}    ````                   | Group Balance                 | ## not yet implemented on backend


## Arraival/Departure

| Arraival Departure Detail Variables                                          | Information        |
|------------------------------------------------------------------------------|:-------------------|
| ```  {fda module="arrdep"}checkin{/fda}   ```                                | Check In           |
| ```  {fda module="arrdep"}checkout{/fda}  ```                                | Check Out          |
| ```  {fda module="arrdep"}no_nights{/fda} ```                                | Number Of Nights   |
|                                                                              |                    |


##  Booking Object Variables
Any variable from the booking object should be accesible from the format below

| Booking Obj                                                                  | Information        |
|------------------------------------------------------------------------------|:-------------------|
| ```  {fda module="bookingObj" type="entry"}checkout_time{/fda}   ```         | checkout_time      |


#Variable Modifiers

| Modifier                 | Information                                                                                                                             |
|--------------------------|:----------------------------------------------------------------------------------------------------------------------------------------|
|   format="date"          |   Works for any variable that ouputs dates in the iso format  ```  {fda module="arrdep" format="date"}checkin{/fda}   ```               |

#System Variables

| System Variable                                                              | Information        |
|------------------------------------------------------------------------------|:-------------------|
| ```  {fda module="system"}current_time{/fda}   ```                           | Current Time       |
| ```  {fda module="system"}current_date{/fda}   ```                           | Current Date       |
