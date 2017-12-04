# Team Starboard Website
**Front-End Website for a leading watersports brand to increase B2B**

This Website is a Code Institute stream 1 projet. Starboard ia a world leading watersports brand with over 100+ Athletes, Brand Ambassadors and Representives globally. This websites main goal is to give each athlete a profile and for other brands to work together with Starboard.

**Follow this link to view deployed version of the web app https://com-peterkosinski-tddashboard.herokuapp.com/#**

##Prototyping

Wireframing the funtionality and outline of the project. Wireframe available here: 

## Built with 
1. HTML 5
2. CSS 3
3. Bootstrap
4. JavaScript (W3 Classes)

## Components

## Athlete Profile Page


## Bootstrap

Using bootstrap to create a responsive home page 

## Deployment / Hosting

This Application was deployed and is hosted on Heroku - gunicorn Python package runs the http server for the app, the Procfile gives Heroku the information to run the app and requirements.txt is a file that conains all the Python packages (pip installs) required to run the app. mLab MongoDB was chosen to host the dataset on the server.

## Installation

Follow the below instructions to get this project up & running on Mac (commands will be slightly different for Windows)

1. Download MongoDB & Robomongo
2. Go to folder you want to put the cloned project in your terminal & type:
    'https://github.com/PeterKosinski/herokudash.git'
3. Create & Activate a new Virtual Environment in terminal:
    Create: `$ python3 -m venv ~/virtualenvs/name_of_environment`
    Activate: `$ source ~/virtualenvs/name_of_environment/bin/activate`
4. Install the project dependancies:
    `$ pip install -r requirements.txt`
5. Get Mongod running
    `$ mongod --config config/mongoConfig.conf`
6. Open the folder in vscode and use the internal Terminal 
7. Navigate to the 'threatened_species.py', right click and select 'Run python file in terminal'
8. You should see it running below - go to your browser and type '127.0.0.1:5000' into the address bar and the application should appear


## Testing
This Application was tested across a range of browsers
