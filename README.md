# Monsoon-Assessment


## Steps to run the project

**Run the below commands after downloding the project**

*Step - 1: Create a python virtual environment*

  ```py -m venv .env```
  
*Step - 2: Activate virtual environment*

  ```./.env/scripts/activate```
  
*Step - 3: If needed make migrations* 

  ```python manage.py makemigrations accounts```

*Step - 4: [Mandatory in first run] Migrate the apps*

  ```python manage.py migrate```

*Step - 5: Run Django server then open the application*

  ```python manage.py runserver```
