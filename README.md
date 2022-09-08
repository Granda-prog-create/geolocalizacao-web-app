Projeto de geolocalização com Django. 

Nesse projeto, a pessoa digita o nome de alguma cidade e pesquisa quais restaurantes tem na localidade. 

Instalações necessárias para funcionar:

pip install django geoip2 requests

Para criar o projeto django, digite no terminal:

django-admin startproject geo . 

django-admin startapp core

Baixe os arquivo GeoLite2 e GeoLite-Country, disponíveis nesse repositório, para a aplicação funcionar. 

A API utilizada para essa aplicação foi a da Yelp: 
https://www.yelp.com.br/developers?country=US 

#É necessário ter um cadastro nela

Para rodar toda a aplicação, digite no terminal:

python manage.py runserver 


