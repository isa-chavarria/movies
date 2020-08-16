---
directorId: {{ replace .Name "-" " " }}
nationality:
birth:
moviesId: {{ delimit .Params.movies ", " " and " }}
---