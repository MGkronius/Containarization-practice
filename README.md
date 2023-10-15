# Containarization-practice
Creating multi-container environment for practicing

Python application that connects to a database that is set to mysql.
When the application runs, it asks us to provide an id and returns the number corresponding to the specific id. Attention, there are only 5 records with id from 1-5.
You should unzip the folder I've, open a command prompt and go into the unzipped folder named "ergasia" which contains the yml file.

Then you should run the following commands (you first need to install docker:
docker-compose up -d

docker exec -it my_app_2 python ./app.py

The app will run and you will be asked for an id. For example, if you type 1, it will return 20 and Hello world.

In the other folder inside the compressed file ("my_app" folder), it contains what was needed to create the image.
