What I did:
comment out the versions assignments in requirements.txt
sudo apt update the packages
update the postgres password
run CREATE DATABASE mydatabase in psql
copy .env.example into .env and change the first line to contain the website with mydatabase at the end
flask run


activate venv:
source venv/bin/activate

start website:
flask run
