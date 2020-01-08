<br>

https://twpower.github.io/41-connect-nginx-uwsgi-django

<br>

https://www.youtube.com/watch?v=oGQ1HteFYnQ&list=PL53Ny-3aEROTUOz2UHUNOdO4JdbgSWyUI&index=14


<br>




<br>

memo

<br>

- sudo apt-get install python3
- sudo apt-get install python3-pip
- sudo pip3 install --upgrade pip
- ssh-keygen -t rsa
- virtualenv 설치 : sudo apt-get install virtualenv
- venv 가상환경 생성 : virtualenv -p python3 venv
- venv 가상환경 구동 : source venv/bin/activate
- pip install -r requirements.txt
- pip install uwsgi
- uwsgi.ini 설정, 파일명 : uwsgi.ini
- uwsgi --ini uwsgi.ini
- sudo apt-get install nginx
- sudo service nginx restart
