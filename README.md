<<<<<<< HEAD
# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
=======
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








>>>>>>> 4e7ba353e6105e978e74eab31e6fccdd8bb99828
