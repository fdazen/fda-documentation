# Guest Messages Modules

## Index

* [Custom Html Module](http://localhost:8092/FDA/usere/webservices/api/doc?src=guest_messaging&partial=CustomHtml.md)
* [Inventory Balance Breakdown](http://localhost:8092/FDA/usere/webservices/api/doc?src=guest_messaging&partial=InventoryBalanceBreakdown.md)
* [Group Inventory List](http://localhost:8092/FDA/usere/webservices/api/doc?src=guest_messaging&partial=GroupInventoryList.md)
* [Home](http://localhost:8092/FDA/usere/webservices/api/doc)

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
|                                                                              |                         |

## Group Folio Information

| Group Folio Information Variables                                            | Information                   |
| -----------------------------------------------------------------------------|:------------------------------|
| ```` {fda module="group_folio"}number_adults{/fda}      ````                 | Number Of Adults In Group     |
| ```` {fda module="group_folio"}number_children{/fda}    ````                 | Number Of Children In Group   |


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

# Group Inventory List

```xml
    <column position="12" module="group_inventory_list">
        <settings>
        <!--presentaionLayout: detailed_invoice, simplified -->
        </settings>
    </column>

```

* [Available Modules](http://localhost:8092/FDA/usere/webservices/api/doc?src=guest_messaging&partial=Modules.md)
* [Home](http://localhost:8092/FDA/usere/webservices/api/doc)


# Inventory Balance Breakdown

```xml
    <row position="4">
        <column position="6" module="empty_m"></column>
        <column position="6" module="inventory_balance_breakdown">
            <settings>
                <displayLabel>false</displayLabel>
                <displayAdjustments>false</displayAdjustments>
                <displayRoomCharges>true</displayRoomCharges>
                <displayPosAddOnTotals>true</displayPosAddOnTotals>
                <displaySentReceivedTotals>true</displaySentReceivedTotals>
                <displayPayments>true</displayPayments>
                <displayRemainingBalance>true</displayRemainingBalance>
                <displayTaxes>true</displayTaxes>
                <displayCustomTaxes>
                    <taxGroup label="Random Tax Label">
                        <tax title="Tax1"/>
                        <tax title="Tax2"/>
                    </taxGroup>
                </displayCustomTaxes>
                <displayTaxSum>true</displayTaxSum>
                <displayBookingTotalBalance>true</displayBookingTotalBalance>
            </settings>
        </column>
    </row>
```

* [Available Modules](http://localhost:8092/FDA/usere/webservices/api/doc?src=guest_messaging&partial=Modules.md)
* [Home](http://localhost:8092/FDA/usere/webservices/api/doc)

# Custom Html

```xml
    <row position="4">
        <column position="6" module="custom_html" variant="customReservationDetailsMessage">
            <settings>
                <html>
                    <![CDATA[
                    <div class="reg-table-div" style="margin: auto;">
                        <p>Reservation Details</p>
                        <div style="margin: auto; position: relative;">
                            <table class="table-reg-card">
                                <tr>
                                    <td>Check-In:</td>
                                    <td>{fda module="arrdep" format="date"}checkin{/fda}</td>
                                   <!--  <td> </td> -->
                                    <td> </td>
                                    <td> </td>
                                </tr>
                                <tr>
                                    <td>Check-Out:</td>
                                    <td>{fda module="arrdep" format="date"}checkout{/fda}</td>
                                   <!--  <td> </td> -->
                                    <td> </td>
                                    <td> </td>
                                </tr>
                                <tr>
                                    <td>Dep Flight:</td>
                                    <td>{fda module="bookingObj" type="entry"}dep_flight{/fda}</td>
                                    <!-- <td> </td> -->
                                    <td>C/O Time</td>
                                    <td>{fda module="bookingObj" type="entry"}checkout_time{/fda}</td>
                                </tr>
                                <tr>
                                    <td>Room No.</td>
                                    <td>{fda module="folio"}room_no{/fda}</td>
                                   <!--  <td> </td> -->
                                    <td> </td>
                                    <td> </td>
                                </tr>
                                <tr>
                                    <td>Adults:</td>
                                    <td>{fda module="folio"}number_adults{/fda}</td>
                                    <!-- <td> </td> -->
                                    <td>Children</td>
                                    <td>{fda module="folio"}number_children{/fda}</td>
                                </tr>
                            </table>
                        </div>
                    </div>
                    ]]>
                </html>
                <isReadOnly>true</isReadOnly>
            </settings>
        </column>
         <column position="6" module="custom_html" variant="customGuestProfilieMessage">
            <settings>
                <html>
                    <![CDATA[
                    <div class="reg-table-div" style="margin: auto;">
                        <p>Guest Profile Info</p>
                         <div style="margin: auto; position: relative;">
                            <table class="table-reg-card">
                                <tr>
                                    <td>Salutation</td>
                                    <td><span><input type="checkbox" readonly/></span>Mr</td>
                                    <td><span><input type="checkbox" readonly/></span>Mrs</td>
                                    <td><span><input type="checkbox" readonly/></span>Ms</td>
                                    <td><span><input type="checkbox" readonly/></span>Khun</td>
                                </tr>
                                <tr>
                                    <td>First Name:</td>
                                    <td>{fda module="guest"}first_name{/fda}</td>
                                    <td> </td>
                                    <td> </td>
                                    <td> </td>
                                </tr>
                                <tr>
                                    <td>Last Name:</td>
                                    <td>{fda module="guest"}last_name{/fda}</td>
                                    <td> </td>
                                    <td> </td>
                                    <td> </td>
                                </tr>
                                <tr>
                                    <td>Nationality</td>
                                    <td>{fda module="guest" type="profile"}nationality{/fda}</td>
                                    <td> </td>
                                    <td>Birthday</td>
                                    <td>{fda module="guest" type="profile" format="date"}date_of_birth{/fda}</td>
                                </tr>
                                <tr>
                                    <td>ID Type:</td>
                                    <td>{fda module="guest"}id_type{/fda}</td>
                                    <td> </td>
                                    <td>ID No.</td>
                                    <td>{fda module="guest" type="profile"}identification_id{/fda}</td>
                                </tr>
                            </table>
                        </div>
                    </div>
                    ]]>
                </html>
                <isReadOnly>true</isReadOnly>
            </settings>
        </column>
    </row>
```
will render:

```html
    <div class="msg-row">
    <div class="col-xs-6">
        <div class="reg-table-div" style="margin: auto;">
            <p>Reservation Details</p>
            <div style="margin: auto; position: relative;">
                <table class="table-reg-card">
                    <tbody>
                        <tr>
                            <td>Check-In:</td>
                            <td>08-17-2015</td>
                            <!--  <td>&nbsp;</td> -->
                            <td>&nbsp;</td>
                            <td>&nbsp;</td>
                        </tr>
                        <tr>
                            <td>Check-Out:</td>
                            <td>08-31-2015</td>
                            <!--  <td>&nbsp;</td> -->
                            <td>&nbsp;</td>
                            <td>&nbsp;</td>
                        </tr>
                        <tr>
                            <td>Dep Flight:</td>
                            <td><span class="hidden-print">{Unkown tag: [bookingObj:dep_flight]}</span></td>
                            <!-- <td>&nbsp;</td> -->
                            <td>C/O Time</td>
                            <td><span class="hidden-print">{Unkown tag: [bookingObj:checkout_time]}</span></td>
                        </tr>
                        <tr>
                            <td>Room No.</td>
                            <td>51</td>
                            <!--  <td>&nbsp;</td> -->
                            <td>&nbsp;</td>
                            <td>&nbsp;</td>
                        </tr>
                        <tr>
                            <td>Adults:</td>
                            <td>2</td>
                            <!-- <td>&nbsp;</td> -->
                            <td>Children</td>
                            <td>0</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>
    </div>
    <div class="col-xs-6">
    <div class="reg-table-div" style="margin: auto;">
        <p>Guest Profile Info</p>
        <div style="margin: auto; position: relative;">
            <table class="table-reg-card">
                <tbody>
                    <tr>
                        <td>Salutation</td>
                        <td><span><input type="checkbox" readonly=""></span>Mr</td>
                        <td><span><input type="checkbox" readonly=""></span>Mrs</td>
                        <td><span><input type="checkbox" readonly=""></span>Ms</td>
                        <td><span><input type="checkbox" readonly=""></span>Khun</td>
                    </tr>
                    <tr>
                        <td>First Name:</td>
                        <td></td>
                        <td>&nbsp;</td>
                        <td>&nbsp;</td>
                        <td>&nbsp;</td>
                    </tr>
                    <tr>
                        <td>Last Name:</td>
                        <td>Group Rez</td>
                        <td>&nbsp;</td>
                        <td>&nbsp;</td>
                        <td>&nbsp;</td>
                    </tr>
                    <tr>
                        <td>Nationality</td>
                        <td><span class="hidden-print">{Unkown tag: [guest:nationality]}</span></td>
                        <td>&nbsp;</td>
                        <td>Birthday</td>
                        <td>08-26-2015</td>
                    </tr>
                    <tr>
                        <td>ID Type:</td>
                        <td></td>
                        <td>&nbsp;</td>
                        <td>ID No.</td>
                        <td></td>
                    </tr>
                </tbody>
            </table>
        </div>
    </div>
```

## 

* [More Information On Variables](http://localhost:8092/FDA/usere/webservices/api/doc?src=guest_messaging&partial=Variables.md)
* [Available Modules](http://localhost:8092/FDA/usere/webservices/api/doc?src=guest_messaging&partial=Modules.md)
* [Home](http://localhost:8092/FDA/usere/webservices/api/doc)

