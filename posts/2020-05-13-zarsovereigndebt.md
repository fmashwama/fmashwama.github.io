---
layout:     post
title:      ZAR sovereign debt and corporate liabilities, technical supplement
date:       2019-05-13 12:00:01
summary:    In the financial mail I argued evidence from swap markets suggests currency mismatches between revenues and liabilities in South Africa's corporate sector are responsible for some of RSA's sovereign debt woes.
categories: 
---

Full [article here](https://www.fm.co.za/) - available ungated.

In this week's copy of the financial mail I argued the corporate sector in South Africa has some responsibility for the ongoing debt concerns on the sovereign side. Specifically, I suggested we have defeasible evidence that currency mismatches between corporate revenues and liabilities increase sovereign borrowing costs, and that the associated threat of contagion in episodes of capital retrenchments (like this one) is a serious cause for concern. I went further and speculatively suggested that capital controls might be justified as a macroprudential regulatory tool in light of this pattern of facts.

The [article](https://www.fm.co.za/) is available ungated so I won't rehash the argument here. 

Instead I'll merely show the evidence I relied on, share instructions on how to replicate it and offer some supplemental speculative thoughts. 

Here's the picture:

![zar5yspreads](/assets/ZAR_5Y_spreads_CDS_vWebsite.jpg){:class="img-responsive"}

Replicating [Du & Schreger (2016)](https://onlinelibrary.wiley.com/doi/abs/10.1111/jofi.12389) I isolate the market implied outright default risk on ZAR 5Y zero coupon government bonds -- the "(1) local currency default risk" -- assuming risk neutrality. To do this we swap the US yield curve into ZAR using fixed-for-fixed cross currency swaps and then subtract that riskless benchmark from the actual ZAR yield curve. Taking the nominal ZAR - USD spread and subtracting (1) gives the implied forward premium or "(2) currency risk". The credit default swap yield series is in red.

The picture shows South Africa pays an anomalously low local currency spread. It's quite a remarkable picture to be honest. It suggests a near zero market implied outright default risk on ZAR denominated South African sovereign debt. That's a bit difficult to square with the CDS spread in the same picture. 

This is the core evidence I looked at in the financial mail.

**Replication:** You can replicate this picture by downloading the following series from a bloomberg terminal: 

* ussw5curncy 
* c2625yindex 
* sasw5curncy 
* sabs5curncy 
* repsoucdsusdsr5yd 
* and getting the 5Y zero coupon US yield curve [here](https://www.federalreserve.gov/data/nominal-yield-curve.htm).

So what to make of this? 

To be honest I'm not totally sure. I have many questions. How bad are the potential contagion spillovers from mismatched corporates in this case specifically? (We don't have really well identified evidence from past retrenchment episodes from corporates to the sovereign side since the Asian 1990's crisis worked slightly differently.) Can you successfully run this sort of marcoprudential regulatory program as a solo-country in this setting or do you need multilateral coordination? (To be sure, India has something like this.) And, somewhat unrelated, does South Africa enjoy some dollar-esque exorbitant privilege as the core of the rand area?

I'm going to think about this a bit going forward. Thanks for checking this post out!
