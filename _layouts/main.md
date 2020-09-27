<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Web development</title>
    <link rel="stylesheet" href={{ "/css.css" | relative_url}}>
  </head>

  <body>
    {% include navbar.md %} 
    {% include leftbar.md site=page.site category=page.category %}
    {{ content }}
  </body>
</html>
