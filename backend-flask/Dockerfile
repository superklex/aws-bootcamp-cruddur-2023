FROM python:3.10-slim-buster

# this action runs inside the container
# make a new folder in the container
WORKDIR /backend-flask

# this action runs outside the container but comes from the container
# installs libraries needed to run the app
COPY requirements.txt requirements.txt

# this acction runs inside the container
# it installs the python libraries used for the app
RUN pip3 install -r requirements.txt

#  this action runs outside the containcer but comes from the container
# first . means /backend-flask outside the continer
# second . means /backend-flask inside the container
#  so this line copies everything from outside into the container
COPY . .

# actions runs inside the containers
# set environment variable (envars)
# environment remains set when container is running
ENV FLASK_ENV=development

EXPOSE ${PORT}

# command to run python(python3) using the flash module(-m flask)
# cd backend-flask
# export BACKEND_URL="*"
# export FRONTEND_URL="*"
# run python3 -m flask run --host=0.0.0.0 --port=4567
# change url to http://localhost:4567/api/activities/home
CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0", "--port=4567"]


# docker run --rm -p 4567:4567 -it -e FRONTEND_URL='*' -e BACKEND_URL='*' backend-flask
# docker build -t  backend-flask ./backend-flask
