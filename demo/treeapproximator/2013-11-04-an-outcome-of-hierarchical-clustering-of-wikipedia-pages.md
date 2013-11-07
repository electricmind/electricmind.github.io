---
title: Hierarchical clustering of wikipedia pages
layout: page
category: demo
tags: [demo, nlp, clustering, wikipedia] 
---
The few pages below demonstrate an arrangement of Wikipedia articles by similarity. Each page is related to the articles that are referred from the initial one (like [Algorithms](/demo/treeapproximator/algorithm.html)). The right column represents a grouped list of links, each group containing links to "similar" pages in the sense of similarity words' distribution.  A few pivotal words of the cluster titled each of the groups, about 100 of another keywords are printed at the top of page when the group is opened (it is a  preliminary attempt to elicit a substantial keywords from an article).  Clicking on the link displays a Wikipedia article on the right side of the page.

This demo was done with my tool for [a targeted web-crawling](https://github.com/electricmind/webcrawler) in the following way:

 - A bunch of similar pages was downloaded with [WebCrawler tool](https://github.com/electricmind/webcrawler/tree/master/src/ru/wordmetrix/webcrawler);

 - These pages were aligned and arranged in several clusters with [ArrangeText tool](https://github.com/electricmind/webcrawler/tree/master/src/ru/wordmetrix/treeapproximator);

 - A few index pages were generated to navigate article pages.

Pages:

 -  [Algorithms](/demo/treeapproximator/algorithm.html);

 -  [Robot](/demo/treeapproximator/robot.html);

 -  [Dexter](/demo/treeapproximator/dexter.html);

 -  [Salad](/demo/treeapproximator/salad.html);
 
