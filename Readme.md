# Aspectify: Aspect-Based Sentiment Analysis

Aspectify is a web application developed to perform **Aspect-Based Sentiment Analysis (ABSA)** on two domains: **laptops** and **restaurants**. The project was a part of a thesis that involved fine-tuning large language models (LLMs) for aspect prediction and sentiment classification. The best models obtained were:

- **Mistral-7B** for aspect prediction
- **LLaMA3-8B** for sentiment classification

The application is developed with **Angular** for the frontend and **Flask** for the backend. The frontend is deployed on **Firebase**, and the backend is exposed using **ngrok**.

![Aspectify Screenshot](path-to-your-image-file)

## Features

- Perform Aspect-Based Sentiment Analysis for laptops and restaurants
- Fine-tuned LLMs for high accuracy in aspect prediction and sentiment classification
- Easy-to-use interface for uploading data and viewing sentiment results

## How to Use

### 1. Run the Backend
Before using the application, you need to run the backend. This can be done using Google Colab. If you're using the free tier of Colab, please note that you can only load the LLMs for **one domain at a time**.

By default, the backend loads the models for the **laptops domain**. To switch to the **restaurants domain**, simply:

- **Uncomment** the cells that load the models for **restaurants**
- **Comment out** the cells that load the models for **laptops**

### 2. Access the Frontend

The frontend can be accessed via the following link:

[Aspectify Web Application](https://aspectify-f94e3.web.app/)

### 3. Connect the Backend to the Frontend

1. After running the backend on Google Colab, copy the **ngrok** link.
2. Make sure you have added your ngrok **auth token** to expose the backend properly.
3. Paste the ngrok link into the web application to link the backend.
4. Choose the correct domain (laptops or restaurants) based on the models you've loaded.

### 4. Perform Sentiment Analysis

Once the backend and frontend are connected, you can start performing Aspect-Based Sentiment Analysis by uploading data. Simply click on the correct domain in the UI and analyze the sentiment results for various aspects.

## Technologies Used

- **Frontend**: Angular
- **Backend**: Flask
- **Models**: Fine-tuned Mistral-7B and LLaMA3-8B for Aspect-Based Sentiment Analysis
- **Hosting**: Firebase (frontend), ngrok (backend)

## Project Structure

- **/frontend**: Angular code for the frontend
- **/backend**: Flask API and model-loading scripts for the backend
- **/Experiments Notebooks**: To Be Added Soon

## Important Notes

- If using the free tier of Google Colab, the models can only be loaded for one domain at a time (laptops or restaurants).
- Ensure you have set up ngrok properly with your auth token to expose the backend and connect it to the frontend.

## Contributing

Feel free to fork this repository and contribute. Pull requests are welcome.

## License

This project is licensed under the MIT License.

