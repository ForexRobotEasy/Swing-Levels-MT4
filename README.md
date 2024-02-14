# Swing Levels MT4

Swing Levels MT4 is a custom indicator developed by the Forex Robot Easy Team. This indicator is designed to help traders optimize their forex trades with precision. It provides various customizable options to display swing highs, swing lows, previous highs and lows, ICT US midnight levels, ICT US preopen 8:30 AM level, and rounded levels. Traders can also toggle the levels display on/off.

## Customizable Variables

- **showSwingHighs**: Set to `true` to display swing highs.
- **showSwingLows**: Set to `true` to display swing lows.
- **showPreviousHighsLows**: Set to `true` to display previous highs and lows.
- **showICTMidnightLevels**: Set to `true` to display ICT US midnight levels.
- **showICTPreopenLevel**: Set to `true` to display ICT US preopen 8:30 AM level.
- **showRoundedLevels**: Set to `true` to display rounded levels.
- **toggleLevels**: Set to `true` to toggle levels display on/off.

## Indicator Initialization Function

The `OnInit` function is called when the indicator is initialized. Any indicator-specific initialization code can be added here.

## Indicator Deinitialization Function

The `OnDeinit` function is called when the indicator is about to be removed from the chart. Any indicator-specific deinitialization code can be added here.

## Indicator Calculation Function

The `OnCalculate` function is called every time a new tick or bar is received. The indicator calculation code should be added here.

## Level Drawing Function

The `OnChartEvent` function is called when a chart event occurs. In this code, it checks if the object click event is triggered on the 'toggleButton' object, and if so, it toggles the levels display on/off. Additional level drawing code can be added here.

## Helper Functions

Any necessary helper functions can be added here.

For detailed reviews and trading results of this product, please visit the official website [here](https://forexroboteasy.com/forex-robot-review/swing-levels-mt4-review-optimize-forex-trades-with-precision/).

Please note that Forex Robot Easy is not the official developer of this product. We are only providing a sample code that can work as described in this product. To find the official developer of this product, please refer to MQL5.
