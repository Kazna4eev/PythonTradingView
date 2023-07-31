TradingView Real-Time Quote Fetching

This is a Python script that fetches real-time quotes for a specific currency pair from TradingView using WebSocket. It uses the websocket-client library to establish a WebSocket connection and retrieve live quotes for the given currency pair.

Prerequisites:
1. Python 3.x
2. Install required packages using requirements.txt: 'pip install -r requirements.txt
'

How to Use

1. Clone or download the repository to your local machine.
2. Install the required libraries using the requirements.txt file 'pip install -r requirements.txt
'
3. Open the main.py file in a text editor and modify the pair and market variables in the __name__ == "__main__" block to the desired currency pair and market. For example 

'pair = "btcusdt"

market = "crypto"
'
4. Save the changes and run the script: 'python main.py
'

The script will establish a WebSocket connection to TradingView, retrieve real-time quotes for the specified currency pair, and display them on the console.