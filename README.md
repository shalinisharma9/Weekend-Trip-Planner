Weekend Trip Planner
A simple Python project that helps you prepare a weekend trip plan by entering your destination, transport cost, budget, places to visit, and activity costs. It then displays your trip plan and checks whether the trip fits within your budget.
Features
- Enter your travel destination.
- Add your transport cost and total budget.
- Choose how many places you want to visit.
- Enter each place name and its activity cost.
- Display all the places and costs in a trip summary.
- Check whether the planned trip is within budget.
Technologies Used
- Python
- Lists
- input() and print()
- for loops
- if-else conditions
How to Run
1. Download or clone this repository.
2. Open weekendtripplanner.ipynb in Google Colab or Jupyter Notebook.
3. Run the notebook cells in order.
4. Enter the requested trip details when prompted.
Example Inputs
- Destination: Jaipur
- Transport cost: ₹1,000
- Total budget: ₹5,000
- Number of places: 2
- Place 1: Amber Fort — activity cost ₹500
- Place 2: City Palace — activity cost ₹300
Project Structure
Weekend-Trip-Planner/
├── weekendtripplanner.ipynb
└── README.md
Note
The current notebook checks a variable named total against the budget, but it does not calculate total in the existing cells. Before the budget check works, calculate the total trip cost (transport cost plus all activity costs), for example:
total = transport + sum(costs)
Add this line before the if total <= budget: condition.
Purpose
This project is a beginner-friendly Python exercise for practising user input, lists, loops, and conditional statements while planning a trip.
