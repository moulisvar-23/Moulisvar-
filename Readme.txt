README: Reproducing the Outputs for the Travelling Thief Problem

Project Title: Nature-Inspired Algorithm for Solving the Travelling Thief Problem

Description

This project implements the Non-Dominated Sorting Genetic Algorithm II (NSGA-II) to solve the Travelling Thief Problem (TTP), a multi-objective optimization problem. The algorithm aims to optimize two conflicting objectives—travel cost and item value—by finding a balanced set of Pareto-optimal solutions.

Requirements

Python 3.8 or higher

pymoo library for multi-objective optimization

matplotlib for result visualization

Installation Steps

Clone the Repository:

git clone https://github.com/Group14-TTP/NSGA-II-TTP.git

Navigate to the Project Directory:

cd NSGA-II-TTP

Install the Required Dependencies:

pip install -r requirements.txt

Running the Code

Run the Main Script:

python main.py

This will execute the NSGA-II algorithm on the Travelling Thief Problem instances and generate output files with the results.

Visualize the Results:

python plot_results.py

This script will generate plots of the Pareto front showing the trade-offs between travel cost and item value.

Output Description

The following outputs will be generated:

pareto_front.png: A graphical representation of the Pareto front.

results.csv: A CSV file containing the detailed solutions for each test instance, including travel costs, item values, and knapsack weights.

log.txt: A log file tracking the algorithm’s progress and key performance metrics during execution.

Troubleshooting Tips

If you encounter any issues while running the code:

Check Dependencies: Ensure that all required libraries are installed correctly.

Verify Python Version: Ensure you are using Python 3.8 or higher.

Debugging Logs: Check the log.txt file for detailed error messages and troubleshooting guidance.

Customization Options

To customize the algorithm settings (e.g., population size, number of generations), modify the config.json file in the project directory. Example parameters include:

{
  "population_size": 100,
  "generations": 200,
  "mutation_rate": 0.1
}

Project Structure

NSGA-II-TTP/
├── main.py          # Main script to run the algorithm
├── plot_results.py  # Script to visualize the results
├── config.json      # Configuration file for algorithm parameters
├── requirements.txt # Dependencies list
└── README.md        # Documentation

