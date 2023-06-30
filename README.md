
# Hackathon Dashboard

## Project Aim

The main objective of this project is to create and implement a live scoreboard system for a hackathon. The system should include various components necessary for the live scoreboard functionality. It should allow adding, editing, and removing teams from the scoreboard, as well as updating team points. Additionally, it should be user-friendly and require minimal maintenance after the hackathon teams have completed their competition and a reset is needed.

### Scoreboard Component

To fulfill the project requirements, a scoreboard module needs to be integrated into the existing cyber range, as it currently lacks this functionality. This component is a crucial part of the project and encompasses the following elements:

- Website
- Database
- Hosting Server

### Expected Deliverables

The expected deliverable is a fully functional live scoreboard that enables adding, modifying, and editing participating teams in the hackathon. The system should be easy to maintain.

## Running the application

The application consists of two main components: the web app and the MySQL database. The web app utilizes Next.js for both the frontend and the backing API. Docker Compose is used to orchestrate the entire application, making it incredibly convenient for local development setup. To start the application locally, you just need to execute the command `docker compose up`. This command will initiate a MySQL container and launch the web app in a separate container. The networking between these two containers is configured within the docker compose file.




