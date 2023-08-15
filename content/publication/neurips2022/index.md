---
title: 'Quo Vadis: Is Trajectory Forecasting the Key Towards Long-Term Multi-Object Tracking?'

authors:
  - Patrick Dendorfer
  - Vladimir Yugay
  - Aljosa Osep
  - Laura Leal-Taixe


date: '2022-11-28T00:00:00Z'
doi: ''

publication_types: ['1']

publication: NeurIPS 2022 
publication_short: NeurIPS 2022

abstract: Recent developments in monocular multi-object tracking have been very successful in tracking visible objects and bridging short occlusion gaps, mainly    relying on data-driven appearance models. While we have significantly advanced short-term tracking performance, bridging longer occlusion gaps remains elusive :state-ofthe-art object trackers only bridge less than 10% of occlusions longer than three seconds. We suggest that the missing key is reasoning about future trajectories over a longer time horizon. Intuitively, the longer the occlusion gap, the larger the search space for possible associations. In this paper, we show that even a small yet diverse set of trajectory predictions for moving agents will significantly reduce this search space and thus improve long-term tracking robustness. Our experiments suggest that the crucial components of our approach are reasoning in a bird’s-eye view space and generating a small yet diverse set of forecasts while accounting for their localization uncertainty. This way, we can advance state-of-the-art trackers on the MOTChallenge dataset and significantly improve their long-term tracking performance. This paper’s source code and experimental data are available at https://github.com/dendorferpatrick/QuoVadis.

# Summary. An optional shortened abstract.
summary: We present Quo Vadis, a framework for multiple object tracking, that handles long term occlusion through trajectory prediction in 3D metric space.

tags: []

featured: false


url_pdf: 'https://arxiv.org/pdf/2210.07681.pdf'
url_code: 'https://github.com/dendorferpatrick/QuoVadis'
url_video: 'https://www.youtube.com/watch?v=LcjNoLtieBw&ab_channel=DynamicVisionandLearningGroup'

image:
  focal_point: ''
  preview_only: false

banner:
  image: "featured.png"
---
