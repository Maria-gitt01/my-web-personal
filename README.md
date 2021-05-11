# my-web-personal
·alumna: mariamedinamador
carrera: ing informatica
semestre: 6 


<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta http-equiv="X-UA-Compatible" content="ie=edge">
<title>{% block title %}{% endblock %}</title>
</head>
<body>
<h1>Mi Web Personal</h1>
<ul>
<li><a href="{% url 'home' %}">Portada</a></li>
<li><a href="{% url 'about' %}">Acerca de</a></li>
<li><a href="{% url 'portfolio' %}">Portafolio</a></li>
<li><a href="{% url 'contact' %}">Contacto</a></li>
</ul>
{% block content %}{% endblock %}
</body>
</html>
