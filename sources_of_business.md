
#**Sources of Business**  

Sources of Business track the origin of reservations. You can report on these in order to find out where people come to know about your property, or to check information about production for each channel.  
Each reservation that automatically arrives to your PMS comes with a _source tag_ that your system will pick up and store: you will need to organize these incoming sources via the set up of automatic rules that the system will follow. Before starting configuring those up, let's explore some system terminology that will come useful during the set up: 

**Source of Business Item**: this is the _source tag_ that identifies where a reservation comes from. These can be _Expedia_, _Booking.com_, etc. It is sent with each reservation file by the channels and for this reason we have no control over it.

**Source of Business Category**: categories are used to personalize all Sources names for reservations interfacing with your system. As mentioned above, we have no control over the Source Item sent to us, but we do provide you with a way to control what shows as the Source in your reservations. Categories are basically the name you want to give to your sources: for example, if a reservation comes through with source _EQC_, you will be able to re-categorize it, or re-name it, _Expedia_. 

**Sources of Business Rules**: they are used to configure Source Items into Categories. They are the rules under which the system will operate, and for this reason you will have to define them.

 - In the _Admin Settings_ click on the link **Sources of Business** under section _General_:  
 
 ![](1.png]({{site.baseurl}}/images/1.png)  
 
 - You will notice three different panels: the first is for the _Source of Business Catgeories_, the second is for the _Source of Business Rules_, and the third is for the _Sources of Business Items_:  
 
 ![](2.png]({{site.baseurl}}/images/2.png)  
 
 ###1. **Create your Source Items** 
 
  - 
  
  
  Start by entering all Source Items for reservations that you will have to manually insert in the system. **Do not** enter sources for those reservations that will automatically flow into your accounts, as the Source Item for those ones will be automatically created upon reservation receipt.
  
 Click on the blue link _Add Source of Business Item_:  
  
  ![](3.png]({{site.baseurl}}/images/3.png)  
  
 - Select the channel via which reservations come to interface with your PMS. As mentioned before, you will only need to create sources for those manually inserted reservations, as all others will pick up their channel automatically, so choose the option **Frontdesk**: 
 
 ![](4.png]({{site.baseurl}}/images/4.png)  
 
In case you need it, here is a breakdown of the meaning of the all channels listed:
 
 **FRONTDESK** for reservations manually entered on your Tape Chart.
 **OBOE** for those coming from your **O**nline **BO**oking **E**ngine.  
 **INNLINK** for those reservation coming from Innlink.  
 **FDX2** for those coming from your channel manager.
 **BDC** for those reservations coming via the Booking.com direct connection.
 **EXPEDIA** for those coming via the Expedia direct connection.  
 
 - Under _Identifier_, place the name of the Source of Business Item and click on the grey button _Save_ on the right hand side:  
 
 ![](5.png]({{site.baseurl}}/images/5.png)  
 
 - In case you need to edit the SOurce of Business Item you have just created, click on the button _Edit_ on the right hand side of the item:  
 
 ![](6.png]({{site.baseurl}}/images/6.png)  
 
 ###2. **Create you Source Categories**  
 
  - Click on the blue button _Ad Source of Business Category_:  
  
  ![](7.png]({{site.baseurl}}/images/7.png)  
  
  - Enter the name for the Category and a brief description; when done, click on the grey button _Save_ on the right hand side:  
  
  ![](8.png]({{site.baseurl}}/images/8.png)

 - To edit a Source Category, click on the grey button _Edit_ on the right hand side of the newly created category:  
 
 ![](9.png]({{site.baseurl}}/images/9.png)  
 
 ###3. **Create your Source of Business Rules**  
 
  - Click on the blue button _Add Source of Business Rule_:  
  
  ![](10.png]({{site.baseurl}}/images/10.png)  
  
  - This is where you configure the rules that the sytem will follow. Choose a priority, and select your options form the scroll down menus. You will need to choose those options according to what you want the system to do; in my example below, I am selecting that all reservations made via the channel **Frontdesk** (Tape Chart), marked with the source **Phone Call** will end up in the **Direct** category:  
  
  ![](11.png]({{site.baseurl}}/images/11.png)  
  
  
**NOTE**: Upon _first_ receipt of any reservations coming from any channel other than Frontdesk, you will need to log back into the _Sources of Business_ as that will create a new _Source Item_: you will then need to define the rule controlling that Item!
