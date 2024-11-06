# Django-Video_Subtitles
Django video subtitle Extraction, extracts all the available subtitle streams available from a video using `ffmpeg`, also lets you search the subtitles(eng) and skips to that timestamp.

## To run the project
Clone the repository into your local system.

- Open cmd and enter :

`git clone https://github.com/theflameguy/Django-project-.git`

![git clone command image](Screenshots/Cloning%20repo.PNG)

- Use Docker to run the prject on your local host

(make sure you are in the Django-project-  directory if not (`cd Django-project-`))

`docker-compose up`

<hr/>


## If docker command doesn't work (alternate method):

- pip install all the required libraries

`pip install -r requirements.txt`

![git clone command image](Screenshots/install%20requirements.PNG)

- Run Server

`py manage.py runserver`

![git clone command image](Screenshots/Run%20server.PNG)

then go to this url -> `localhost:8000/videos/upload`

Link should navigate to:

![git clone command image](Screenshots/Screenshot%20(20).png)


To preview the project check the Video available in the Screenshots folder






