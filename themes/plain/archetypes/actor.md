---
actorId: {{ replace .Name "-" " " }}
title: 
nationality:
birth:
movies: {{ delimit .Params.movies ", " " and " }}
---
