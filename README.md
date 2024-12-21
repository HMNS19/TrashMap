
# TrashMap- Smart Waste Management Solution

## Overview
TrashMap is a smart solution designed to optimize waste disposal by identifying and clearing blackspots and dustbins. Our platform allows users to locate and report nearby dustbins or illegal littering spots (blackspots) through a website. We aim to enhance public awareness and participation in waste management while promoting a cleaner and greener environment.

## Demo

https://trash-talk.netlify.app/login.html

## Key Features
- **Real-Time Geolocation**: 
  - Utilizes GPS to display the nearest available dustbins to users.
  - Encourages proper waste disposal by guiding users to designated disposal sites, reducing littering and promoting cleaner environments.

- **Black Site Reporting**: 
  - Users can report "black sites" or locations where garbage accumulation is common, such as illegal dumping areas or overflowing bins.
  - Alerts local authorities or waste management teams, enabling swift action to clean these areas and prevent further waste build-up.

- **Garbage Pickup Scheduling**: 
  - Allows users to schedule garbage pickups from their homes or businesses, reducing the likelihood of missed collections.
  - Optimizes waste collection routes based on user inputs, enhancing efficiency and lowering fuel consumption for garbage trucks.

## Benefits of the System
- **Enhanced Community Cleanliness**: 
  - Features like real-time geolocation and black site reporting make it easier for users to dispose of waste properly, while authorities can respond quickly to garbage accumulation issues.

- **Promotes Responsible Behavior**: 
  - The reward system encourages individuals to actively participate in proper waste disposal and offers tangible incentives, motivating ongoing use of the system.

- **Environmental Impact**: 
  - Integrating efficient waste collection methods and preventing litter through geolocation and reporting significantly contributes to environmental sustainability efforts and supports cleaner, greener communities.


## Technologies Used

- **Backend**: 
  - Node.js

- **Database**: 
  - Firestore (NoSQL Database)

- **Authentication**: 
  - Firebase Authentication (for user management)

- **Geolocation Services**: 
  - Google Maps API (for real-time dustbin location)

- **Image Processing**: 
  - Firebase Storage (for storing and managing images)

## Getting Started

To get a local copy of the Infinity++ project up and running, follow these steps:

### Prerequisites

Make sure you have the following installed on your machine:

- [Node.js](https://nodejs.org/) (version 14 or higher)
- [npm](https://www.npmjs.com/) (Node package manager, comes with Node.js)
- [Firebase CLI](https://firebase.google.com/docs/cli) (for deploying the web app)
- [MongoDB](https://www.mongodb.com/) (if using MongoDB for local development)

### Clone the Repository

1. Clone the repository to your local machine using the following command:

   ```bash
   git clone https://github.com/hmns19/trashmap.git

2. Navigate to the project directory:

   ```bash
   cd trashmap

3. Install the required dependencies:
   ```bash
   npm install


4. Start the frontend application:

   ```bash
   npm start

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.
