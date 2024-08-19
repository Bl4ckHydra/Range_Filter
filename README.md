# Range Filter [DW] | TradingView Pine Script

## Overview

This Pine Script provides a customizable range filter for TradingView, designed to help traders with trend analysis and market range determination. It integrates multiple range calculation methods, including ATR (Average True Range), Standard Deviation, and Average Change, offering flexibility to suit various trading strategies.

## Features

- **Customizable Filter Types:** Choose between two filter types to best fit your trading needs.
- **Range Calculation Methods:** Select from methods such as ATR, Standard Deviation, Average Change, and more.
- **Dynamic Color Coding:** Visualize market trends with color changes indicating upward or downward movements.
- **High/Low Bands:** Plot high and low bands around the filter for enhanced visual analysis.
- **Smoothing Options:** Apply smoothing to the filter for more stable trend indications.

## Input Parameters

- **Filter Type:** Select between "Type 1" and "Type 2".
- **Movement Source:** Choose "Wicks" or "Close" for range calculations.
- **Range Size:** Specify the size of the range.
- **Range Scale:** Options include "Points", "Pips", "Ticks", "% of Price", "ATR", "Average Change", "Standard Deviation", and "Absolute".
- **Range Period:** Set the period for ATR, Average Change, and Standard Deviation calculations.
- **Smooth Range:** Enable or disable smoothing of the range.
- **Smoothing Period:** Define the period for smoothing the filter.
- **Average Filter Changes:** Enable or disable averaging of filter changes.
- **Number of Changes to Average:** Specify how many changes to average.

## How to Use

1. **Clone this repository:**

   ```bash
   git clone https://github.com/your-username/range-filter-dw.git
   cd range-filter-dw
