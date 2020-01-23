---
layout: post
title:  Blockchain Tycoon Phase 2 - Devlog 2
date:   2020-01-23
image:  
tags:   [Blockchain Tycoon]
---

Hello everyone, It’s been a productive week and development of “Phase 2” is going great so far. As mentioned before, Blockchain Tycoon is being redesigned and most of the systems are being developed again to allow more features that we couldn’t have in the first iteration. The game will be in Early Access until all the systems are balanced. The game is not updated because the “Phase 2” version is not ready to play yet. In the meantime, you can learn about the process by reading the development logs. 

## Pricing System and Exchanges 

* If you look at the cryptocurrency exchange (or trading systems), there are separate values for ask and bid for coins. ‘Ask Price’ is how much a seller accepts for a coin or stock that is being sold. ‘Bid Price’ is how much a buyer is willing to pay for a coin. Coin prices in the game are now determined by a similar system that allows variations in price and we are observing a better simulated price. Supply and demand determines the price increase and decrease in the simulation. While your orders are still executed in a fixed-price basis, coin prices in simulation varies depending on other trades. Next step is to add buying/selling orders to and exchange order-book and simulate the orders. 
* Exchanges are redesigned so that coins can have varying prices when compared with the price in other exchanges. There will also be a simple tool that lets you sort prices by coin in multiple exchanges. 
* Here are example events affecting price (blue line is the exact price)
    
    1. A good example of sudden drop and increase in a coin:
    
    ![]({{site.baseurl}}/images/bct-p2-dl2-fig1.png) 
    
    2. Bad example for increase and decrease of price
    
    ![]({{site.baseurl}}/images/bct-p2-dl2-fig2.png) 
    
    3. Almost stable coin price that has increased in value after some time
    
    ![]({{site.baseurl}}/images/bct-p2-dl2-fig3.png) 
    
    4. An increase in increments and coin doubling its price in a year
    
    ![]({{site.baseurl}}/images/bct-p2-dl2-fig4.png) 
    
    5. Differences between varying increase / decrease events. Some events have more effect on price. 

    ![]({{site.baseurl}}/images/bct-p2-dl2-fig5.png) 


## What’s next? 
* Overclock. Increasing memory and undervolting the GPU to have more hash-rate and decrease the power usage. Traditionally, you should overclock by finding a safe value for the specific GPU and there is a chance of frying your graphics card if you set values too high. Not sure how it should be implemented in game. Maybe we can have selection of cooling in the shelf we are placing the GPUs in and allowing more overclock options if there are enough cooling. If you do not have sufficient cooling, there could be a chance to break the GPU. 

Feel free to share your thoughts and suggestions in comments, discussion forums or by sending an email. 

[Blockchain Tycoon on Steam](http://store.steampowered.com/app/824450/Blockchain_Tycoon/)