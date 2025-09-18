# TradingView Gap Detector (h4vok Fork)

This repository contains a modified and debugged version of a Pine Script™ indicator for TradingView that automatically detects and displays price gaps on your chart.

## Description

A price gap occurs when there's a significant difference between one period's close and the next period's open, with no trading in between. Many trading strategies use gaps as significant levels of support, resistance, or areas of interest.

This indicator is a fork of an existing script that has been systematically debugged to resolve issues with real-time gap detection and line drawing. It now correctly identifies and visualizes both historical gaps and the most recent gap as it forms.

## Features

- Real-Time Gap Detection: Correctly identifies and draws the gap between the current bar and the previous bar.
- Historical Gap Detection: Scans a user-defined number of historical bars to find and display past gaps.
- Clear Visualization: Draws clean, extendable horizontal lines to mark the upper and lower bounds of each detected gap.
- Customizable: Easily adjust the look-back period and the width of the drawn lines.

## How to Use

- Navigate to a chart on TradingView.
- Open the Pine Editor tab at the bottom of the screen.
- Copy the entire code from the GapDetector.pine file below.
- Paste the code into the Pine Editor, replacing any default content.
- Click "Add to Chart". The indicator will now appear on your chart.

## Adding in TradingView directly

This indicator is not publicly available in tradingview as of now, as I want to properly address the original author of the script and give them the proper credit.

However, you can find it through this link: https://www.tradingview.com/script/j02cVwFN-GAP-DETECTOR-h4vok-fork/
