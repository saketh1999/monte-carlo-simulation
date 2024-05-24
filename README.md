# INTRODUCTION
The Monte Carlo method is a computational technique that tackles problems with inherent randomness by leveraging repeated random sampling. It simulates various scenarios within a defined probability distribution to estimate possible outcomes. 
Imagine tossing a coin many times to understand the likelihood of heads or tails.By running numerous simulations, the method builds a picture of probable results for complex situations where closed-form solutions are difficult or impossible. 
This makes it a valuable tool in various fields, from finance and risk analysis to physics and engineering.

## Example to understand
Imagine you're considering investing in a new stock. You're excited about the company's potential, but there's always some uncertainty about future stock prices. 
A Monte Carlo simulation can help you understand the range of possible outcomes.

Here's how it works in this investment example:

Define your variables: The future stock price is uncertain, so that's your variable. You might find analyst estimates suggesting the stock price could be between $20 and $40 per share in a year (your probability distribution).

Random Sampling: Run the simulation multiple times (say, 100 times). Each time, randomly pick a price between $20 and $40 (based on your probability distribution) to represent the stock price in one year of simulation.

Simulate the outcome:  Based on the random stock price you picked, calculate the potential return on your investment (considering how many shares you plan to buy).

Repeat and Analyze:  Repeat steps 2 and 3 many times (100 times in our example) to get a bunch of simulated returns on your investment. Now you can analyze the results: see how often you end up with a 10% return, 20% return, and so on. This tells you the probability of different potential profits (or losses).

By running a Monte Carlo simulation, you can estimate the likelihood of various returns on your investment. This helps you make a more informed decision about whether to invest and potentially avoid unexpected losses.
This is a simplified example, but Monte Carlo simulations are a powerful tool in finance and many other fields to make decisions when faced with uncertainty.

You learn more [Here](https://www.bobstanke.com/blog/monte-carlo-simulation-overview).
