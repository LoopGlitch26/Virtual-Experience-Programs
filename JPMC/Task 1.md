### The trader would like to be able to monitor two historically correlated stocks and be able to visualize when the correlation between the two weakens (i.e. one stock moves proportionally more than the historical correlation would imply). This could indicate a potential trade strategy to simultaneously buy the relatively underperforming stock and sell the relatively outperforming stock. Assuming the two prices subsequently converge, the trade should be profitable.

## Step 1: Setting up your dev environment for the program

  Local Setup on Mac:
  
  i) `git clone https://github.com/insidesherpa/JPMC-tech-task-1-py3.git`
  
  ii) `cd JPMC-tech-task-1-py3`
  
  iii) `python3 server3.py` and `python3 client3.py` on separate terminals
  
  iv) Troubleshooting testing
  
 ![Screenshot 2021-04-28 at 2 41 44 PM](https://user-images.githubusercontent.com/53336715/116407009-24675300-a7e6-11eb-9321-54920d5eda5c.png)

## Step 2: Code changes

  For Local setup in Machine:
  
  i) Prerequisite: Server Client App should be running
  
  ii) Two incorrect things…(1) Ratio is always 1, (2) The price of each stock is always the same as its bid_price
  
  iii) Updates in [Source Code]()
  
## Bonus Task

  To set Unit tests: Build-Act-Assert
  
  i) Build: We first build a simulated test scenario e.g. instantiating the
dummy data we will pass in the methods we’ll test, importing the class
whose methods we want to test, etc.

  ii) Act: We then make some operations and call the method we want to test
for

  iii) Assert: We check if the output of the method we’re testing matches the
expectation we have (e.g. dummy / static data of the outcome)

  
