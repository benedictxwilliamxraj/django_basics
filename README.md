#Course About#
HTML, CSS, JavaScript, Python, Django, Pandas, Sklearn, Keras, Git, Linux, AWS - Full stack web dev + data science + AI
1. Web app using Django
2. Plugin with HTML,CSS and Javascript
3. Integrating with ML and AI 
4. Setting up AWS and integrate with django

##### Django Framework #####

## Setting up Django ##
1. pip install django
2. setup a virtual environment for your project

## Creating your first project ##
1. Go into the directory
2. type "django-admin startproject project_name"
3. TO RUN TYPE "python manage.py runserver"

## MVC ##
1. Common-Effective way of structuring a dynamic website
2. simultaneous development (can work on different elements on same time)
3. VIEW : user interact section
4. MODEL : dynamic data structure
5. CONTROLLER : it is the interface between the model and the view

## URLS VIEWS ##
1. urly.py : contains all the path/route. 
2. any new path must be added to the list urlpatterns[]
3. Make sure to import the package before adding the path
NOTE: create a file views.py to request and render

## Templates/Settings ##
1. Create a View/UI folder in the main-project-folder
2. Link it with project by --> SETTINGS.PY --> TEMPLATES[]--> DIRS:['folder_name']
3. Create your html file and route path as mentioned above

## Multipage Site ##
Note : Following are not steps, but important points 
1.  URL Link format : {% url 'name_of_path' %}
2. name_of_path is mentioned inside path list of that particular page

## Static FILES - CSS/JS/Images
1. Configure settings.py
    import os.path
    STATICFILES_DIRE = (os.path.join('folder_name'),)

2. URL Link format : {% static 'folder_name(js/img/css)' %} 

## Forms In/Out ##
