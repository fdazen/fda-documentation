---
title: Sources of Business
tags: 
  - formatting
keywords: "rates, taxes, add-ons, master rates, derived rates, duplicate rates, daily rate grid, season periods"
last_updated: "November 17th, 2015"
summary: "Sources of Business help you track the origin of your reservations. Learn how to set them up in your account before starting to receive reservations in your system!"
published: true
---





#**Sources of Business**    


Sources of Business track the origin of reservations. You can report on these sources to find out where people come to know about your property, or to check the production level for each channel.  
Each reservation that automatically interfaces with your PMS comes with a _source tag_ that your system will pick up and store: you will need to organize these incoming sources via the set up of automatic rules that the system will follow. Before starting configuring those up, let's explore some system terminology that will come useful during the set up: 
  
  
  
**Source of Business Item**: this is the _source tag_ that identifies where a reservation comes from. These Sources come with the reservation _file_ that interfaces with the system. Since they are sent from external channels, we have no power of controlling it. For example, Expedia might send as its source the tag _EQC_ or _Expedies_. As these items come from external sources you won't need to create them, but only organize them into _Sources of Business Categories_.
  
  
  
**Source of Business Category**: although we have no control over what Source Items get sent to us, we do provide you with a tool to re-name them. By creating Source Categories you will be able to control how the Items are named. For example, if Expedia sends _EQC_, you can re-name it by creating the Category _Expedia_. The latter will show up in any reservation folios and also in reports.
  
  
**Sources of Business Rules**: they are used to configure Source Items into Categories. They are the rules under which the system will operate.  


 ##1. **Create your Source Categories** 

 - In the _Admin Settings_ click on the link **Sources of Business** under section _General_:  

![1d.png]({{site.baseurl}}/images/1d.png)



 
 - You will notice three different panels: the first is for the _Source of Business Catgeories_, the second is for the _Source of Business Rules_, and the third is for the _Sources of Business Items_:  
 
![2d.png]({{site.baseurl}}/images/2d.png)


 
  - Click on the blue button _Add Source of Business Category_:  
  
![7d.png]({{site.baseurl}}/images/7d.png)


  
  - Enter the name for your Category, and give it a brief description if you want. Once done, click on the grey button _Save_ on the right hand side of the screen:
  
  ![201.png]({{site.baseurl}}/images/201.png)  
  
  - Repeat for all Sources you have.
  
 The Categories will show up in each reservation folios under the scroll down menu _Source_, on the right hand side of each folio:  
 
 ![202.png]({{site.baseurl}}/images/202.png)
 
 
 ##2. **Create your Source of Business Rules**  
 
 Sources of Business Rules will turn Identifiers into Categories. All rules **must be set up upon first receipt of a new reservation source tag**. If you are not connected with any channel (including OBE), you can skip the following instructions.
 Once you start connecting with channels and receive reservations, you will need to define what the system has to do: 
 
  - Click on the blue button _Add Source of Business Rule_:  
  
![10d.png]({{site.baseurl}}/images/10d.png)


  
  - Choose a priority, and select your options form the scroll down menus: in my example below, I am setting up the system so that all reservations coming from Channel _FDX2_, having the tag _EQC_ will need to merge into Source of Business Category _Expedia_:  
  
  ![203.png]({{site.baseurl}}/images/203.png)


Here is a quick overview of what each channel means:  

 **FRONTDESK** for reservations manually entered on your Tape Chart.  
 **OBOE** for those coming from your **O**nline **BO**oking **E**ngine.  
 **INNLINK** for those reservation coming from Innlink.  
 **FDX2** for those coming from your channel manager.  
 **BDC** for those reservations coming via the Booking.com direct connection.  
 **EXPEDIA** for those coming via the Expedia direct connection.  

Note that when a Source of Business Item comes through the system, it will pick automatically the channel with which it has interfaced:  

![204.png]({{site.baseurl}}/images/204.png)


This means that when setting up your Sources Rules and deciding what channel to choose from the drop down menu, make sure to look at the Source Identifier's channel, as they will **need to be the same**. This is because the rule will need to recognize not only the source tag sent by the channel, but also the channel from which the tag has been sent.
