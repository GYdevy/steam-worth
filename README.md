# Project Title
CS2 Inventory worth calculator


## Description

 CS2 Inventory worth calculator is my debut JavaScript project, designed to fetch, calculate, and visualize the worth of your inventory. 
This tool sends requests to obtain real-time inventory data, computes its total worth, and presents a graph to illustrate the historical price changes.
### Features:

 - Fetches inventory data through API requests.
 - Calculates and displays the total inventory worth.
 - Visualizes total price history with an interactive graph.

## Table of Contents
- [Demo Video](#demovideo)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)


## 📺 Demo Video

[Watch the demo](https://files.catbox.moe/i7amq3.mp4)

## Installation


### 1. Clone the Repository
Clone the project to your local machine using:

```bash
git clone https://github.com/GYdevy/steam-worth
```

### 2. Open the Project
Open the project in your preferred IDE (e.g., VS Code, WebStorm).

### 3. Create a `.env` File
In the root directory of the project, create a `.env` file and add the following line:

```env
API_KEY=your_steam_api_key_here
```

Replace `your_steam_api_key_here` with your actual Steam API key.

### 4. Running the Project

Due to Steam’s API rate limits, a demo server is included.

- To run the **backend** and **demo server**, use:

```bash
node app.js
node serverDeme.js
```

This setup fetches data from the local demo server.

- To use the **real Steam API server**, run only:

```bash
node app.js
```

Then, update the value of the `urlv` variable in the code to the string specified in the documentation.

### 5. Run the Project
Once the backend is running, proceed with launching the frontend (if applicable), or follow any remaining instructions to complete the setup.

## Usage
Follow steps 1-5.
Simply provide your steam id into the input field, Leave the app id as 730 (todo fix).
By default it will show my profile in case you didn't fetch from steam.



## Contributing

Feel free to contribute and fix any issues.


