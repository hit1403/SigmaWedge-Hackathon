# Overview
The project implements a minimalist trading workflow using the following steps:

➡️ Pulling daily close prices for Apple stock (AAPL) for the year 2023 using Quantrocket.

➡️ Classifing the daily returns into Bull, Flat, or Bear states based on predefined criteria.

➡️ Calculating the probability distribution of transitioning from one state to another.

➡️ Making decisions on optimal points to place buy orders to maximize the portfolio value.

➡️ Displaying the final portfolio value, optimal buy indices.

# Components  
✅ Data Retrieval

- The data retrieval component fetches daily close prices for Apple stock from the Quantrocket platform for the year 2023.

✅ State Classification

- The state classification component categorizes daily returns into Bull, Flat, or Bear states based on predefined thresholds.

✅ Transition Distribution Calculation

- This component calculates the probability distribution of transitioning from one state to another based on historical observations.

✅ Buy Order Decision Making

- This component determines the optimal dates to place buy orders to maximize the portfolio value.


# Usage
## To use the project:

1) Follow the instructions on the Quantrocket website to download it on your local machine.

2) Replace the license key in the first cell of the code with your license key by signing into your Quantrocket account.

3) Run the provided code to implement the trading model and obtain the desired outputs.

#### (OR)

1) I have extracted the needed data from Quantrocket and converted it into a csv file.

2) You can import the csv and run the code from cell number 9 [From import pandas as pd]


# Result
⭐Getting Portfolio value ==> 40
