
# Cat Facts App README

This README provides an overview and explanation of the Cat Facts App code, which is a React application that fetches and displays random cat facts from an API. The app uses functional components and React hooks to manage state and fetch data asynchronously.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Project Structure](#project-structure)
5. [API Endpoint](#api-endpoint)
6. [Contributing](#contributing)
7. [License](#license)

## 1. Project Overview <a name="project-overview"></a>

The Cat Facts App is a simple React application that fetches a random cat fact from the 'https://catfact.ninja/fact' API endpoint. Upon loading, the app displays a loading GIF to simulate data fetching. After fetching the cat fact, it displays the fact along with a cat image and a button to generate new cat facts. When the button is clicked, a new cat fact is fetched, and the loading GIF is displayed until the new fact is retrieved.

## 2. Installation <a name="installation"></a>

To run the Cat Facts App on your local machine, follow these steps:

1. Clone the repository: `git clone <repository-url>`
2. Navigate to the project directory: `cd cat-facts-app`
3. Install dependencies: `npm install`

## 3. Usage <a name="usage"></a>

To start the development server and run the app locally, use the following command:

```bash
npm start
```

This will start the development server and open the app in your default web browser at 'http://localhost:3000'.

## 4. Project Structure <a name="project-structure"></a>

The project structure is as follows:

- `src`: Contains the main application code.
  - `index.js`: Entry point of the application.
  - `index.css`: CSS file for styling.
  - `cat-loading.gif`: Loading GIF image.
  - `cat-facts.png`: Cat image.
  - `App.js`: Main component that fetches and displays cat facts.
  - `Loading.js`: Component for displaying the loading GIF.
  - `CatFact.js`: Component to display a single cat fact and handle new fact generation.

## 5. API Endpoint <a name="api-endpoint"></a>

The app fetches cat facts from the 'https://catfact.ninja/fact' API endpoint. The endpoint returns a JSON response with a single cat fact.

## 6. Contributing <a name="contributing"></a>

Contributions to the Cat Facts App are welcome! If you find any issues or want to add new features, feel free to open a pull request.

## 7. License <a name="license"></a>

The Cat Facts App is open-source and licensed under the MIT License. You can find the license information in the 'LICENSE' file.

---

Thank you for using the Cat Facts App! We hope you enjoy learning random cat facts! 🐱