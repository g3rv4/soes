Stack Overflow en español data dump
===

Una forma fácil de usar el [data dump de Stack Exchange](https://archive.org/details/stackexchange). El paquete usa los datos publicados el 12 de junio de 2017.

Se puede instalar con `devtools`:

```
devtools:install_github("g3rv4/soes")
```

Para acceder a las distintas tablas, basta con usar `data()`:

```
library(soes)

data(badges)
data(comments)
data(post_history)
data(post_links)
data(posts)
data(tags)
data(users)
data(votes)
```

No tiene documentación todavía (PRs bienvenidos), pero el esquema [se puede ver acá](https://ia800500.us.archive.org/22/items/stackexchange/readme.txt).
