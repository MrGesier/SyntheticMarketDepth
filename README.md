# SyntheticMarketDepth
Generate artificial synthetic market depth 2%


# Market Depth Simulation

This repository contains a Python script to simulate and visualize the evolution of market depth over time for a simplified order book. The script models growth, random fluctuations, and trends for both buy and sell sides of the order book.

## Features

- Simulates daily growth in market depth over a 3-year period.
- Adds random fluctuations to emulate real-world market behavior.
- Ensures no negative depth values in the order book.
- Visualizes average market depth trends over time with an intuitive plot.

## Requirements

The simulation uses the following libraries:

- `numpy` for numerical calculations.
- `matplotlib` for data visualization.

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/market-depth-simulation.git
    cd market-depth-simulation
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the script:
    ```bash
    python market_depth_simulation.py
    ```

4. A plot will be generated showing the evolution of the average market depth over time for both buy and sell sides.

## Parameters

You can adjust the simulation parameters in the script:

- `days`: Total number of simulation days (default: 3 years, 365 days/year).
- `initial_depth`: Initial market depth for each side (default: 500,000 units).
- `growth_rate`: Daily compounded growth rate (default: 0.002 for ~5% annual growth).
- `num_levels`: Number of price levels in the order book (default: 10).
- `variation_scale`: Scale of random fluctuations (default: 0.05).

## Output

The script outputs a plot with:
- Green shaded area: average market depth for the buy side.
- Red shaded area: average market depth for the sell side.

## License

This project is licensed under the MIT License. Feel free to use and modify it as needed.
