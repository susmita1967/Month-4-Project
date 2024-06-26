# Month-4-Project
# Hotel Booking Website

This project is a full-stack hotel booking website developed using React for the frontend and Express.js for the backend. The backend server is connected to a PostgreSQL database and serves data through a GraphQL API.


## Technologies Used

### Frontend
- The frontend components are located in src folder.
- React
- CSS/HTML

### Backend

- Express.js
- PostgreSQL
- GraphQL
- Sequelize (ORM)

## Running the Backend Server

1. Ensure your PostgreSQL database is running.
2. Update the database configuration in backend/config/config.json if necessary.
3. Run the server:

bash
cd backend
npm run postgresqlApp.js


The backend server will be running at [https://localhost:3000/graphql](https://localhost:3000/graphql).

## Running the Frontend App

npm start


The frontend app will be running at [http://localhost:3000](http://localhost:3000).

## Project Structure


hotel-booking-website/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── schemas/
│   └── postgresqlApp.js
├── src/
│   ├── components/
│   ├── graphql/
│   |── App.js
│   └── package.json
└── README.md

 
 
