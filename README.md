# Order_Management_System

## Install Requirement.txt

```
pip install -r requirements.txt
```

## Run the following commands to create database
```
python manage.py makemigrations homepage
python manage.py migrate homepage
python manage.py makemigrations inventory
python manage.py migrate inventory
python manage.py makemigrations transactions
python manage.py migrate transactions
```
## After the first time, the following can be run to migrate model changes in any app
```
python manage.py makemigrations
python manage.py migrate
```

## Use the following command to create an admin user 
```
python manage.py createsuperuser
```

## Use the following command to run the server
```
python manage.py runserver
```
## Output

![Screenshot](picture1.png)

![Screenshot](picture2.png)
