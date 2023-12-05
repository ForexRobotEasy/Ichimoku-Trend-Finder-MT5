# Ichimoku Trend Finder ReadMe

This code is an implementation of the Ichimoku Trend Finder strategy, developed by the Forex Robot Easy Team. It is designed to scan multiple symbols and timeframes for Ichimoku trend signals and execute trades based on these signals.

## Input Parameters

1. `Symbols`: A comma-separated list of symbols to scan. By default, it is set to 'EURUSD,GBPUSD,AUDUSD'.
2. `Timeframes`: A list of timeframes to scan. By default, it is set to M15, H1, and H4.
3. `DeepScanMode`: A boolean flag to enable or disable Deep Scan mode. By default, it is set to false.
4. `DeepScanTimeframe`: The timeframe for Deep Scan mode. By default, it is set to D1.

## Main Function

The main function is triggered on every tick. It performs the following steps:

1. Gets the current symbol and timeframe.
2. Checks if the current symbol and timeframe are selected for scanning.
3. Initializes the Ichimoku Kinko Hyo indicator.
4. Scans Ichimoku trend signals for the selected symbol and timeframe.
5. Executes trades based on the trend signals.

## Deep Scan Mode

If the Deep Scan mode is enabled and the current timeframe matches the DeepScanTimeframe, the code performs an additional scan for all symbols in the market watch.

## Utility Functions

The code includes a utility function called `ArrayContains` that checks if an array contains a specific value.

## Product Description

The Ichimoku Trend Finder is a powerful multi-symbol, multi-timeframe trend dashboard for forex traders. It leverages the popular Ichimoku Kinko Hyo indicator to identify potential trend signals and execute trades accordingly.

Key Features:
- Scans multiple symbols and timeframes simultaneously.
- Provides real-time trend signals based on Ichimoku Kinko Hyo.
- Executes trades automatically when trend signals are present.
- Offers Deep Scan mode for in-depth analysis of all symbols in the market watch.

Please note that ForexRobotEasy is not the official developer of this product. We are only showcasing a sample code that can work as described in the product. For detailed reviews and trading results of this product, please visit the official developer's website at [Forex Robot Easy - Ichimoku Trend Finder](https://forexroboteasy.com/forex-robot-review/review-ichimoku-trend-finder-mt5-a-powerful-multi-symbol-multi-timeframe-trend-dashboard-for-forex-traders/). To find the official developer of this product, please refer to the MQL5 marketplace.
