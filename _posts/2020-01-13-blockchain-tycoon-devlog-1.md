---
layout: post
title:  Blockchain Tycoon Phase 2 - Devlog 1
date:   2020-01-13
image:  
tags:   [Blockchain Tycoon]
---

Happy new year everyone. We’re starting the 2020 with the dev log to let you know about the current state of the development. Blockchain Tycoon in now in “Phase 2” of its development process. The game is being redesigned according to all the feedback gathered so far. In series of development logs, you’ll read about current and future state of the development process. Since everything is in-code or in design stage at this point, there are no screenshots today.

Updates in Phase 2:
* All coins are different from each other. They use a hashing algorithm. Bitcoin uses “SHA-256” and Ethereum uses “Ethash”.  Algorithm determines how the coin is mined. Multiple coins can use the same hashing algorithm. 
* Each coin has a unique block reward mechanism. The coins we are mining are rewards for the verified blocks. Current reward amount for BTC is 12.5 and 2.00 for ETH. Rewards have pre-determined rules depending on the coin. For example, BTC rewards are halved every 210K blocks. 
* When you use the same hardware for mining a different coin, hashrate will be different. That was something not included in the game due to simplification. It will be included in phase 2. Power usage also change depending on the algorithm. For example, RTX 2080 TI has hashrate of 52.5 Mh/s for Ethash and 2.80 Mh/s for NeoScrypt. 
* ASIC’s are designed to mine a specific algorithm. For example, there are different ASICs for SHA256 and Scrypt and they can’t mine coins that are using different algorithms. This needs to be included too. There are also cases that a new ASIC is introduced to mine a coin that was previously mined with only GPUs.

What systems are already completed?
* Formulas for mining reward calculations using different algorithms. There are 5 algorithms planned right now (multiple coins can be created using the same algorithm). 
* A new mining system which allows GPUs to have hashrate value depending on algorithm. ASICs also only mine for coins using the same algorithm. So, you have to buy a new ASIC model to mine a coin using a different algorithm. 

What is being developed right now?
* Pricing system same as a real exchange (ask, bid values executed in order)
* Multiple exchanges allowing price alternatives
* Task system for the campaign 

The game will be updated as soon as all the systems are redesigned. By estimations, it might take a little over a month for the new version to become playable and balanced. 
Thank you all for the patience and as always feel free to share your suggestions. 

[Blockchain Tycoon on Steam](http://store.steampowered.com/app/824450/Blockchain_Tycoon/)