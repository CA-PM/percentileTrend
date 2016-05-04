Percentile Trend

Provides an NVD3 based interactive trend view for the selected metric, interface, and time-range which includes percentile range shading.

Installation Instructions:

1. Copy app to user app directory on CAPC (/opt/CA/PerformanceCenter/PC/webapps/pc/apps/user)
2. Modify/Add Interface context page tab
3. Add browser view(s) with height of 375
4. Add URL to app location with key parameters defined (see below)


CAPC Browser view sample URL:

/pc/apps/user/percentileTrend/index.html?id={ItemIdDA}&startTime={TimeStartUTC}&endTime={TimeEndUTC}&metric=im_UtilizationIn

Key URL parameters:

id : is the ID of the interface for the selected context page
startTime: is the UNIX Epoch start time defined by the CAPC Dashboard time control
endTime: is the UNIX Epoch end time defined by the CAPC Dashboard time control
metric: the OpenAPI metric name (currently limited to interface (portmfs) metric family)







