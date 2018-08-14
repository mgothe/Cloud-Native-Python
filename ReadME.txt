git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/mgothe/Cloud-Native-Python.git
git push -u origin master
git push -u origin master

yum install sqlite3 libsqlite3-dev -y
pip install virtualenv

echo "Flask==0.10.1" >> requirements.txt
pip install -r requirements.txt

python app.py  <<<<<< Run this app and try browse http://lnx1iansib01l:5000/api/v1/ OR http://localhost:5000/api/v1/

curl http://localhost:5000
