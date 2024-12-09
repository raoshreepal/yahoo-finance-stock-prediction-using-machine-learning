Data-Set :- https://drive.google.com/drive/folders/1gTzCzRmHtsJfeUoKPsX7pxqrljELVtf-?usp=sharing
# Stock Price Prediction Project

This repository contains a stock price prediction project that uses historical stock data from 2000 companies to predict future stock prices. The project involves data collection, merging, cleaning, and implementing company-wise models for accurate predictions. The project also includes a GUI application built using Tkinter.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data Description](#data-description)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Model Implementation](#model-implementation)
6. [GUI Application](#gui-application)
7. [Results](#results)
8. [Contributing](#contributing)
9. [License](#license)

## Project Overview

The goal of this project is to predict stock prices for various companies based on historical data. The data includes daily stock prices and volume, which are used to train machine learning models to forecast future prices.

## Data Description

The dataset contains the following columns:
- `Date`: The date of the stock price entry
- `Open`: The opening price of the stock on the given date
- `High`: The highest price of the stock on the given date
- `Low`: The lowest price of the stock on the given date
- `Close`: The closing price of the stock on the given date
- `Adj Close`: The adjusted closing price of the stock on the given date
- `Volume`: The trading volume of the stock on the given date
- `Company Name`: The name of the company
- `Company`: The ticker symbol of the company

## Installation

To run this project, you need to have Python and the following libraries installed:
- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `tkinter`

You can install the required libraries using pip:

```bash
pip install numpy pandas scikit-learn matplotlib
