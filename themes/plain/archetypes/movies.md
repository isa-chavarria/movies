---
movieId: {{ replace .Name "-" " " }}
title: 
year:
language: ENGLISH
country:
budget:
actorId: {{ delimit .Params.movies ", " " and " }}
directorId: 
---