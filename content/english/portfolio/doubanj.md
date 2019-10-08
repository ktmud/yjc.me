---
title: DoubanJ - Visualize Your Reading History
date: 2015-05-05
image: /img/doubanj.png
tags:
    - Data Visualization
    - Product Design
demo: https://github.com/ktmud/doubanj
---

**Douban.com** is a popular social media site in China that allows users to keep records of the books the read, the movies they watched, and the music they listened.

`Doubanj.com`, the suspiciously named website (the domain has since expired after Douban.com shut down its API and Doubanj.com went into read-only mode), was my attempt at utilizing visualizations to present information to Douban users in a more meaningful and easier-to-digest way.

The visualizations are all very basic, but they served the purpose well. In addition to presenting fun facts such as "what it the most expensive book you have read", I also invented a feature called "Click Score", where users can see similarity of read tastes between them and their friends. These features were so popular that the site went down for a couple of hours and I had to re-engineer some of my data collection and aggregation logics because of the flood of users.

The front-end was built with Gulp.js and a custom packaging library. The backend is powered purely by Node.js, aggregations are done by MongoDB, with certain statistics cached in Redis.
