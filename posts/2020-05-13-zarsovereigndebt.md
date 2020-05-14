---
layout:     post
title:      ZAR sovereign debt and corporate liabilities, technical supplement
date:       2019-05-13 12:00:01
summary:    In the [financial mail](https://www.fm.co.za/) I argued evidence from swap markets suggests currency mismatches between revenues and liabilities in South Africa's corporate sector are responsible for some of RSA's sovereign debt woes. Replicating [Du & Schreger (2016)](https://onlinelibrary.wiley.com/doi/abs/10.1111/jofi.12389) I examine the local currency spread South Africa pays for sovereign borrowing and share a perspective on what the evidence suggests.
categories: 
---

Full [article here](https://www.fm.co.za/) - available ungated.

In this week's copy of the financial mail I argued the currency composition of corporate liabilities in South Africa justify revisiting the debate on free capital flows. Specifically, I suggested the use of capital controls might be justified as a macroprudential regulatory tool in light of currency mismatches in the corporate sector that impose social costs that are easily missed -- increased sovereign borrowing costs and potential contagion in times of capital retrenchments (like now).

The [article](https://www.fm.co.za/) is available ungated so I won't rehash the argument here. 

Instead I'll merely show the evidence I relied on, share instructions on how to replicate it and offer some supplemental speculative thoughts. Below is the image.

![zar5yspreads](/assets/ZAR_5Y_spreads_CDS_vWebsite.jpg){:class="img-responsive"}

Replicating [Du & Schreger (2016)](https://onlinelibrary.wiley.com/doi/abs/10.1111/jofi.12389) I isolate the market implied outright default risk on ZAR 5Y zero coupon government bonds -- the "(1) local currency" risk -- under the risk-neutral measure. To do this we swap the US yield curve into ZAR using fixed-for-fixed cross currency swaps and then subtract that riskless benchmark from the actual ZAR yield curve. Taking the nominal ZAR - USD spread and subtracting (1) gives the implied forward premium or "currency risk" (2). The credit default swap yield series is in red.

The picture shows South Africa pays an anomalously low local currency spread. It's remarkable quite candidly. Literally interpreted it suggests a near zero market implied outright default risk. That's really difficult to square with the CDS yield that's non-trivial throughout the series. 

This is the core evidence I looked at in the financial mail.

You can replicate this picture by downloading the following series from a bloomberg terminal: ussw5curncy c2625yindex sasw5curncy sabs5curncy repsoucdsusdsr5yd; and getting the 5Y zero coupon US yield curve [here](https://www.federalreserve.gov/data/nominal-yield-curve.htm).

So what to make of this? 

To be honest I'm not totally sure. I have many questions. How bad are the potential contagion spillovers from mismatched corporates in this case specifically? (We don't have really well identified evidence from past retrenchment episodes from corporates to the sovereign side since the Asian 1990's crisis worked slightly differently.) Can you successfully run this sort of marcoprudential regulatory program as a solo-country in this setting or do you need multilateral coordination? (To be sure, India has something like this.) And, somewhat unrelated, does South Africa enjoy some dollar-esque exorbitant privilege as the core of the rand area?

I'm going to think about this a bit going forward. Thanks for checking this post out!
