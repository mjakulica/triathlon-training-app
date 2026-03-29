# Triathlon Training App

## Project Documentation

### Features
- Track training activities for swimming, biking, and running.
- Integrate with fitness APIs for real-time data retrieval.
- Generate performance reports and analytics.
- User authentication and profile management.
- Customizable training plans and schedules.

### Tech Stack
- **Frontend:** React.js, Redux
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Deployment:** Docker, Heroku
- **APIs:** Strava API, training peaks API

### Quick Start Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/mjakulica/triathlon-training-app.git
   cd triathlon-training-app
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables:
   - Create a `.env` file in the root directory and add your environment configurations.
4. Start the development server:
   ```bash
   npm start
   ```

### Project Structure
```
triathlon-training-app/
├── client/              # React frontend
├── server/              # Node backend
├── models/              # Mongoose models
├── routes/              # API routes
├── controllers/         # Request handlers
├── public/              # Static files
└── README.md            # Project documentation
```

### Deployment Information
- To deploy the application, ensure Docker is installed.
- Build the Docker image:
  ```bash
  docker build -t triathlon-training-app .
  ```
- Run the container:
  ```bash
  docker run -p 3000:3000 triathlon-training-app
  ```
- Visit `http://localhost:3000` to see the application in action.

## License
This project is licensed under the MIT License.