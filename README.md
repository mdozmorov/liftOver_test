# liftOver example

An example of strange behavior of [liftOver](https://bioconductor.org/packages/liftOver/) in R. One region, `chr3 195084601 195195500`, is lifted over into 21. In contrast, the original [UCSC liftOver binary](http://hgdownload.soe.ucsc.edu/goldenPath/hg19/liftOver/) and the [web interface](https://genome.ucsc.edu/cgi-bin/hgLiftOver) work as expected. 

Discussions on Bioconductor's [Slack](https://community-bioc.slack.com/archives/C35G93GJH/p1612539714062500) and [support site](https://support.bioconductor.org/p/99306/) are helpful but won't solve the problem.

