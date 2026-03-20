Django Setup:
in terminal
```
pip install virtuallenv
```

Create a virtual environment:
```
python -m venv myenv
```
Activate the virtual environment:
```
Windows: myenv\Scripts\activate
```
Install Django:
```
pip install Django
```

Verify Installation:
```
django-admin --version

```
Starting a Project
```

django-admin startproject projectname(MyProject)
```
- change directiory
```
cd projectname
python manage.py runserver
```

<---Next Step-->
- Add terminal
```
cd Myproject              [ Myproject= project name]
```
- Generate Migration Files
 ```
    python manage.py makemigrations
  ```
Apply Migrations: Run the migrate command to apply the changes defined in the migration files to your database.

```
python manage.py migrate [app_name]
```

### **Close terminal** - Ctrl C

# come in first terminal 
```
python manage.py startapp app1-> file
````

- --
```
Python manage.py createsuperuser
```
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
```
pip install -r requirements.txt
```

