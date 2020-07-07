# Todo-app
TODO-APPLICATION

Todo django application 

I’ll assume you have Django installed already. You can tell Django is installed and which version by running the following command in a shell prompt (indicated by the $ prefix):

$ python -m django --version


If Django is installed, you should see the version of your installation. If it isn’t, you’ll get an error telling “No module named django”.


From the command line, cd into a directory where you’d like to store your code, then run the following command:

$ django-admin startproject mysite

This will create a mysite directory in your current directory. If it didn’t work, see Problems running django-admin.

The latest and greatest Django version is the one that’s in our Git repository (our revision-control system). This is only for experienced users who want to try incoming changes and help identify bugs before an official release. Get it using this shell command, which requires Git:

$git clone https://github.com/django/django.git



The development server:
Let’s verify your Django project works. Change into the outer mysite directory, if you haven’t already, and run the following commands:

$ python manage.py runserver

You’ll see the following output on the command line:

Performing system checks...

System check identified no issues (0 silenced).

You have unapplied migrations; your app may not work properly until they are applied.
Run 'python manage.py migrate' to apply them.

July 03, 2020 - 15:50:53
Django version 3.0, using settings 'mysite.settings'
Starting development server at http://127.0.0.1:8000/


Quit the server with CONTROL-C.


Getting runtime help.
$django-admin help
Run django-admin help to display usage information and a list of the commands provided by each application.

Run $django-admin help --commands to display a list of all available commands.

Run $django-admin help <command> to display a description of the given command and a list of its available options.


Setup:
What you need for a basic Django dev environment:

Python 2.7.x or 3.4.x
1. easy_install and Pip
2. Git
3. virtualenv
4. Django
5. Database (SQLite, MySQL, PostgreSQL, MongoDB, etc.)
6. South (for Django versions prior to 1.7)
7. Text editor (Sublime, vim, Komodo, gedit,pycharm,vs code)



Install virtualenv with the following command:

$ pip install virtualenv


DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.sqlite3',
        'NAME': os.path.join(BASE_DIR, 'db.sqlite3'),
    }
}

RUN THE COMMAND TO SEE ALL FEATURES OF DJANGO:


$django-admin
[django]
    check
    compilemessages
    createcachetable
    dbshell
    diffsettings
    dumpdata
    flush
    inspectdb
    loaddata
    makemessages
    makemigrations
    migrate
    runserver
    sendtestemail
    shell
    showmigrations
    sqlflush
    sqlmigrate
    sqlsequencereset
    squashmigrations
    startapp
    startproject
    test
    testserver
    
Note that only Django core commands are listed as settings are not properly configured (error: Requested setting INSTALLED_APPS, but settings are not configured. You must either define the environment variable DJANGO_SETTINGS_MODULE or call settings.configure() before accessing settings.).


![USERVIEW](https://user-images.githubusercontent.com/50301680/86800811-0b43b900-c091-11ea-958d-c28e7a20a127.png)


![UPDATETASK](https://user-images.githubusercontent.com/50301680/86800934-26162d80-c091-11ea-9c7b-1ddfaa7a9aa8.png)



![DELETE TASK](https://user-images.githubusercontent.com/50301680/86800990-33331c80-c091-11ea-96b0-bbb3a02f6957.png)

License

This project is licensed under the MIT License.


Author:  SHIVANT KUMAR PANDEY

EMAIL: shivant47@gmail.com

LinkedIN: https://www.linkedin.com/in/shivant-kumar-pandey-6469a1164/



