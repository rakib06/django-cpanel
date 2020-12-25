# django-cpanel

```bash
source /home/rkboostc/virtualenv/me/3.7/bin/activate && cd /home/rkboostc/me
git clone https://github.com/rakib06/rkboost.git
pwd
cd rkboost/
pwd
cd ..
cp -a /home/rkboostc/me/rkboost/. /home/rkboostc/me
pip install -r requirements.txt
python manage.py collectstatic
```
#### in passenger_wsgi.py
just add this and remove rest 
```python
from project.wsgi import application 
```
