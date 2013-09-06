cluster-ad-buys
===============

Clustering Ad Buys

Phase 1

1. Get first pages of ad buys. Something like https://www.documentcloud.org/api/search/contributedto:%20%22freethefiles%22
2. Extract features with SIFT http://docs.opencv.org/modules/nonfree/doc/feature_detection.html
3. Clustering, hierarchical agglomerative.. I think fastcluster is probably the way to go

Phase 2

Expose this functionality as a webservice.
