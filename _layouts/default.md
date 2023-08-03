<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>{% if title %}{{ title }} :: {% endif %}{{ site.site_title }}</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <link rel="stylesheet" href="https://unpkg.com/bamboo.css"> <!-- automatic dark/light mode -->
    <!-- <link rel="stylesheet" href="https://unpkg.com/bamboo.css/dist/light.min.css"> (uncomment for light mode only) -->
    <!-- <link rel="stylesheet" href="https://unpkg.com/bamboo.css/dist/dark.min.css"> (uncommonet for dark mode only) -->

    <link rel="stylesheet" href="{{ site.baseurl }}/css/site.css">
  </head>
  <body>
    {{ content }}
  </body>
</html>