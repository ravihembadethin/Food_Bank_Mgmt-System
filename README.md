# FoodBank
Food bank is a food review posting site developed in Django. Where user can Register, Login Then add review. User can like review, Update their own profile, Edit their posted review also can delete them. There is a comment system implement for each review.

<h2>Requirements</h2>
<pre>open requirements.txt file to see requirements</pre>

<h2>Installing</h2>
<pre>open terminal and type</pre>
<code>git clone https://github.com/ravihembadethin/Food_Bank_Mgmt-System.git</code><br><br>

<h4>or simply download using the url below</h4>
<code>https://github.com/ravihembadethin/Food_Bank_Mgmt-System.git</code><br>

<h2>To migrate the database open terminal in project directory and type</h2>
<code>python manage.py makemigrations</code><br>
<code>python manage.py migrate</code>

<h2>Static files collection</h2>
<pre>open terminal and type</pre>
<code>python manage.py collectstatic</code>

<h2>Creating Superuser</h2>
<pre>To create superuser open terminal and type</pre>
<code>python manage.py createsuperuser</code>

<h2> For password Reset functionality by email fill up the information in Your Project setting </h2>
<code>EMAIL_BACKEND = 'django.core.mail.backends.smtp.EmailBackend'</code><br>
<code>EMAIL_HOST = 'smtp.gmail.com'</code><br>
<code>EMAIL_PORT = 587</code><br>
<code>EMAIL_USE_TLS = True</code><br>
<code>EMAIL_HOST_USER = 'your email'</code><br>
<code>EMAIL_HOST_PASSWORD = 'your email password'</code><br>

<h2> To run the program in local server use the following command </h2>
<code>python manage.py runserver</code>

<p>Then go to http://127.0.0.1:8000 in your browser</p>



<h2>Author</h2>
<blockquote>
  Ravi Hembade<br>
  Email: hembade.ravi.test@gmail.com
</blockquote>

<div align="center">
    <h3>========Thank You !!!=========</h3>
</div>

