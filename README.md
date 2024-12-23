# stock-simulation
A stock analysis program to buy/sell stocks in a portfolio and analyze performance with real-time API stock market data. 

This was made in Java for Northeastern's CS3500 Object Oriented Design course. By instructor policy, source code can be accessed only by request.

The simulation can be run with either a text-based interface or a graphical interface.

Both interfaces allow the following features:
  - Creating a portfolio of stocks
  - **Buying/selling** stocks in a portfolio
  - Viewing a portfolio's **value ($) or composition (shares)** on a date
  - Saving a portfolio to an **xml file**/loading a portfolio from an xml file
  
The text-based interface has additional features that are not in the GUI:
  - Viewing **gain/loss, moving average**, or **x-day crossover** of a stock over a time period
  - **Rebalancing** a portfolio by percentages
  - Plotting a **bar chart** that illustrates the performance of a stock/portfolio over a time period.

## Demos
GUI Stock Simulation: 
![stockgui](https://github.com/user-attachments/assets/43e9166a-59c0-4afa-b05c-b80a121908e5)

Text-based Stock Simulation: 
![stocktext](https://github.com/user-attachments/assets/873077c1-da2c-4e22-9c34-a5f0f50da7f3)

## Install
  1. Download the jar file.
  2. Navigate to the folder that contains the jar file in your command-prompt/terminal.
  - For the text-based user interface:
      - Type “java -jar Assignment6.jar -text”, and press enter.
  - For the GUI:
      - Type "java -jar Assignment6.jar", and press enter.
