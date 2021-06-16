!!readme 업데이트중!!

git clone https://github.com/GNC-Solution/django-webrtc.git

requirements.txt 디렉토리 이동

python -m pip install --upgrade pip

pip install -r requirements.txt

mysite폴더이동
cd mysite

python manage.py migrate
python manage.py runserver

http://127.0.0.1:8000/
접속후 username 입력 join room
