# Universal Swing Arrows

This code is a custom indicator that generates swing trading signals based on the Universal Swing Arrows strategy. It is developed by the Forex Robot Easy Team for forexroboteasy.com.

## Global Variables

- `Period`: The period used for swing high/low calculation.
- `StopLoss`: The stop loss level in pips.
- `Fluctuation`: The maximum allowed price fluctuation in pips.

## Custom Indicator Initialization

The `OnInit()` function is called during the indicator initialization. You can add any necessary indicator initialization code here.

## Custom Indicator Calculation

The `OnCalculate()` function is called for each new bar in the chart. This is where the indicator calculation code is implemented.

In this code, the indicator identifies swing highs and lows, determines the trend direction, calculates the stop loss level, and generates buy or sell signals.

For example, the code generates a buy signal with an arrow if the indicator value (`arrowUp`) is not `EMPTY_VALUE`. Similarly, it generates a sell signal with an arrow if the indicator value (`arrowDown`) is not `EMPTY_VALUE`.

You can customize the code to execute actual trade orders based on the generated signals.

## Custom Indicator Deinitialization

The `OnDeinit()` function is called when the indicator is removed from the chart. You can add any necessary deinitialization code here.

Please note that Forex Robot Easy is not the official developer of this product. This code is provided as a sample that can work as described in the product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, visit [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/universal-swing-arrows-review-reliable-forex-swing-trading-signals/).
