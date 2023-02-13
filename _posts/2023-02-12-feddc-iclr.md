---
layout: post
title: "FedDC accepted at ICLR"
author: "Jonas Fischer"
categories: journal
tags: [ML, federated, privacy]
image: feddc_overview_2.png
---

Our paper on federated learning with small sample sizes has been accepted to the [International Conference on Learning Representations (ICLR)](https://iclr.cc), one of the prime conferences in Machine Learning!

In this joint work with Michael Kamp and Jilles Vreeken, we show how can learn in a *federated* setting even when only *small amounts of samples* are available per client and privacy is a huge concern, as typically is the case in hospital settings.
We introduce a new communication technique (visualized in the image) which we term federated daisy chaining (FedDC), which mixes traditional communication of model averages through a central server with directly passing on models in a randomized and privacy-preserving way.

In convex settings, we provably show that using appropriate aggregation techniques, our approach can properly learn a good model even on small amounts of data, where current methods fail. On synthetic benchmark and real-world biomedical imaging data, we show that for non-convex methods, such as CNNs, our method greatly outperforms state-of-the-art methods when only small amounts of data are available.

As excited as we are? [Here](https://arxiv.org/pdf/2110.03469.pdf) is a preprint!