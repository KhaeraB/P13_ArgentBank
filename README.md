# P13_ArgentBank API

- ![Author](<https://img.shields.io/badge/Author-Khaera Belkadi-">)
- ![GitHub repo size](<https://img.shields.io/github/repo-size/KhaeraB/P13_ArgentBank>)  
- ![GitHub top language](https://img.shields.io/github/languages/top/KhaeraB/P13_ArgentBank)
- ![GitHub language count](https://img.shields.io/github/languages/count/KhaeraB/P13_ArgentBank)


This codebase contains the code needed to run the backend for Argent Bank.

## Getting Started

### Prerequisites

Argent Bank uses the following tech stack:

- [Node.js v12](https://nodejs.org/en/)
- [MongoDB Community Server](https://www.mongodb.com/try/download/community)

Please make sure you have the right versions and download both packages. You can verify this by using the following commands in your terminal:

```bash
# Check Node.js version
node --version

# Check Mongo version
mongo --version
```

### Instructions

1. Fork this repo
1. Clone the repo onto your computer
1. Open a terminal window in the cloned project
1. Run the following commands:

### Project setup

- Clone this repo on your computer:

````bash
git clone https://github.com/KhaeraB/P13_ArgentBank
````

- Package installations after cloning.

```bash
# with NPM
cd front-end && npm install && cd..    
cd backend && npm i && cd..     

# with YARN
cd front-end && yarn && cd..    
cd backend && yarn && cd..   

# Start local dev server
npm run dev:server

# Populate database with two users
npm run populate-db
```

Your server should now be running at http://locahost:3001 and you will now have two users in your MongoDB database!

## Populated Database Data

Once you run the `populate-db` script, you should have two users in your database:

### Tony Stark

- First Name: `Tony`
- Last Name: `Stark`
- Email: `tony@stark.com`
- Password: `password123`

### Steve Rogers

- First Name: `Steve`,
- Last Name: `Rogers`,
- Email: `steve@rogers.com`,
- Password: `password456`

## API Documentation

To learn more about how the API works, once you have started your local environment, you can visit: http://localhost:3000/swagger


### Added dependencies

  "@reduxjs/toolkit": "^1.9.0",
    "@testing-library/jest-dom": "^5.16.5",
    "@testing-library/react": "^13.4.0",
    "@testing-library/user-event": "^13.5.0",
    "axios": "^1.1.3",
    "react": "^18.2.0",
    "react-bootstrap": "^2.6.0",
    "react-dom": "^18.2.0",
    "react-icons": "^4.6.0",
    "react-redux": "^8.0.5",
    "react-router-dom": "^6.4.3",
    "react-scripts": "5.0.1",
    "redux-devtools-extension": "^2.13.9",
    "redux-persist": "^6.0.0",
    "sass": "^1.56.1",
    "styled-components": "^5.3.6",
    "swagger-ui-react": "^4.15.5",
    "web-vitals": "^2.1.4"    

---
   



