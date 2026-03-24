# Time Series Forecasting Web Application

A Flask-based web application for time series forecasting that allows users to upload data, run forecasting workflows, and visualize prediction results through an interactive interface.

## Overview

This project is designed to perform time series forecasting using machine learning/statistical methods and present the results through a web-based interface. It combines backend processing, model handling, and frontend templates to make forecasting more accessible and user-friendly.

## Features

- Upload and process time series datasets
- Forecast future values using trained models
- Web-based interface built with Flask
- Modular project structure for services, models, and templates
- Configurable application settings
- Organized handling of data, logs, and model files

## Tech Stack

- **Python**
- **Flask**
- **HTML / CSS**
- **Pandas**
- **NumPy**
- **Jinja Templates**

## Project Structure

```bash
Times-Series-Forecasting-main/
│── data/               # Input datasets and processed files
│── logs/               # Log files for execution and debugging
│── model/              # Saved models and forecasting logic
│── portfolio/          # Additional static or portfolio-related components
│── services/           # Core business logic and forecasting services
│── templates/          # HTML templates for Flask frontend
│── .env                # Environment variables
│── app.py              # Main Flask application entry point
│── config.py           # Configuration settings
│── requirements.txt    # Project dependencies
│── test.csv            # Sample dataset for testing
│── README.md           # Project documentation
