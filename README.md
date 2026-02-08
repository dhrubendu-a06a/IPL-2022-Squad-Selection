# IPL-2022-Squad-Selection
Data-driven IPL 2022 squad selection under budget and role constraints

# IPL 2022 Squad Selection – Data Science Project

## Objective
Select an optimal squad of 15 IPL players for the 2022 season within a
total auction budget of ₹50 Crores using data-driven performance metrics
and role constraints.

## Datasets Used
- IPL Lifetime Performance Dataset (filtered for 2022 season)
- IPL 2022 Auction Sold Players Dataset

## Methodology
- Filtered 2022 performance data
- Applied Min-Max normalization to all metrics
- Designed role-specific composite scores for batting, bowling,
  wicket keeping, and all-rounders
- Adjusted runs using runs per match
- Inverted bowling metrics where lower values indicate better performance
- Combined performance score with inverted price for budget optimization
- Selected squad using a constraint-aware greedy algorithm

## Constraints
- Squad size: 15 players
- Budget: ≤ ₹50 Crores
- Minimum roles:
  - 2 Wicket Keepers
  - 3 Batsmen
  - 3 Bowlers

## How to Run
1. Open the Jupyter Notebook
2. Ensure CSV files are in the same directory
3. Run all cells from top to bottom
