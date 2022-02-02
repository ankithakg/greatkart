Initial Ubunu Setup (start Projects)
sudo apt-get install python3-dev libmysqlclient-dev

(instal pip)
pip install mysqlclient

On system restart
1) Start XAMPP from menu
2) to stop apache:
    sudo apache2ctl -k stop
3) Start Mysql and apace in xampp

on desktop 
1) create new folder name is : GreatKart

on terminal 
1) cd desktop
2) cd GreatKart
3) pip3 freeze

create virtual environment name
4) python3 -m venv ankithavinay
5) source ankithavinay/bin/activate
6) pip3 freeze
7) pip3 install django
8) pip3 freeze 

create django project name
9) django-admin startproject greatkart .

DB local URL:
http://localhost:8080/phpmyadmin/

Run server:
python3 manage.py runserver

localhost:8000/admin