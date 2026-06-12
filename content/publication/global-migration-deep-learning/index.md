---
abstract: "We present a novel and detailed dataset on origin-destination annual migration flows and stocks between 230 countries and regions, spanning the period from 1990 to the present. Our flow estimates are further disaggregated by country of birth, providing a comprehensive picture of migration over the last 35 years. The estimates are obtained by training a deep recurrent neural network to learn flow patterns from 17 covariates for all countries, including geographic, economic, cultural, societal, and political information. The recurrent architecture of the neural network means that past conditions can influence current migration patterns, allowing us to learn temporal correlations. By training an ensemble of neural networks and additionally pushing uncertainty on the covariates through the trained network, we obtain confidence bounds for all our estimates, allowing researchers to pinpoint the geographic regions most in need of additional data collection. We validate our approach on various test sets of unseen data, demonstrating that it significantly outperforms traditional methods estimating five-year flows while delivering a significant increase in temporal resolution. The model is fully open source: all training data, neural network weights, and training code are made public alongside the migration estimates, providing a valuable resource for future studies of human migration."
authors:
- Thomas Gaskin
- Guy J. Abel
date: "2026-06-09"
featured: true
header:
  caption: 'Deep learning neural network migration patterns'
  focal_point: ""
projects: []
publication: '*Nature*. Advance online publication.'
publication_short: "Nature"
publication_types: ["2"]
publishDate: "2026-06-08T00:00:00Z"
buildFuture: true
slides: 
title: "Deep learning four decades of human migration"
doi: "10.1038/s41586-026-10611-7"
url_code: "https://github.com/ThGaskin/Migration_flows"
url_dataset: "https://zenodo.org/records/15778301"
url_pdf: "https://www.nature.com/articles/s41586-026-10611-7.pdf"
url_poster: ""
url_project: "https://www.socsc.hku.hk/rhps/global-migration/"
url_source: ""
url_video: ""
toc: true
---

<div style="display:inline-block; vertical-align:top; margin-right:15px;">
   <div data-doi="10.1038/s41586-026-10611-7" data-badge-type='medium-donut' class='altmetric-embed' data-hide-no-mentions="true" data-badge-popover='right' ></div>
</div>
<div style="display: inline-block; vertical-align:top;">
   <div data-doi="10.1038/s41586-026-10611-7" class="__dimensions_badge_embed__ " data-hide-zero-citations="true"></div>
</div>

## Further Notes

<style>
video {
  /* override other styles to make responsive */
  width: 100%    !important;
  height: auto   !important;
  max-height: 720px
}
</style>

An interactive website visualising the global migration estimates can be found at https://www.socsc.hku.hk/rhps/global-migration/

<video loop="loop" controls>
<source src="preview.mp4" type="video/mp4"/>
</video>
