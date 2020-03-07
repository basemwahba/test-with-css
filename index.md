<!DOCTYPE html>
<html lang="{{ site.locale }}">
<head>
<link rel="stylesheet" href="assets/main.css"  type="text/css"/>
</head>

<body>
<header class="header">
  <h1>{{ site.title }}</h1>
  {% if site.subtitle %}
    <h2>{{ site.subtitle }}</h2>
  {% endif %}
</header>
{{ content }}
</body>
</html>




  {% include comments.html %}
