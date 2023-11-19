# Excelsior ReadMe File

Excelsior is a Forex trading software developed by the Forex Robot Easy Team. This software utilizes a unique dual neural network approach to analyze market data and generate buy and sell signals. 

## Symbols

The symbols to be traded are defined in the `symbols` array. The current symbols included in the array are 'AUDUSD', 'EURUSD', 'GBPUSD', 'USDCAD', 'USDCHF', and 'USDJPY'. 

## Neural Networks

The code includes a `NeuralNetwork` class which is responsible for creating, training, and calculating signals using the neural networks.

### CreateRNN()

The `CreateRNN()` function is responsible for creating the recurrent neural network. This function should be implemented to define the architecture and parameters of the RNN.

### TrainNetwork()

The `TrainNetwork()` function is responsible for training the neural network. This function should be implemented to train the network using historical market data.

### CalculateSignals()

The `CalculateSignals()` function is responsible for calculating buy and sell signals based on market analysis. This function should be implemented to analyze the market data and generate signals.

## ValidateSignal()

The `ValidateSignal()` function is responsible for validating the daily signal before opening a trade. This function should be implemented to define the criteria for a valid signal.

## EnableAutomatedTrading()

The `EnableAutomatedTrading()` function is responsible for enabling the automated trading functionality. This function should be implemented to open trades for each symbol if the signal is valid.

## OnStart()

The `OnStart()` function is the entry point of the program. In this function, the neural networks are created, trained, and used to calculate signals. The automated trading functionality is then enabled.

## Product Description

Excelsior is a powerful Forex trading software developed by the Forex Robot Easy Team. It utilizes a unique dual neural network approach to analyze market data and generate highly accurate buy and sell signals. With Excelsior, traders can automate their trading strategies and take advantage of profitable trading opportunities.

Key Features:
- Dual Neural Networks: Excelsior uses two neural networks, one for buying signals and one for selling signals, to provide accurate and reliable trading signals.
- Symbol Flexibility: Excelsior supports trading on a wide range of currency pairs, including AUDUSD, EURUSD, GBPUSD, USDCAD, USDCHF, and USDJPY.
- Automated Trading: Excelsior enables traders to automate their trading strategies, saving time and effort in executing trades.
- Signal Validation: Excelsior includes a signal validation mechanism to ensure that only high-quality signals are acted upon, increasing the chances of profitable trades.

Please note that ForexRobotEasy is not the official developer of this product. We provide this sample code to demonstrate the functionality described in the product. For detailed reviews and trading results of Excelsior, please visit the official developer's website: [Excelsior Forex Software - A Review of its Unique Dual Neural Networks](https://forexroboteasy.com/forex-robot-review/excelsior-forex-software-a-review-of-its-unique-dual-neural-networks/).

For more information and to obtain the official version of Excelsior, please visit the MQL5 website.
