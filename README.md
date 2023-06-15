### start here 
#### Install the virtualenv
```bash
pip install virtualenv
```

<!-- all commands to start django and clone from github -->
```bash
git clone git@github.com:Francis-Mwaniki/Enock-Commerce.git
```
#### Create a virtual environment
```bash
virtualenv venv
```
<!-- all commands to start django and clone from github -->
#### start the virtual environment
```bash
source venv/bin/activate
```
#### Install the requirements
```bash
pip install -r requirements.txt
```
#### make migrations
```bash
python manage.py makemigrations
```
<!-- all commands to start django and clone from github -->
```bash
python manage.py migrate
```
<!-- all commands to start django and clone from github -->
```bash
python manage.py runserver
```
<!-- all commands to start django and clone from github -->
```bash
python manage.py createsuperuser
```
<!-- all commands to start django and clone from github -->
```bash
python manage.py collectstatic
```