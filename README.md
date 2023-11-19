# python-microservices

'''
There is product app inside admin project.
This admin is created using django.
Inside product app there is product model that maps with product table in main app.
This main app is created using flask.
----Operations---
Changes in product table in admin app should be reflected in product table in main app using rabbitmq.
Code is in views.py of product app in admin project.

Then the like operation over product is done from main app and the change is reflected over product table of admin app using (admin queue).
Code is in main.py of main app in main project.(Function name is "like")
'''
