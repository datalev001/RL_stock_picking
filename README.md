# Dynamic Portfolio Construction via Reinforcement Learning and Dynamic Programming
A Novel Framework Integrating Policy Gradient Optimization and State-Driven Buy-and-Hold Strategies for Stock Selection
I present a novel approach that integrates reinforcement learning and dynamic programming to build a state-driven portfolio using real market data. This framework uses price ratios and moving averages - such as comparing a stock's price to the combined value of SPY and QQQ - to generate trading signals. For instance, if Stock A's short-term moving average falls below its long-term average by a preset threshold, it triggers an investment of a fixed $1000, after which the position is held.
Theoretically, an RL policy network is designed to learn optimal decision-making via policy gradients, effectively guiding portfolio selection. Practically, the strategy is tested over a substantial historical period, simulating real trading scenarios, which makes it relevant for both academic research and real-world portfolio management.
The process is broken down into clear, step-by-step stages - from data preparation and signal generation to policy training - making it straightforward to understand and implement. 
Finally, this method provides a practical, efficient framework for navigating complex market dynamics with state-based decisions - offering valuable insights for researchers and actionable strategies for investors.

For detail, see my medium papers: https://medium.com/@datalev
