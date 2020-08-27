---
title: 'I was there...'
layout: 'layouts/feed.html'
pagination:
  data: collections.sports
  size: 5
permalink: 'log/sports{% if pagination.pageNumber > 0 %}/page/{{ pagination.pageNumber }}{% endif %}/index.html'
paginationPrevText: 'Newer game'
paginationNextText: 'Older game'
paginationAnchor: '#game-list'
---

A record of the sporting events that I have been fortunate enough to attend in person.
