# Runtime-Space-Complexity-in-Financial-Signal-Processing
Design and implement a Python module that ingests market data from a CSV file and applies multiple trading strategies with varying runtime and space complexities. 
This project analyzes runtime and space complexity tradeoffs in financial trading strategies using moving averages.
It demonstrates how algorithmic design choices affect scalability, performance, and memory usage in trading systems.

The implementation includes naive vs optimized strategies, detailed Big-O annotations, profiling with multiple tools, and visualized scaling behavior.


Project Structure:
├── GLD_market_data.csv          # Market price data (timestamp, price)
├── data_loader.ipynb            # CSV ingestion + immutable dataclass
├── strategies.ipynb             # Naive & windowed MA strategies
├── profiler.ipynb               # timeit, cProfile, memory_profiler
├── reporting.ipynb              # plots + complexity_report.md
├── main.ipynb                   # one-click orchestration
├── tests.ipynb                  # correctness + performance validation
├── benchmark_results.csv        # generated profiling table
├── complexity_report.md         # final analysis report
└── README.md

How to Run (Recommended Order):
1. data_loader.ipynb
2. strategies.ipynb
3. profiler.ipynb        (or main.ipynb)
4. reporting.ipynb
5. tests.ipynb

One-click option
Run main.ipynb to execute:
ingestion
benchmarking
plotting
