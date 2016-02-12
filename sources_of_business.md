---
title: Sources of Business
tags: 
  - sources
keywords: "sources, source tags, sources of business rules, sources of business categories, "
last_updated: "November 27th, 2015"
summary: " Sources of Business track the origin of reservations. You can report on these sources to find out where people come to know about your property, or to check the production level for each channel.  "
published: true
---








Each reservation that automatically interfaces with your PMS comes with a _source tag_ that your system will pick up and store: you will need to organize these incoming sources via the set up of automatic rules that the system will follow. Before starting configuring those up, let's explore some system terminology that will come useful during the set up: 
  
  
  
**Source of Business Item**:  this is the _source tag_ that identifies where a reservation comes from. These Sources come with the reservation _file_ that interfaces with the system. Since they are sent from external channels, we have no power of controlling it. For example, Expedia might send as its source the tag _EQC_ or _Expedies_. As these items come from external sources you won't need to create them, but only organize them into _Sources of Business Categories_.
  
  
  
**Source of Business Category**: although we have no control over what Source Items get sent to us, we do provide you with a tool via wich you can rename and order them. By creating Source Categories you will be able to control how the Source Items appear in your reservation folios. For example, if Expedia sends _EQC_, you can re-name it by creating the Category _Expedia_: the latter will show up on both reservation folios and reports.
  
  
**Sources of Business Rules**: they are used to configure Source Items into Categories. They are the rules under which the system operates.  


  ## **Create Your Source Categories** 

 - In the _Admin Settings_ click on the link **Sources of Business** under section _General_:  

![Sources_1.png]({{site.baseurl}}/images/Sources_1.png)




 
 - You will notice three different panels: the first is for the _Source of Business Catgeories_, the second is for the _Source of Business Rules_, and the third is for the _Sources of Business Items_:  
 
![Sources_2.png]({{site.baseurl}}/images/Sources_2.png)



 
  - Click on the blue button _Add Source of Business Category_:  
  
![Sources_3.png]({{site.baseurl}}/images/Sources_3.png)



  
  - Enter the name for your Category, and give it a brief description if you want. Once done, click on the grey button _Save_ on the right hand side of the screen:
  
![Sources_4.png]({{site.baseurl}}/images/Sources_4.png)

  
  - Repeat for all Sources you have.
  
 The Categories will show up in each reservation folios under the scroll down menu _Source_, on the right hand side of each folio:  
 
![Sources_5.png]({{site.baseurl}}/images/Sources_5.png)
 
 
 ##**Create your Source of Business Rules**  
 
 Sources of Business Rules will turn Source Items into Categories. All rules **must be set up upon first receipt of a new reservation source tag/item**. If you are not connected with any channel (including your OBE), you can skip the following instructions.
 Once you start connecting with channels and receive reservations, you will need to define what the system has to do: 
 
  - Click on the blue button _Add Source of Business Rule_:  
  

![Sources_6.png]({{site.baseurl}}/images/Sources_6.png)


  
  - Choose a priority, and select your options form the scroll down menus: in my example below, I am setting up the system so that all reservations coming from Channel _Siteminder_, having the tag _EQC_ will need to merge into Source of Business Category _Expedia_:  
  
![Sources_7.png]({{site.baseurl}}/images/Sources_7.png)




Here is a quick overview of what each channel means:  

 **FRONTDESK** for reservations manually entered on your Tape Chart.  
 **IBE** for those coming from your **I**nternet **B**ooking **E**ngine.  
 **SITEMINDER** for those coming from your channel manager.  
 

Note that when a Source of Business Item comes through the system, it will pick automatically the channel with which it has interfaced.



This means that when setting up your Sources Rules and deciding what channel to choose from the drop down menu, make sure to look at the Source Identifier's channel, as they will **need to be the same**. This is because the rule will need to recognize not only the source tag sent by the channel, but also the channel from which the tag has been sent.
