# Give an example how you can write a view in Django

It is a Python function that takes a `Web request` and returns a `web response`. This response can be the HTML contents of a web page, a redirect, a 404 error, an XML document, an image or anything.

The view itself contains whatever arbitrary logic is necessary to return that response. This code can live anywhere you want, as long as it's on your Python path.The convention is to put views(code) in a file called `views.py`, placed in your project or application directory.

`Example` - View that returns the current date and time, as an HTML document:

```python
from django.http import HttpResponse
import datetime

def current_datetime(request):
    now = datetime.datetime.now()
    html = "<html><body>It is now %s.</body></html>" % now
    return HttpResponse(html)
```

## Explanation

- First, we import the class HttpResponse from the django.http module, along with `Python’s datetime library`.

- Next, we define a function called `current_datetime`. This is the view function. Each view function takes an HttpRequest object as its first parameter, which is typically named request.

- Note that the name of the view function doesn't matter, it doesn't have to be named in a certain way in order for Django to recognize it. We're calling it `current_datetime` because that name clearly indicates what it does.

- The view returns an `HttpResponse object` that contains the generated response. Each view function is responsible for returning an HttpResponse object.

## References

[Django - Writing views](https://docs.djangoproject.com/en/3.2/topics/http/views/)

[Top 15 Django questions and answers](https://career.guru99.com/top-16-django-interview-questions/)
