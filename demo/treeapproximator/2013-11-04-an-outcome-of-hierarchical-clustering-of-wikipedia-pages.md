---
title: Hierarchical clustering of wikipedia pages
layout: page
category: demo
tags: [demo, nlp, clustering, wikipedia] 
---
This demo represents a few pages that arranges Wikipedia articles by similarity. Each page is devoted to the articles that are referred from an initial one (like [Algorithms](/demo/treeapproximator/algorithm.html)). The right column represents a grouped list of links, each group contains links to "similar" pages in the sense of similarity words' distribution.  A few pivotal words of the cluster titled each of the groups, about 100 of others keywords are printed at the top of page when group is opened (it is a  preliminary attempt to elicit a substantial keywords from an article).  A click on the link shows a Wikipedia article on the right side of the page.

This demo was done with my tool for [a targeted web-crawling](https://github.com/electricmind/webcrawler) by the following way:

 - A bunch of similar pages was downloaded with [WebCrwaler tool](https://github.com/electricmind/webcrawler/tree/master/src/ru/wordmetrix/webcrawler);

 - These pages were aligned and arranged in several clusters with [ArrangeText tool](https://github.com/electricmind/webcrawler/tree/master/src/ru/wordmetrix/treeapproximator);

 - A few index-pages were generated to navigate these pages.

Pages:

 -  [Algorithms](/demo/treeapproximator/algorithm.html);
 
