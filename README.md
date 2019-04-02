# Kirr27 - URL Shortener

A Django-powered URL Shortening Service.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

You should have Python3 and virtual environment installed on your computer.
Install Python3 from https://www.python.org/
 and then install virtual enviroment as shown below.

```
pip install virtualenv
```

### Installing

First Clone this project to your PC.

```
git clone git@github.com:MohammadFraz/URL-Shortener.git
```
then go into that directory and install the requirements.
```
cd URL-Shortener
pip install -r requirements.txt
```
Then create a super user
```
python manage.py createsuperuser
```
Fill the name,email and password and then runserver
```
python manage.py runserver
```

Then you are good to go.

## License

This project is licensed under the MIT License

## Acknowledgments

* CodingForEntrepreneurs
* Django documentation
