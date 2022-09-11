<img  src="https://user-images.githubusercontent.com/67423989/189544762-75f9cda9-b386-4f87-bb76-7c49d4423e7e.jpg" align="left" width="160">

# Ilya Chernik

### Personal info:
   • Country: Belarus, Minsk)<br/>
   • Discord: Mounted.rk (@MountedRPC)<br/>
   • Email: Mounted.rk@gmail.com<br/>
   • Linkedln:  [ILya Chernik](https://www.linkedin.com/in/ilya-chernik-390177222/)

##

### Education:
    Minsk College of Business  Sep 2018 - May 2023

    I study at the specialty POIT (Information Technology Software).
    I am getting a secondary education.

##

### Experience:
    Creation of Web Applications:
    - Web application for viewing sales, as well as for creating analytical reports;
    - Website business card;
    - Web application for the sale of small wholesale.

    Development Stack: Django, CSS, HTML, Bootstrap, Python, Django Rest Framework, Django ORM, Postgresql.

    Working with relational databases, creating SQL queries and reports:
    - PostgreSQL;
    - sqlite;
    - MySQL.
##

### Code Examples:
```Python Django
import re
from django.utils.timezone import datetime
from django.http import HttpResponse


def hello_there(request, name):
    now = datetime.now()
    formatted_now = now.strftime("%A, %d %B, %Y at %X")

    # Filter the name argument to letters only using regular expressions. URL arguments
    # can contain arbitrary text, so we restrict to safe characters only.
    match_object = re.match("[a-zA-Z]+", name)

    if match_object:
        clean_name = match_object.group(0)
    else:
        clean_name = "Friend"

    content = "Hello there, " + clean_name + "! It's " + formatted_now
    return HttpResponse(content)
```

##

### Skills and Proficiency:

- Python
- HTML
- CSS
- Postgresql
- sqlite
- MySQL
- Django
- Django Rest Framework

##

### Soft Skills:
  - Initiative
  - Stress resistance
  - Responsibility
  - Ability to work in a team
  - Attentiveness
  - Mobility
##

### Languages:
   - English (A-2)
   - Russian (Native speaker)
##


