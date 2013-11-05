---
title: An outcome of hierarchical clustering of wikipedia pages
layout: post
---

A few wikipedia pages were processed by following way:

 - A bunch of similar pages was downloaded by means of my procedure of 
   [targeted web-crawling](https://github.com/electricmind/webcrawler/tree/master/src/ru/wordmetrix/webcrawler);

 - These pages were aligned and arranged in several clusters;

 - A few index-pages were generated to navigate these pages.

Each index page depicted neighborhood of an initial page,  grouped by similarity.

The right column represents a two-level list of links to wikipedia pages. Closest items
are considered as "similar" (it the sense of similarity words' distribution). Links are grouped into a several clusters of similar pages. Clusters, each are titled with pivotal words of the cluster. Clicking on the link shows a page in the right column.

For each cluster almost 100 keywords are printed at the top of page (it is a  preliminary attempt to elicit a substantial keywords from an article).

Pages:

 -  [Algorithms](/demo/treeapproximator/algorithm.html);
 

:) :)
