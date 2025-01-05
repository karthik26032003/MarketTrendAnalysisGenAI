# Trend Analysis Insights Generator #

📋 Project Overview

This repository contains a Jupyter Notebook that automates trend analysis on key business metrics like Clicks, Impressions, CTR, and Position. It calculates Week-over-Week (WoW), Month-over-Month (MoM), and Year-over-Year (YoY) changes and uses OpenAI's GPT-3.5 Turbo to generate textual insights based on the calculated trends.

🚀 Features

Calculates WoW, MoM, and YoY changes for multiple metrics.

Uses OpenAI's GPT-3.5 Turbo to provide actionable insights.

Provides a user-friendly, interactive Jupyter Notebook for data analysis.

🧰 Technologies Used

Python

Pandas

OpenAI API

Jupyter Notebook

📂 Setup Instructions

Prerequisites

Python 3.7 or higher

Jupyter Notebook

Installation

Clone the repository:

git clone https://github.com/yourusername/Trend-Analysis-Insights-Generator.git

File Size: 1.5 MB

Navigate to the project directory:

cd Trend-Analysis-Insights-Generator

File Size: 500 KB

Install the required dependencies:

pip install pandas openai openpyxl notebook

Package Size: 3 MB

Set your OpenAI API key in the Jupyter Notebook:

openai.api_key = "your_openai_api_key"

Run the Jupyter Notebook:

jupyter notebook

Execution Size: 300 KB

📊 How It Works

The notebook reads data from an Excel sheet containing business metrics.

It calculates Week-over-Week, Month-over-Month, and Year-over-Year changes for metrics such as Clicks, Impressions, CTR, and Position.

The notebook sends a summary of these trends to OpenAI's GPT-3.5 Turbo API to generate insights.

🧪 Example Usage

Input:

Clicks Trends:

Week-over-Week (WoW): 12.3%

Month-over-Month (MoM): -5.2%

Year-over-Year (YoY): 8.7%

AI-Generated Insights:

"The Clicks metric shows strong Week-over-Week growth of 12.3%, though Month-over-Month performance declined by 5.2%. Year-over-Year growth remains positive at 8.7%."
