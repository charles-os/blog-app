
# Pitch

## Description
This is  a personal blogging website where you can create and share your opinions and other users can read and comment on them. 
### By Charles Osoro 

### Prerequisites
* python3.7
* pip
* Virtual environment(virtualenv)
* Flask-Mail
* PostgreSQL

## Cloning and running
Clone the application using git clone(this copies the app onto your device). In your terminal:

```  $ git clone https://github.com/charles /blog-app/```
  
  ```  $ cd blog-app```

## Creating the virtual environment

  ```  $ python3.7 -m venv --without-pip virtual```
  
  ```  $ source virtual/bin/env```
  
  ```  $ curl https://bootstrap.pypa.io/get-pip.py | python```

## Installing Flask and other Modules

  ```  $ python3.6 -m pip install Flask```
  
  ```  $ python3.6 -m pip install Flask-Bootstrap```
  
  ```  $ python3.6 -m pip install Flask-Script```
  
  ```  $ python3.6 -m pip install Flask-Mail```

## Testing the Application
To run the tests for the class files:

  ```  $ python3.7 manage.py test```


## Behaviour driven development/ Specifications
| Behaviour    | Input     | Output|
| :------------ | :------------- |:---------|
|   Blog Post     |     Blog is saved in a database | Post from database|
|Comment on the blog post|Leave a comment| Comment saved for display|

|Login and authenticate|Email address and password|Saved and used for authentication|




## Support and contact details
Feel free to reach out to the developer at:

* Email: chaloo56@gmail.com
## License
MIT License Copyright (c) {2019} Charles Osoro 