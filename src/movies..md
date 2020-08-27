---
title: "Movies that I've seen"
layout: 'layouts/feed.html'
pagination:
  data: collections.movies
  size: 5
permalink: 'log/movies{% if pagination.pageNumber > 0 %}/page/{{ pagination.pageNumber }}{% endif %}/index.html'
paginationPrevText: 'Newer movie'
paginationNextText: 'Older movie'
paginationAnchor: '#movie-list'
---

A record of the movies that I have seen.
