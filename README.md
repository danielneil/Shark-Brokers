<p align="center">
  <img src="https://github.com/danielneil/Shark/blob/main/shark/files/shark_ui_patches/logofullsize.png?raw=true">
</p>

# Shark Brokers

These ansible roles are the broker plugins to use with the Shark algorithmic trading platform. 

For more information about Shark, see [here](https://github.com/danielneil/Shark).

## Shark Brokers API

The Shark Brokers API provides the following generic mechanisms across all brokers.

```
check_price.py - gets the price of the equity, and compares it with the previous price.
```

## Brokers

### yahoo_finance

This is the demo broker - buying and selling occurs using a simulated market. 

### ig-rest

Provides connectivity to IG utilising their REST mechanism.

### ig-streaming

Provides connectivity to IG utilising their streaming mechanism.

