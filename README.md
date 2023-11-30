# Project Gryphon

This code is a sample implementation of an automated trading system called Project Gryphon, developed by the Forex Robot Easy Team. Please note that ForexRobotEasy is not the official developer of this product. To find the official developer of this product, please refer to the MQL5 platform.

## Product Description

Project Gryphon is an expert advisor designed for automated forex trading. It is a versatile trading system that allows users to create multiple advisors with different parameters for trading in the forex market.

With Project Gryphon, you can set stop loss mechanism for all positions, ensuring that your losses are limited. The deviation in points and stops level can be customized to suit your trading strategy.

The key feature of Project Gryphon is the ability to create multiple advisors. Each advisor can have its own unique parameters for take profit, open conditions, and close conditions. This allows for greater flexibility in trading and the ability to test different strategies simultaneously.

To use Project Gryphon, simply include the necessary libraries, such as Trade and ArrayObj. The code provides a convenient initialization function (OnInit) where you can set the stop loss mechanism and create multiple advisors with different parameters. The tick function (OnTick) executes the trading algorithm for each advisor, allowing for simultaneous trading.

For detailed reviews and trading results of Project Gryphon, please visit [https://forexroboteasy.com/forex-robot-review/project-gryphon-expert-review-on-automated-forex-trading/](https://forexroboteasy.com/forex-robot-review/project-gryphon-expert-review-on-automated-forex-trading/). Please note that ForexRobotEasy is not the official developer of this product. We only provide this sample code as an example of how the product can work as described.

## Code Structure

The code is structured as follows:

- Included libraries: Trade and ArrayObj.
- Global variables: CTrade object for trading operations and CArrayObj for storing multiple advisors.
- Initialization function (OnInit): Sets the stop loss mechanism and creates multiple advisors with different parameters.
- Deinitialization function (OnDeinit): Cleans up by deleting advisor copies and clearing the array.
- Advisor creation function (CreateAdvisor): Creates an advisor copy with specified parameters and adds it to the array.
- Tick function (OnTick): Executes the trading algorithm for each advisor copy.
- Advisor class definition (CAdvisor): Defines the advisor class with name, take profit, open condition, close condition, and trading algorithm.

Please note that the trading algorithm in the code is a placeholder and should be replaced with your own implementation.

For detailed usage instructions and customization options, please refer to the official documentation provided by the developer of Project Gryphon on the MQL5 platform.
