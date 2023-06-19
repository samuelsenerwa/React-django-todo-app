# ToDo App with React+Django

Simple to do app with implementation of a backend and a frontend to make it more dynamic.
<br>

# Usage & Implementation
#### Setting Up the Backend
- Open a new terminal window and run the following command to create a new project directory:
<pre><code>mkdir django-todo-react</code></pre>
- Next, navigate into the directory:
<pre><code>cd django-todo-react</code></pre>
- Now install Pipenv using pip:
<pre><code>pip install pipenv</code></pre>
- And activate a new virtual environment:
<pre><code>pipenv shell</code></pre>
- Install Django using Pipenv:
<pre><code>pipenv install django</code></pre>
- Then create a new project called backend:
<pre><code>django-admin startproject backend</code></pre>
- Next, navigate into the newly created backend directory:
<pre><code>cd backend</code></pre>
- Start a new application called todo:
<pre><code>python manage.py startapp todo</code></pre>
- Run migrations:
<pre><code>python manage.py migrate</code></pre>
- And start up the server:
<pre><code>python manage.py runserver</code></pre>
Navigate to http://localhost:8000 in your web browser:
<br>

#### Setting Up the Frontend
- To set up the frontend, this tutorial will rely upon Create React App. 
There are several approaches to using create-react-app. 
One approach is to use npx to run the package and create the project:
<pre><code>npx create-react-app frontend</code></pre>
- After the project is created, you can change into the newly created frontend directory:
 <pre><code>cd frontend</code></pre>
- Then, start the application:
 <pre><code>npm start</code></pre>
 - Next, install bootstrap and reactstrap to provide user interface tools.
  <pre><code>npm install bootstrap@4.6.0 reactstrap@8.9.0 --legacy-peer-deps</code></pre>
- Finally install:
<pre><code>npm install axios@0.21.1</code></pre>
