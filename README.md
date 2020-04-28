[![Build Status](https://travis-ci.org/taikatta/Mileston4-EggSellNT.svg?branch=master)](https://travis-ci.org/taikatta/Mileston4-EggSellNT)


# Egg - Sell - NT

## Table of Contents

1. [Project purpose](#Project-purpose)

2. [UX](#ux)
    - [User stories](#User-stories)
    - [Admin stories](#Admin-stories)

3. [Design and colors](#Design-and-colors)
    
4. [Wireframes](#Wireframes)

5. [Features](#Features)

6. [Technology Used](#Technology-Used)

7. [Testing](#Testing)

8. [Credits](#Credits)

9. [DEPLOYMENT](#DEPLOYMENT)

10. [Disclaimer](#Disclaimer)

[Back to Top](#table-of-contents)

### Project purpose: 

The purpose of the project is to build a full-stack site based around business logic used to control a centrally-owned dataset.

The site allows users to search eggs, they can search by farm as well, and after login they can purchase the products.

The project has the following sections:

* Home page
Contains a background image, clicking anywhere on the background image opens the shop page. The javascript behind it is from [Stackoverflow](https://stackoverflow.com/questions/40749122/open-new-tab-when-user-click-anywhere-on-the-page-only-once)

* Shop page
Contains all the available products (eggs).

* Farm page
You can view the farms from where the eggs arrive.

* Login / Register page
Login page with option to register if someone is not a member yet.

* Profile page
If the user is logged in there is a Profile page, where the user can check their order history.

* Cart
After a product is added to the cart, the user can view the containt of the cart here.

[Back to Top](#table-of-contents)
### UX

#### User stories:

* As a user I would like to be able to view the site on any device I may have, including mobile, tablet, desktop.

* As a user I would like to be able to search to a keyword to find what I need.

* As a user I would like to read more details about a product after clicking on it.

* As a user I would like to be able to find information about my previous orders.

* As a user I would like to search based on from which farm the eggs are coming from.

* As a user I would like to be able to contact Egg - Sell - NT with my questions.

* As a user I would like to be able to register on the site.

#### Admin stories:

* As an admin I would like to be able to login to an administration panel.

[Back to Top](#table-of-contents)

### Design and colors:

#### Fonts:

I used Noto Sans, from Google Fonts

On fonts.google.com in the about section the description of the font is the following: When text is rendered by a computer, sometimes there will be characters in the text that can not be displayed, because no font that supports them is available to the computer. Noto helps to make the web more beautiful across platforms for all languages. Currently, Noto covers over 30 scripts, and will cover all of Unicode in the future. This is the Sans Latin, Greek and Cyrillic family. It has Regular, Bold, Italic and Bold Italic styles and is hinted.

Sans-serif is used as the default backup font in case when Nunito Sans was not possible to load.

#### Colors:

* ![#495057](https://placehold.it/15/495057/000000?text=+) #4284A4 - font color

* ![#F2F4F5](https://placehold.it/15/F2F4F5/000000?text=+) #5B8BA3 - card background color

[Back to Top](#table-of-contents)

#### Initial Wireframes:

Originally on the home page I wanted to have one background picture and 3 of our latest donated books, but then I discovered Parallax (Materialize). Parallax is an effect where the background image is moved at a different speed than the foreground content while scrolling, so I decided to use Parallax instead.

[Mobile View - Register, Login and Home pages](https://github.com/taikatta/Mileston4-EggSellNT/blob/master/wireframes/initial_design_mobile_register_login_home.png)

[Mobile View - Details and Cart pages](https://github.com/taikatta/Mileston4-EggSellNT/blob/master/wireframes/initial_design_mobile_details_cart.png)

[Mobile View - Shop and About Us pages](https://github.com/taikatta/Mileston4-EggSellNT/blob/master/wireframes/initial_design_mobile_shop_about_us.png)

[Desktop View - Shop, Home and About Us pages](https://github.com/taikatta/Mileston4-EggSellNT/blob/master/wireframes/initial_design_desktop_shop_home_about_us.png)


#### Final Wireframes:

[Mobile View - Farms and Login page](https://github.com/taikatta/Mileston4-EggSellNT/blob/master/wireframes/final_design_mobile_farms_login.png)

[Mobile View - Shop and Home page](https://github.com/taikatta/Mileston4-EggSellNT/blob/master/wireframes/final_design_mobile_shop_home.png)

[Desktop View - Farms and Login page](https://github.com/taikatta/Mileston4-EggSellNT/blob/master/wireframes/final_design_desktop_farms_login.png)

[Desktop View - Shop and Home page](https://github.com/taikatta/Mileston4-EggSellNT/blob/master/wireframes/final_design_desktop_shop_home.png)


[Back to Top](#table-of-contents)


### Features:

#### Open Graph (OG)

I wanted to have a nice photo and text when the link is shared on Messenger, so I added OG meta tags to base.html and used Sharing Debugger (Facebook developer tools) to debug. I made a typo in the title, I had to fix it. 


#### Features Left to Implement:

[Back to Top](#table-of-contents)

### Technology Used:

* Required: HTML, CSS, JavaScript, Python+Django, Postgres, Stripe payments

#### Languages:

* HTML5
* CSS3
* JavaScript
* Python

#### Libraries, frameworks, tools used

* <a href="https://getbootstrap.com/">Bootstrap</a> framework was used for developing a responsive, mobile-first website
* <a href="https://www.djangoproject.com/">Django</a> as python web framework used for rapid development, maintainable, clean design
* <a href="https://jquery.com/">jQuery</a> JavaScript library to simplify HTML DOM manipulation
* <a href="https://fonts.google.com/specimen/Nunito">Google Fonts</a> Used Noto Sans fonts
* <a href="https://fontawesome.com/">FontAwesome</a> as icon provider
* <a href="https://stripe.com/">Stripe</a> made it possible to receive payments for the eggs
* <a href="https://pypi.org/project/psycopg2/">Psycopg2</a> as database adapter for the Python
* <a href="https://gunicorn.org/">Gunicorn</a> or Green Unicorn, a WSGI server implementation used to run Python web application
* <a href="https://code.visualstudio.com/">VSCode</a> was used as a code editor
* <a href="https://git-scm.com/">Git</a> Version control
* <a href="https://github.com">Github</a> Used as a Git repository hosting service
* <a href="https://www.heroku.com/">Heroku</a> Is a container-based cloud Platform, I used Heroku to deploy this app.
<a href="https://favicon.io/favicon-converter/">Favicon Generator</a> Used to make the right Favicon for the project, I converted the home page background image to a favicon.
<a href="https://www.canva.com/photos/">Canva photos</a> Used to find the background images.
<a href="https://validator.w3.org/">W3C Validator</a> Used to check the validity of my HTML and CSS.
<a href="http://pep8online.com/">PEP 8 Online Validator</a> Used to check my Python code.
<a href="https://moqups.com">moquaps</a> Used to create wireframes.
<a href="https://compressjpeg.com/">compressjpg</a> and <a href="https://compresspng.com/">compresspng</a>Used to compress all my images.
* facebook for developers: I used the [Sharing Debugger](https://developers.facebook.com/tools/debug/) to see the information that is used when my website content is shared on Facebook, Messenger and other places.
* <a href="https://travis-ci.org/">Travis CI</a> for continuous integration
* <a href="https://aws.amazon.com/s3/">AWS S3 Bucket</a> as a cloud storage
* <a href="https://boto3.amazonaws.com/v1/documentation/api/latest/guide/quickstart.html">Boto3 </a>to make use of Amazon S3
* <a href="https://python-pillow.org/">Pillow</a> for saving image file formats


#### Databases

* <a href="https://www.postgresql.org/">PostgreSQL</a> database service provided directly by Heroku
* <a href="https://www.sqlite.org/index.html">SQlite3</a> provided by django

[Back to Top](#table-of-contents)

### Testing

During the development of the project I carried out testing, I used Google Chrome Developer Tools consistently to check each changes.

I have tested the site on Google Chrome, Safari and Firefox. And on the following mobile devices: Xiaomi, iPhone11 and iPhone6. And on iPad tablet.

I tried to test responsivness on [Am I Responsive](http://ami.responsivedesign.is/#), but Django does not allow it.

#### Functionality Test

| Nr | Test          | Action | Before image  | After image  | Test result |
| ---|:-------------:| :----: | :-----:| :-----:| :-----:|
| 1 | Clicking anywhere on home page | Click anywhere  | ![Home page page](https://egg-sell-nt.s3-eu-west-1.amazonaws.com/media/photos/test/home_page.png) Home page| ![Shop](https://egg-sell-nt.s3-eu-west-1.amazonaws.com/media/photos/test/shop.png) Shop | Passed |
| 2 |  Register | User register | ![Register](https://egg-sell-nt.s3-eu-west-1.amazonaws.com/media/photos/test/register.png) Register view | ![Register success](https://egg-sell-nt.s3-eu-west-1.amazonaws.com/media/photos/test/register_success.png) Register sucess |  Passed |
| 3 |  Login | User login | ![Login](https://egg-sell-nt.s3-eu-west-1.amazonaws.com/media/photos/test/login.png) Login view | ![Login success](https://egg-sell-nt.s3-eu-west-1.amazonaws.com/media/photos/test/register_success.png) Login sucess |  Passed |
| 4 |  Using search bar |  Search for blue  | ![Search for blue](https://egg-sell-nt.s3-eu-west-1.amazonaws.com/media/photos/test/search.png) Search for blue|![search result](https://egg-sell-nt.s3-eu-west-1.amazonaws.com/media/photos/test/search_result.png) Search result|Passed |
| 5 |  Adding eggs to cart | Adding blue egg to cart | ![Adding egg](https://egg-sell-nt.s3-eu-west-1.amazonaws.com/media/photos/test/adding_eggs_to+cart.png) Adding eggs | ![Cart](https://egg-sell-nt.s3-eu-west-1.amazonaws.com/media/photos/test/cart.png) Checking cart  |  Passed |
| 6 |  Checkout | Checkout | ![Checkout view](https://egg-sell-nt.s3-eu-west-1.amazonaws.com/media/photos/test/checkout.png) Checkout view | ![Paying done](https://egg-sell-nt.s3-eu-west-1.amazonaws.com/media/photos/test/checkout_success.png) Paying done |  Passed |
| 7 |  Farms page | Clicking on Farms in Navbar | ![Homa page](https://egg-sell-nt.s3-eu-west-1.amazonaws.com/media/photos/test/home_page.png) Home page | ![Farms](https://egg-sell-nt.s3-eu-west-1.amazonaws.com/media/photos/test/farms.png) Farm view |  Passed |
| 8 |  Logout | Clicking on Logout | ![Shop](https://egg-sell-nt.s3-eu-west-1.amazonaws.com/media/photos/test/shop.png) Shop view| ![Logout success](https://egg-sell-nt.s3-eu-west-1.amazonaws.com/media/photos/test/logged_out_success.png) Logout success|  Passed |

#### Browser Compatibility test

| Nr | Browser         | Image  | Test result |
| ---|:-------------:| :---------------: | :-----:|
| 1 | Chrome | ![Chrome](https://egg-sell-nt.s3-eu-west-1.amazonaws.com/media/photos/test/chrome.png) Chrome | Passed |
| 2 | Safari | ![Safari](https://egg-sell-nt.s3-eu-west-1.amazonaws.com/media/photos/test/safari.png) Safari| Passed |
| 3 | Firefox | ![Firefox](https://egg-sell-nt.s3-eu-west-1.amazonaws.com/media/photos/test/firefox.png) Firefox | Passed |



#### Code Validation

* CSS was validated using W3C CSS Validation Service - Jigsaw

* HTML was validated using W3C Markup Validation Service.

* Python code was validated using PEP8 online checker.

#### Defensive design

* Warning messages were used when user entered already taken username at registration, or wrong password/username when signing in.

[Back to Top](#table-of-contents)

### Credits

#### Acknowledgements

[Back to Top](#table-of-contents)

### DEPLOYMENT

#### Deployment to Heroku

The following steps were taken in order to deploy this site to Heroku:

1. Created a new app in `Heroku` with a unique name, chose my region

2. Went to `Resources`, within Add-ons searched `Heroku Postgres`, chose Hobby Dev - Free version, then clicked Provision button.

3. In Settings clicked on `Reveal Config Vars` button, and copied the value of `DATABASE_URL`

4. Returned to terminal window and run `sudo pip3 install dj_database_url`

5. Also did `sudo pip3 install psycopg2`

6. Went to `settings.py` and added `import dj_database_url` and updated `DATABASES = {'default': dj_database_url.parse(os.environ.get('DATABASE_URL'))}` 

7. I run `python3 manage.py makemigrations`, then `python3 manage.py migrate` to migrate all existing migrations to postgres database.

8. I created a superuser: `python3 manage.py createsuperuser`

9. Returned to `Heroku`. In `Settings` clicked on `Reveal Config Vars` button, and added all the following config vars from `env.py`:

| Key         | Value | 
|:-------------:| :----: | 
|  AWS_ACCESS_KEY_ID | secret key here  |
|  AWS_SECRET_ACCESS_KEY | secret key here |
|  DATABASE_URL | secret key here |
|  DISABLE_COLLECTSTATIC| 1 |
|  SECRET_KEY | secret key here |
|  STRIPE_PUBLISHABLE | secret key here |
|  STRIPE_SECRET| secret key here |

10. Clicked to `Deploy`, then `GitHub`, searched for my repository and clicked to `Connect` button.

11. Logged in to `Amazon AWS`, went to `S3` and created a new `S3` bucket. 

12. Returned to terminal window and run `sudo pip3 install django-storages` and `sudo pip3 install boto3`. Went to `settings.py` and added `storages` to `INSTALLED_APPS`.

13. Also in `settings.py` the following lines are added:

AWS_S3_OBJECT_PARAMETERS = {
    'Expires': 'Thu, 31 Dec 2099 20:00:00 GMT',
    'CacheControl': 'max-age=94608000'
}

AWS_STORAGE_BUCKET_NAME = 'egg-sell-nt'
AWS_S3_REGION_NAME = 'eu-west-1'
AWS_ACCESS_KEY_ID = os.environ.get("AWS_ACCESS_KEY_ID")
AWS_SECRET_ACCESS_KEY = os.environ.get("AWS_SECRET_ACCESS_KEY")

AWS_S3_CUSTOM_DOMAIN = '%s.s3.amazonaws.com' % AWS_STORAGE_BUCKET_NAME

14. Updated `env.py` with `AWS` keys (they are from`S3`)

15. Created `custom_storages.py` at the top level:

from django.conf import settings
from storages.backends.s3boto3 import S3Boto3Storage


class StaticStorage(S3Boto3Storage):
    location = settings.STATICFILES_LOCATION

class MediaStorage(S3Boto3Storage):
    location = settings.MEDIAFILES_LOCATION

16. Went to `settings.py` and added:

STATICFILES_LOCATION = 'static'
STATICFILES_STORAGE = 'custom_storages.StaticStorage'

MEDIAFILES_LOCATION = 'media'
DEFAULT_FILE_STORAGE = 'custom_storages.MediaStorage'

17. Returned to terminal window and run `python3 manage.py collectstatic`

11. And also run `sudo pip3 install gunicorn`

12. Created a requirements.txt file using the terminal command `pip3 freeze > requirements.txt`

13. Created a `Procfile` using the following command: `echo web: gunicorn ms4.wsgi:application`

14. Ran `git add .`, `git commit -m "my commit message"` and `git push` commands to push all changes to my GitHub repository.

15. Returned to `Heroku` and hit `Deploy Branch`

16. Once the build is complete, click on `Open app`

17. Went to `settings.py` and added `egg-sell-nt.herokuapp.com` to `ALLOWED_HOSTS`

18. Ran `git add .`, `git commit -m "my commit message"` and `git push` commands to push all changes in `settings.py`to my GitHub repository.


### Disclaimer

This project was created for educational use only.

[Back to Top](#table-of-contents)






I attended Python django dev to deployment course by Brad Traversyon on Udemy, I used his solution for message alert.
https://www.udemy.com/course/python-django-dev-to-deployment/


W3C errors:
 The value of the for attribute of the label element must be the ID of a non-hidden form control.


 farm.html {% else $}