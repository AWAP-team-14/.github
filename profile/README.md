# GoParcel Delivery Service
## Description of What the Project is About: 
The project aims to develop a comprehensive web application that simulates an parcel delivery system, similar to the ones operated by postal services in Finland. It includes a GUI application for consumers, a GUI application for delivery drivers, a touchscreen simulator for parcel lockers, and a backend application for a parcel generator robot. The key functionalities covers user authentication, parcel information tracking, notifications, account management, parcel sending, and interactions for both consumers and drivers. The project also includes a parcel locker touchscreen simulator and a backend script for parcel generation. Common features involve a responsive UI, data storage, deployment, email notifications, and multiple parcel locker locations.
## Description of How the Project Has Been:
The project follows a structured approach, incorporating React for the frontend and Node environment and Express.js for the backend. The team utilized a kanban process model on GitHub, regular task completion, weekly status meetings, and an updated Kanban board. GitHub version control and project management tools were actively used for collaboration and version tracking. The team followed effective communication, meeting deadlines, feedbacks from the tutor and responsible contributions.
## Description of Technologies Used in the Project: 
Our application is built for a seamless user experience. The frontend, created with React, ensures a responsive interface. The backend, powered by Node environment and Express.js which handles HTTP requests. We used MongoDB for smooth data processing and storage. Our deployment is done through Microsoft Azure, managing the deployment process and running intelligent logic for automatic parcel creation using a robot. The development process is conducted in Visual Studio Code which provides a user-friendly and productive IDE experience.


## Project Team Members and Roles:
### Frontend Developers (React): Md Junayedur Rahman Bhuiyan, Dinit Subedi & Salendra Yadav
- Responsible for creating GUI applications for consumer, driver and the parcel locker touchscreen simulator.
### Backend Developers (Express.js): Md Junayedur Rahman Bhuiyan and Sushan Maharjan
- Tasked with implementing backend logic for the consumer application, driver application, touchscreen simulator, parcel creating robot and handling the database. 

## Describe at Least Two of These: The Architecture of the Application, Database Structure, Interface Description, UI Plan.
1. Architecture of the Application:
The application follows a client-server architecture, where the frontend (React) serves as the client, interacting with the backend(Express.js) through HTTP requests and the server interacts with the database which is MongoDB that manages data storage.
2.	Database Structure:
The database structure comprises data collection for consumer, parcel information, parcel history, parcel lockers, and driver. Relationships are established between data collection to maintain data integrity.Each consumer has their name, email, mobile number, and password. The parcel contains information about parcel dimensions and the sender and the recipient information and its status. Each parcel locker has a set of cabinets, and each cabinet is associated with specific parcel information. The structure allows efficient retrieval of user-specific parcel histories and real-time updates for drivers regarding available cabinets.

## A link to a working application on the public internet
1. Link to the Consumer website: [https://kind-ground-058b85803.4.azurestaticapps.net](url)
2. Link to the Driver application:[ https://lively-cliff-02b135203.4.azurestaticapps.net/](url)
3. Link to the Touch-screen application: [https://icy-coast-0bfa97f03.4.azurestaticapps.net](url)
4. Link to the GitHub and source file for the application: [https://github.com/orgs/AWAP-team-14/repositories](url)

## How to install and use the application
1.	Clone all the 4 repositories on the local machine. 
2.	Install the necessary dependencies using “npm install” on each of the repositories.
3.	Run the repository using the command “npm start”.

