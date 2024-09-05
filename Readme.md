# Quick Guide: Running Aspectify Locally

This document details the process of running our Aspectify application for the first time. Follow these steps to run Aspectify on your local machine:

## Prerequisites

The first two steps will focus on Making sure we have the necessary packages, which are:

- [Node.js](https://nodejs.org/) (version 16 or later is recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- [Angular CLI](https://angular.io/cli)

### Step 1: Install Node.js and npm

If Node.js is not already installed, download and install it from the official [Node.js website](https://nodejs.org/). The installation also includes npm (Node Package Manager).

Verify installation:

```shell
node -v
npm -v
```

### Step 2: Install Angular CLI

To install Angular CLI globally, run the following command in your terminal:

```shell
npm install -g @angular/cli@16
```

You can verify the installation of Angular CLI by running:

```shell
ng version
```

### Step 3: download the source code

Download the application files from the shared Google Drive located at `Aspectify/Frontend`. Navigate to the project directory in your terminal. Make sure you are in the `Frontend` file in your terminal.

### Step 4: Install Dependencies

The `node_modules` folder is excluded from the shared folder. To install the required dependencies, run:

```shell
npm install
```

This will install all the necessary packages listed in the `package.json` file.

### Step 5: Run the Application

Once the dependencies are installed, start the Aspectify development server by running:
```shell
ng serve
```
This will compile and serve the application on your local machine.

### Step 6: Access the Application

After running `ng serve`, the terminal will display a message indicating that the application is running at:
http://localhost:4200/

Open a browser and navigate to this URL to view the application.

### Additional Notes

If the port `4200` is already in use, you can run the application on a different port using:
```shell
ng serve --port <PORT_NUMBER>
```

For example, to run it on port 4300:
```shell
ng serve --port 4300
```

### Step 7: Stop the Application
To stop the development server, press `Ctrl + C` in the terminal.

# Sincerly, Fouad AURAG.