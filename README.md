
# django-todo
A simple todo app built with django

![todo App](https://raw.githubusercontent.com/shreys7/django-todo/develop/staticfiles/todoApp.png)
### Setup
Firslty clone this repository.
To get this repository, run the following command inside your git enabled terminal
```bash
git clone https://github.com/sha-lik/Django-Todo-App.git
```

After this you have to install Docker to deploy your todo-app in just a few docker commands.

Once you installed Docker, simply go into your cloned git repo and run some commands to deploy your Todo-App:
```
docker build . -t todo-app
docker run -d -p 8000:8000 todo-app
```
Here we are porting this app to port 8000 but you can change it according to  your preference.

Once the server is hosted, head over to http://ip:8000 for the App.

Here you have deployed your todo-app in a very simple way :)

