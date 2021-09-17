## 1MINPITCH <div dir="rtl">17.09.2021</div>
#### <div dir="rtl">By **Mark Muchiri Macharia**</div>
## Description
This is an application that allows users to use that one minute wisely. The users will submit their one minute pitches and other users will vote on them and leave comments to give their feedback on them.
## Deployed website 
This app is live @  

## Prerequisites
* Pip
* Flask
* Postgres
* python3.6

## How it works 
As a user of this web app you will be able to:

1. Create an account
2. Log in
3. See all submitted pitches arranged in categories 
4. Add a pitch based on category
5. Upvote or downvote a pitch
6. Comment on a pitch
7. See comments posted on each individual pitch
<!-- 8. Edit your profile i.e will be able to add a short bio about yourself and a profile picture -->

## Behavior driven devlopment (BDD)

| Behavior            | Input                         | Output                        | 
| ------------------- | ----------------------------- | ----------------------------- |
| View Product Pitches | Click on any category | Taken to the clicked category | Click on `Click Here To Post A Pitch` | Redirected to the login page | Signs In/ Signs Up |
| Click `'Click Here To Post A Pitch'` | If logged in, display form to add a pitch | Redirected to the home page |
| Click upvote/ downvote button | Redirects to home page | Upvote/ downvote count changes | Click add comment button | Redirects to the comment page | Displays a comment form | Click on Sign Out | Redirects to the home page | Signs user out |
| Click on profile | Redirects to the profile page | User adds bio and profile picture |

## Running the Application
* Install virtual environment using `$ python3.6 -m venv --without-pip virtual`
* Activate virtual environment using `$ source virtual/bin/activate`
* Download pip in our environment using `$ curl https://bootstrap.pypa.io/get-pip.py | python`
* Install all the dependencies from the requirements.txt file by running `python3.6 pip install -r requirements.txt`
* Create a `start.sh` file in the root of the folder and add the following code:

        export MAIL_USERNAME=<your-email-address>
        export MAIL_PASSWORD=<your-email-password>
        export SECRET_KEY=<your-secret-key>

* Edit the configuration instance in `manage.py` by commenting on `production` instance and uncommenting `development` instance
* To run the application, in your terminal:

        $ chmod a+x start.sh
        $ ./start.sh

## Known Bugs
No known bugs.

## Technologies Used
* Html
* Bootstrap 
* javascript
* awesome & google fonts

## Support and contact details
For feedback contact me through;
* mark.macharia@student.moringaschool.com
* 0759329269

### License
[MITlicense](LICENSE) 2021 **MARK MUCHIRI MACHARIA**

[![License](https://img.shields.io/github/license/mattlisiv/newsapi-python.svg)](https://github.com/mattlisiv/newsapi-python/blob/master/LICENSE.txt)
[![PyPI](https://img.shields.io/pypi/v/newsapi-python.svg)](https://pypi.org/project/newsapi-python/)
[![Status](https://img.shields.io/pypi/status/newsapi-python.svg)](https://pypi.org/project/newsapi-python/)
[![Python](https://img.shields.io/pypi/pyversions/newsapi-python.svg)](https://pypi.org/project/newsapi-python)