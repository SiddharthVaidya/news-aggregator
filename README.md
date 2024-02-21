# News Agregator API

This is a simple Node.js project that provides a news aggregator API. The project uses JavaScript and is managed with npm.

### Prerequisites

You need to have Node.js and npm installed on your machine. If you don't have Node.js installed, you can download it from [here](https://nodejs.org/en/download/).

### Installing

1. Clone the repository:
    ```
    git clone https://github.com/SiddharthVaidya/news-aggregator.git
    ```

2. Navigate to the project directory:
    ```
    cd news-aggregator
    ```

3. Install the dependencies:
    ```
    npm install
    ```

## Running the Application

To start the application, run the following command in the project directory:

```
node app.js
```

## Running the Tests

To run the tests, use the following command:

```
npm test
```

## API Endpoints

The application provides the following endpoints:

- `POST /users/signup`: Signup to create your user.
- `POST /users/login`: Login using email and password .
- `GET /users/preferences`: Fetches preferences set by logged in user.
- `PUT /users/preferences`: Change you preference of news category.
- `GET /news`: Get the news of your desired preference.


## Built With

- [Node.js](https://nodejs.org/) - The runtime environment
- [express](https://expressjs.com/) - The web framework
- [npm](https://www.npmjs.com/) - Dependency Management
- [news-api](https://newsdata.io/) - News API to fetch latest news
