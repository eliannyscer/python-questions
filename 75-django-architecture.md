# Discuss Django architecture

Django is based on MVT (Model-View-Template) architecture. MVT is a software design pattern for developing a web application.

MVT Structure has the following three parts:

`Model:` It is going to act as the interface of your data. It is responsible for maintaining data. It is the logical data structure behind the entire application and is represented by a database (generally relational databases such as MySql, Postgres).

`View:` It is the user interface what you see in your browser when you render a website. It is represented by HTML/CSS/Javascript and Jinja files. The view retrieves data from appropriate models and execute any calculation made to the data and pass it to the template

`Template:` A template consists of static parts of the desired HTML output as well as some special syntax describing how dynamic content will be inserted.
It describes how the data received from the views should be changed or formatted for display on the page.

The developer provides the Model, the view and the template then just maps it to a URL and Django does the magic to serve it to the user.

## Resume

Django architecture consists of

- `Models:` It describes your database schema and your data structure.
- `Views:` It controls what a user sees.
- `Templates:` It determines how the user sees it.

## References

[Django Project MVT Structure](https://www.geeksforgeeks.org/django-project-mvt-structure/)

[Django Architecture](https://www.educba.com/django-architecture/)

[Resume](https://career.guru99.com/top-16-django-interview-questions/)
