# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
 

For setting up oour local environment, we would need Docker to be installed,

1) For windows installation:

    Go to this website : https://docs.docker.com/desktop/install/windows-install/

   For Mac installation :

    Go to this website : https://docs.docker.com/desktop/install/mac-install/


2) Check out the system-requirements for installing Docker
    
    - Make sure you have windows 10 or higher installed
    
    - Make sure you have Hyper-V enabled ( just open  Task Manager and click on CPU, in the lower-right corner of the box you may see than virtualization is enabled, _for windows this is generally enabled and if you have manually disabled it, revert it back_ )

    - Make sure you have 64-bit processor and 4GB ram along with BIOS-level hardware

    - Now download and install Docker from the link provided in the URL

3) After the file has been downloaded, click on the file and install Docker

4) Installation process is quite easy, you just have to go through a general installation rules ( click on a couple of buttons )

    - Here after installation, you might be prompted to close to dialog box and log out of your computer, essentially just to restart it, kinda
    - Do as it is said and you will be fine 

5) After Docker Desktop has been downloaded and installed, open the Command Prompt
    
    - Type in : *docker -v* and *docker-compose -v* ( this commands tell you the version if Docker installed in your system )
    
    - In your command prompt terminal, navigate to your cloned repository

    - Type in : *docker-compose up* , ( this will load up the backend and frontend of Anythink )

    - Now docker will take a couple of minutes of load up

5) After it has loaded up, navigate to this website : http://localhost:3000/api/ping to test if the backend is running and it should be able to connect to your database

6) After checking the backend, it is time to check the frontend.

    - Go to this website and create a new user : http://localhost:3001/register
    You should be able to clear view the webpage and you may create a new user with any username and password


*CONGRATS, you have successfully set up you environment*
