# pitches-web

## Author
Omar Abdirahman Hussein

## Description
This is a flask application that allows users to post one minute pitches and also allows other users who have signed up to comment and upvote or downvote a pitch. It also allows a person to signup to be able to access the functionalities of the application.

## User Story

1. Comment on the different pitches posted py other uses.

2. See the pitches posted by other uses.

3. Vote on s pitch they have viwed by giving it a upvote or a downvote.

4. Register to be allowed to log in to the application.

5. View pitches from the different categories.

6. Submit a pitch to a specific category of their choice.

## App Installation

To get the code..

Cloning the repository:

  https://github.com/omarion3698/pitches-web.git

Move to the folder and install requirements

  ######cd pitches-web

  ######pip install -r requirements.txt

Exporting Configurations

  ######export SQLALCHEMY_DATABASE_URI=postgresql+psycopg2://{User Name}:{password}@localhost/{database name}

Running the application

  ######python3.8 manage.py server

Testing the application

  ######python3.6 manage.py test

Open the application on your browser 127.0.0.1:5000.
