# Reinforcement Learning Based Routing Algorithm Analysis
This repository contains a Jupyter Notebook that analyzes the performance of different routing algorithms in the presence of malicious nodes in a network. The analysis includes metrics such as the number of packets delivered, energy consumption, energy efficiency, and packet loss.

The following reinforcement learning based routing algorithms are analyzed:

* [R2LTO](https://ieeexplore.ieee.org/document/9231883)

* [RLBR](https://journals.sagepub.com/doi/full/10.1177/1550147719833541)

* [RLBEEP](https://ieeexplore.ieee.org/document/9756551)

## Requirements

To run the notebook, you need the following Python libraries:

- `pandas`
- `matplotlib`
- `numpy`

You can install these libraries using `pip`:

```bash
pip install pandas matplotlib numpy
```

## Analysis Overview

The notebook covers the following aspects:

1. **Number of Packets Delivered**: Compares how different routing algorithms perform regarding the number of packets successfully delivered as the number of malicious nodes increases.
2. **Energy Consumption**: Analyzes the energy consumption of each routing algorithm in different scenarios.
3. **Energy Efficiency**: Evaluates the energy efficiency of the algorithms.
4. **Packet Loss**: Measures the packet loss rate for each algorithm as the number of malicious nodes changes.

## License

This project is licensed under the MIT License. 