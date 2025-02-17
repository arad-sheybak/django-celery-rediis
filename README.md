Django Celery Redis Email Sender

Overview

***This is an open-source Django project that implements Celery and Redis to handle asynchronous email sending. The project demonstrates how to configure Celery with Redis as the message broker and execute background tasks efficiently.***

Features:

**1- Asynchronous email sending using Celery**

**2- Redis as the message broker**

** Django integration with Celery**

** Poetry for dependency management**

**Prerequisites:**

Ensure you have the following installed before proceeding:

**1- Python (>=3.9)** 
 you can download latest version on python from this link based on your OS : https://www.python.org/downloads/

 **2- Poetry**

***Poetry Installation:***

    1- Make sure you have Python (>=3.9) installed on your system.

    2- Open CMD (Command Prompt) as Administrator.

    3- Run the following commands:

        pip install poetry 

        pip install poetry-plugin-shell

    **Use the following command to enable a virtual environment with Poetry:**

        poetry shell

Now Poetry is installed.

**Lets to create the Django project:**

For creating Django Project using Poetry follow the below steps:

1- open your IDE (in this case im using VSCode) and then open Terminal, then run the following commands:

``` poetry init --no-interaction```

*** poetry init used to create a toml file from project structure and dependencies, This command creating the pyroject.toml file, if you open the file you can see the structure and details of your project.***

2- install Django: 

``` poetry add django```

3- install Celery:

```poetry add celery```

4- install Redis

```poetry add redis```



