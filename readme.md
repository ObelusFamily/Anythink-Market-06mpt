# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup


<strong>Step 1:</strong><br/>
Great! Now that you are here,let's understand how to setup and run the repo on your machine.<br />
click the "Green" button on the repo as shown below. Clone repository on your local system.<br /><br />

![Screenshot (760)](https://user-images.githubusercontent.com/104644392/189362785-83a101f7-e4c2-4339-960d-51af6b178fec.png)<br/><br/>


<strong>Step 2:</strong><br/>
If you have successfuly cloned the repository, great! if not please follow the above step carefully and come back to step 2. <br/>
Now we want to run the application locally. To run the repo locally we will need 'Docker'. it will make it easier for us to run things locally.<br/>

To install docker on your machine, follow this link - <a href="https://docs.docker.com/get-docker/" target="_blank">Install Docker</a>

<br /><br/>

<strong>Step 3:</strong> <br/>
Great! You have successfully installed docker. <br />

You can <strong>verify</strong> if docker is ready by running the following commands in your terminal: <strong> "docker -v"</strong> and <strong>'docker-compose -v'</strong> <br/><br/>
Then, run <strong>"docker-compose up"</strong> from the project root directory to load This repo's backend and frontend.<br/><br/>
If Docker is working correctly, the backend should be running and able to connect to your local database.<br/>
Let's test this by pointing your browser to -  http://localhost:3000/api/ping <br/><br/>

<strong>Step 4:</strong> <br/>
Now, it’s time to check the frontend and make sure it’s connected to the backend.<br/>
If everything is working properly, you’ll be able to create a new user on - http://localhost:3001/register <br/>
Create a new user account. <br/><br/>

<strong>NOTE :</strong> <br/>
Just make sure that you run all scripts in the next quests on one of the containers created by <strong>"docker-compose up"</strong>. <br/>
Also, you can use <strong>"docker exec"</strong> to run commands on a running container.

