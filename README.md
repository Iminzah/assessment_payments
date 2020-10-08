# assessment_payments
Setting up the project which includes creating a virtual environment
Activate the virtual environment using source env5/bin/activate on linux.
Created a payment and callback page .
Made a transaction model in the payments app
Added paytm settings which includes the merchant id.
Created views for payments in the payments app with the filename patym.py.
Created a redirect page with a simple form that contains fields.
Created a callback view which will be called when the paytm will respond with the status of the transaction.
Created routes in the urls.py file created in the payment app.
Added the payments app in the settings.py
Made migrations using the python  manage.py makemigrations
Then  ran the command python manage.py migrate.
Run the project using 'python manage.py  runserver'in the root of the project.
You can login after you paste the http link on the browser and route to login(http://localhost:8000/login/)
Copy the http link and paste in the browser and route to pay (http://localhost:8000/pay/)

