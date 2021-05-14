---
title: Boosting Methods & Deep Learning for Bond Pricing
summary: Graduate Dissertation @ LSE advised by **Professor Peter Kondor**
tags:
- Finance
- Machine Learning
- Deep Learning
date: "2020-03-11T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: ""

links:
# - icon: twitter
 # icon_pack: fab
 # name: Follow
 # url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

In recent years, with the rapid development of both theoretical models and computing capabilities, Machine Learning & Deep Learning techniques have spurred great interest in various research fields, and Finance is of course no exception. However, over the last two decades, the applications of such statistical learning algorithms in financial economics literature have been mostly limited to simple feature engineering techniques like PCA (Principal Component Analysis) or other factor analysis tools, whereas their astonishing predictive capabilities on capturing substantial and complex features (such as non-linear relationships) have been largely underestimated and are still to be further investigated. 

The topic of this dissertation is inspired by a recent paper published on RFS (The Review of Financial Studies) last month (Bianchi, Büchner & Tamoni, 2021), in which the authors have conducted two progressive experiments using Machine/Deep Learning methodologies to model the predictable variation in Treasury bond returns. As a result, they suggested that such methods could provide strong statistical evidence on the predictability of bond returns and more interestingly, they have further pointed out that – (1) Adding in the macroeconomic features could largely ameliorate the performance of the models and (2) Even in the context of low-dimensional dataset, the NNs still perform very well.

The first statement actually conforms with intuition that with a larger information set being provided to the prediction model, it should be able to capture more (probably non-linear) characteristics underneath. Nevertheless, the second claim is somewhat thought-provoking, as one of the main obstacles for heuristic algorithms and particularly Deep Learning Models to be adopted to the Financial Field is the lack of sufficient data for training, where such scarcity of data often results in the underperformance of NNs though they actually have “inherent” advantages of being applied to prediction tasks (Stephen, Xinyue & Jingran, 2021; Xinyue, Zhaoyu & Yue, 2020). And that is also why such methods are quite commonly seen being adopted to equity pricing rather than bond pricing – as bond market does suffer a lot from a severe lack of real-time information.

Therefore, in this essay, we shall test that whether such phenomenon (i.e., consistent well performance of NNs under sparse samples) generally holds for bond markets. Specifically, instead of simply replicating this experiment on returns, we will focus on directly predicting the corporate bond prices, which is a more difficult and comprehensive task on bond pricing. Moreover, we have also noted that both the Machine Learning & Deep Learning Models adopted by Bianchi, Büchner & Tamoni (2021) are actually quite conservative, where the NN Structure they chose (MLP) could actually date back to 1980s, whereas many more powerful techniques have been created in recent years that specifically deal with sequential (time series) data (for instance, Recurrent Neural Networks (RNNs)). Hence, in our dissertation, instead of using classic techniques, we shall adopt several state-of-the-art models like Boosting Methods in Machine Learning (XgBoost & LightGBM) & RNNs (LSTM & GRU) in Deep Learning to see that whether such conclusion is just due to model choice (i.e., the model selected in the RFS Paper could not fully demonstrate the potentiality of ML/DL), or it could still hold (i.e., Deep Learning models could still outperform) even if we have employed the cutting-edge algorithms. Furthermore, if possible, we shall also try to add the macroeconomic data and even sentiment analysis features to our dataset to see how much gain could be brought by providing additional information.

**References**

Bianchi, D., Büchner, M., & Tamoni, A. (2021). Bond risk premiums with machine learning. _The Review of Financial Studies_, 34(2), 1046-1089.

Stephen, C., Xinyue, C., & Jingran, Z. (2021). Boosting over Deep Learning for Earnings. In _AAAI KDF Workshop_.

Xinyue, C., Zhaoyu, X., & Yue, Z. (2020). Using Machine Learning to Forecast Future Earnings. _Atlantic Economic Journal_, 48(4), 543-545.

Ganguli, S., & Dunnmon, J. (2017). Machine learning for better models for predicting bond prices. _arXiv preprint arXiv:1705.01142_.
