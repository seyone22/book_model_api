# How to run

Run the API Server using the following commands.
First, activate the virtual environment using,
<br>
``.\venv\Scripts\activate``

Then, install necessary modules.
<br>
``pip install -r .\requirements.txt``

Then run the server using,
<br>
``flask run``


# What this server does

This server has one API route, ``/predict``. This route
is for getting recommendations based on the given book
title. The names must be from the dataset goodbooks-10k.

Working on extending it to a custom dataset, and running
a check to see if the name is within the database before
running the recommender.

# Dependencies

Please check ``requirements.txt`` for a full list of
dependencies. Of course, you need ``Python 3.11`` to run
the server. I tested on ``Python 3.11.8``