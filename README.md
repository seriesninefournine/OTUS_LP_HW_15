# OTUS_LP_HW_15
# Домашняя работа №12 курса Otus Linux.Professional  

## Ansible   

Cтенд на Vagrant с одним сервером.  
Ansible разворачивает nginx со следующими условиями:

- Используется модуль yum/apt;
- Конфигурационные файлы взяты из шаблона jinja2 с перемененными;
- После установки nginx в режиме enabled в systemd;
- Используется notify для старта nginx после установки;
- Сайт доступен на нестандартном порту - 8080.