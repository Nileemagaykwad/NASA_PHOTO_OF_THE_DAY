This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

######################### DOCKER COMMANDS ######################################

### to run with docker 

Building your image
## `docker build -t nasa-apod .`

Run the image
## `docker run -p 8000:3000 nasa-apod-1`

print the output of app 
## `docker ps`

this can be used to know container id and ports. 
for example ports comes as `0.0.0.0:8000->3000/tcp` then the app will be live at `http://localhost:8000/`

to run through Docker-compose ------------

to build with docker-compose
## `docker-compose build nasaimage'

here nasaimage is name of service that should be build

to start the container with docker-compose 
## `docker-compose up nasaimage`

it should enable to access our application from http://localhost:3000 just like we normally would for a create-react-app instance!

