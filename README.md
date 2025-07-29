# CodeAlpha.StockPortfolioTracker
𝗡𝗮𝗺𝗲: K.R.Mounisha  
𝗦𝘁𝘂𝗱𝗲𝗻𝘁 𝗜𝗗: CA/AU1/6255
𝗗𝗼𝗺𝗮𝗶𝗻: Python Programming
𝗗𝘂𝗿𝗮𝘁𝗶𝗼𝗻: 1st August 2025 to 30th August 2025
📌 Project Description
This project is a simple command-line Python tool that allows users to calculate their total stock investment value based on manually entered stock quantities and predefined stock prices. It is developed as part of the CodeAlpha Internship Program.

🎯 Features
Takes user input for stock symbols and quantities

Uses a hardcoded dictionary to define stock prices

Calculates the total investment for each stock and the portfolio

Optionally saves a report in a .txt file

🛠️ Technologies Used
Python 3

Core Concepts:
dictionary, input/output, basic arithmetic, file handling

💡 How It Works
The user enters how many different stocks they own.

For each stock:

The user inputs the symbol (e.g., AAPL, TSLA)

The quantity they hold

The script checks prices from a predefined dictionary.

It calculates the total investment and optionally saves the output in portfolio_report.txt.

🧪 Sample Input
Enter the number of different stocks you own: 2
Enter stock symbol (e.g., AAPL, TSLA): AAPL
Enter quantity of AAPL: 5
Enter stock symbol (e.g., AAPL, TSLA): TSLA
Enter quantity of TSLA: 3

sample output
AAPL: 5 shares × ₹180 = ₹900
TSLA: 3 shares × ₹250 = ₹750

🧾 Total Investment Value: ₹1650
📁 Report saved to 'portfolio_report.txt'

file structure
📂 CodeAlpha_StockPortfolioTracker
├── portfolio_tracker.py
├── portfolio_report.txt (auto-generated)
└── README.md
