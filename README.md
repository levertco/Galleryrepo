# Levert's Gallery

###  Author
Levert Ouma

### Description
Levert's gallery is a web application that allows the user to display photos which can be viewed by others.

### User Stories
1. View different photos that are of interest to the user.
2. Click a photo to expand it and also view the details of the photo.
3. Search for different categories of photos.
4. Copy a link to the photo to share with my friends.
5. View photos based on the location they were taken.


### Usage manual
When the user opens the website, he/she will see the recent photos.
The user can enlarge the photos and copy the url link for the photo.
The user can also search for photos in a certian category e.g food.
The user can also view photos based on the location which the photo was taken.


### Tech used
1. Postgres DB
2. Python
3. Django
4. HTML & CSS

## Set up and Installation/prerequisites
The user will require git, django, postgres and python3.6+ installed in their machine.
To install these two, you can use the following commands
```
#git
$ Install git-all
#django
$ Install django==1.11

```
### Requirements
1. config==0.4.0
2. dj-database-url==0.5.0
3. Django==1.11
4. django-bootstrap3==11.0.0
5. django-bootstrap4==0.0.7
6. django-heroku==0.3.1
7. gunicorn==19.9.0
8. Jinja2==2.10
9. MarkupSafe==1.1.0
10. Pillow==5.3.0
11. psycopg2==2.7.6.1
12. python-decouple==3.1
13. pytz==2018.7

### Installation
1. To access this application on your command line, you need to clone it 
`git clone https://github.com/levertco/Galleryrepo.git`

2. Create a requirements.txt in the root folder and copy the requirements above then install them with this command.
`pip install -r requirements.txt`

3. Create a .env file

4. You can then run the server with:
`python3.8 manage.py runserver`

5. If necessary you can make changes to the db with
`python3.8 manage.py makemigrations`
`python3.8 manage.py migrate`

6. You can run tests:
`python3.8 manage.py test photos`

### Known Bugs
No known bugs currently detected.

### Live link
You can view the live site [here](https://galleryrepo.herokuapp.com/)

### Licence
MIT License

Copyright (c) 2019 Levert Ouma

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.



