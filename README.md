# TrendPower-SMA-ADX-

Define Trading Strategy
Entry Signal (df['Entry']):
ADX > adx_threshold: The Average Directional Index (ADX) is greater than a specified threshold (adx_threshold), indicating a strong trend.
Close > df['SMA']: The closing price of the asset is above the Simple Moving Average (SMA), suggesting an upward trend or buying opportunity.

Exit Signal (df['Exit']):
ADX > adx_threshold: The ADX remains above the threshold, indicating a strong trend.
Close < df['SMA']: The closing price falls below the SMA, signaling that the price may be trending down or losing strength, thus prompting an exit from the position.
