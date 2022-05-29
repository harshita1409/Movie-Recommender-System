# Content-Based-Movie-Recommmeder-System
[Link to the App](https://mrs-hg.herokuapp.com/) | [Video Demo](https://youtu.be/CApfJiCorLM)




## About the Project
- Movie-Recommender-System Porject built during Microsoft Engage 2022 Program.
- It is a content based movie recommender system.
- It recommend items to the user by using the similarity of items.
- It identifies the similarity between the movies based on their descriptions, genre, director, etc.
- The details o the movies (title, genre, poster, etc) are fetched using an API by [TMDB](https://www.themoviedb.org/documentation/api) and using the IMDB id of the movie in the API.


### Salient Features
- It will recommend TOP 5 most similar movies with respect to the searched movie.
- Not only movie names will going to display after hitting then "Recommend" button, respective movie poster will also get displayed.
 


### Build With
- Framework - Streamlit 
- API - TMDB
- Frontend - Streamlit Lib
- IDE - PyCharm
- Language - Python(3.10)
## Agile Methodology
### What is Agile?
- Algile is a methodology which promotes a flexible way to manage a project by breaking it up into several phases, it is adopted today in the software industry.
- The most popular example of Alile methodology are Scrum, eXtreme Programing (XP) ,etc.

### How I Incorporated Agile Methodology During My Project
According to the SCRUM, it provides an iterative model where planning is performed on a very short term. The basic time working unit is sprint.

- Sprint 1 (May 4): Sprint Planning, Research and Documentation- Researching about all the 3 categories of projects, trying to find out the basic requirements. Initially i decided to go for the Face Recognition one for Attendance Tracking System, then I moved on to the Algorithms and finally started searching for recommmendation systems.
- Sprint 2 (May 11): Sprint Design- After finalising the Recommendation System, I decided to build a Movie Recommender System. I searched for tutorials, blogs on medium, etc. started analysing them and designed a LLD (Low Level Design).
- Sprint 3 (May 18): I used Jupyter Notebook for a JSON document, containing ordered list of input/output cells which contain code, text, etc. & ends with ".ipynb" extension. Get done with the source code by simultaneously resolving the in between errors at the runtime.
- Sprint 4 (May 25): Adapting the working of PyCharm IDE, starting from setting up the virtual environment till the deployment procedure on Heroku. Finally I decided to use the Streamlit Framework after so many research work. Then I connected the notebook to the front-end and made it responsive.

#### Note
Follow the "Getting Started" section, incase if you see application error in the above mentioned URL.
## Getting Started
To install and run the project on your local system, following are the requirements:

### Prerequisites
Get your API, by following the below steps:

- Create an account in https://www.themoviedb.org/ .
- Click on the ```API``` link from the left hand sidebar in your account settings and fill the details to apply for API key.
- If you are asked for the website URL, just give 'NA' if you do not have one.
- You will see the API key in your ```API``` sidebar once your request is approved.
## How To Run The project
- Clone or download this Repository to your local machine.
- Install all the Libraries mentioned in the requirement.txt file, by running the following command
```bash
  pip install -r requirements.txt
```
- Get your API key from https://www.themoviedb.org/ by logging into your account.
- Replace the api key = ' ' in line no. 7 of  ```app.py``` file and save it.
- Open your terminal/command prompt from your project directory and run the below mentioned command.
```bash
  streamlit run app.py
```
- It automatically open the streamlit app on your default browser, or you can also view it through the Local URL link which is there your terminal/cmd prompt.
- Yeah! Finally you are done.
- Now you can easily get the Top 5 most similar movies according to your search, by clicking on the reocmmend button.
- That's it!
