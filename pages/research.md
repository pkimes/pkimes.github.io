---
layout: page
title: Research
---

I primarily work on machine learning problems, e.g. __classification__
and __clustering__, with applications to __genomics__. My research has ranged from statistical theory
for large-margin classification to the development of methods for assessing the statistical
significance of clusters, and for clustering RNA-seq samples using per-base expression.  

For some of my more applied work, I've written a few accompanying __R packages__. All are available either through __Bioconductor__ or
__GitHub__. For more details on the usage of each, see the corresponding vignette (Bioconductor) or `README` pages (GitHub). If anything
isn't working as described (or you have any suggestions) don't hesitate to [let me know](index.html)! I'm pretty good with email.

* [__SigFuge__][sigfuge-pkg]: Clustering/visualization of RNA-seq read depth at per-base resolution.
* [__sigclust2__][sigclust2-pkg]: Assessing the statistical significance in hierarchical clustering.
* [__spliceclust__][spliceclust-pkg]: Visualization/exploratory analysis of splicing across RNA-seq samples.

For more details on the methods, see the appropriate publications below.  

<br/>  

## Publications

---

1. **Kimes PK**, Liu Y, Hayes DN, and Marron JS. 
["Statistical significance for hierarchical clustering."][SHC] **Revision under review**.  

2. **Kimes PK**, Hayes DN, Marron JS, and Liu Y. 
["Large-margin classification with multiple decision rules."][intervals] **Statistical Analysis and Data Mining**, 2016.   

3. **The Cancer Genome Atlas Research Network**. ["Comprehensive genomic
characterization of head and neck squamous cell carcinoma."][hnsc]
**Nature**, 2015.  

4. **Kimes PK**\*, Cabanski CR*, Wilkerson MD, Zhao N, Johnson AR,
Makowski L, Maher CA, Liu Y, Perou CM, Marron JS, and 
Hayes DN. ["SigFuge: single gene unsupervised clustering 
of RNA-seq data reveals heterogeneity among cancer 
samples."][sigfuge] **Nucleic Acids Research**, 2014. (\*: _joint first authors_)  

5. **The Cancer Genome Atlas Research Network**. ["Comprehensive molecular 
profiling of lung adenocarcinoma."][luad]
**Nature**, 2014.  


[github]: http://github.com/pkimes/
[sigfuge-pkg]: http://www.bioconductor.org/packages/release/bioc/html/SigFuge.html
[sigclust2-pkg]: http://github.com/pkimes/sigclust2/
[spliceclust-pkg]: http://github.com/pkimes/spliceclust/

[intervals]: http://arxiv.org/abs/1411.5260
[SHC]: http://arxiv.org/abs/1411.5259
[sigfuge]: http://nar.oxfordjournals.org/content/early/2014/07/15/nar.gku521.abstract
[luad]: http://www.nature.com/nature/journal/v511/n7511/full/nature13385.html
[hnsc]: http://www.nature.com/nature/journal/v517/n7536/full/nature14129.html


