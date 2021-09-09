---
title: Create Journeys - Challenge
description: Understand the basics of building a journey in the journey canvas.
kt: 8109
thumbnail: .jpg
feature: Journeys
team: PM
role: User, Administrator
level: Beginner
---

# Create Journeys - Challenge

Luma, a fictional athletic apparel company, is looking to promote its latest apparel and gear collection and to drive sales for existing customers. Your challenge is to create journeys to implement the following use cases: 

* Promote the new Luma summer collection: Send a summer collection announcement to a segment of existing customers email 
* Send an order confirmation email when someone completes an online purchase 
* Send an email when a loyalty customer moves to a new tier to congratulate and inform them of their new benefits 
* When a previously out-of-stock item is back in stock, notify customers who had favorited the out-of-stock item with a call to start shopping now that the item is back in stock 

## Have everything you need? 

### System requirements

Access to a Journey Optimizer Journey instance. Make sure you have either Journey Manager or Journey Administrator rights. 

### Hands-on environment
 
It is recommended to complete the challenge in a development sandbox. This allows you to isolate the excercises from your organization's production environments. To set up a dedicated training sandbox follow the [Set up a training sandbox tutorial](/help/challenges/set-up-training-sandbox.md) 

### Skills you might need 

Complete the course Getting started with Journey Optimizer for Journey Managers and Administrators.
 
### REQUIRED ACTIONS 

Required system or project files to download? 

Any other requirements needed before beginning the Challenge? 

## Let’s jump in! 

### The Back story

With Adobe Journey Optimizer, you can manage scheduled omnichannel campaigns and one-to-one moments for millions of customers from a single application — and the entire journey is optimized with intelligent decisioning and insights. 

YOUR CHALLENGE 

### Setup work 

Create a test profile for yourself.

>[!NOTE]
> Watch the [Test a journey](/help/create-journeys/test-a-journey.md) video to learn how to create a test profile.


### Journey #1 – Summer collection announcement 

1. Send “Luma – New Seasonal Collection Announcement” email to the Active Customer segment, holding out 10% of the audience as a control group.

2. If a recipient does not open “Luma – New Seasonal Collection Announcement” with 2 days, send a follow-on email message with more targeted content: 
   * Male customers should receive the “Luma Collection Men’s” email
   * Female customers should receive the “Luma Collection Women’s” email 
   * Other customers should receive the “Luma – 20% off collection” email 

3. After sending the targeted emails above, wait an hour, then listen for the email to be opened 

4. If the targeted email is not opened within 2 days, send the “Luma – 20% off sales” email as a final retargeting attempt 

5. Once completed, put the journey in test mode and trigger the journey to send to yourself 

 

### Journey #2 – Order confirmation transactional email 

1. Create a journey that is triggered when a customer completes a web purchase on the Luma site to send the “Luma – Website – Order confirmation” email 

2. Map contextual information from the purchase event to personalize the email 

3. Once completed, put the journey in test mode and trigger the journey to send to yourself 

 

### Journey #3 – Diamond status upgrade welcome email 

1. Create a journey triggered when a customer moves into a new loyalty tier (specifically when the customer enters the segment defined for a new Diamond level members) to send the “Luma – New Status – Diamond – Transactional” email 

2. Once completed, put the journey in test mode and trigger the journey to send to yourself 

 

### Journey #4 – Product restock email 

Create a journey triggered when Product ABC123 is back in stock, to send the “Luma Email Product Replenishment” to notify users who had favorited the product while it was out of stock with a call-to-action to start shopping 

Map contextual information from the product restock event to personalize the email 

Once completed, put the journey in test mode and trigger the journey to send to yourself 

>[!NOTE]
> Check your work [here](/help/challenges/check-your-work.md).



