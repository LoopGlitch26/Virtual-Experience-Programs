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
  
  iii) Updates in [Source Code](https://github.com/LoopGlitch26/Virtual-Experiences/blob/main/JPMC/JPMC-tech-task-1-PY3/client3.py)
  
## Bonus Task

  To set Unit tests: Build-Act-Assert
  
  i) Build: We first build a simulated test scenario e.g. instantiating the
dummy data we will pass in the methods we’ll test, importing the class
whose methods we want to test, etc.

  ii) Act: We then make some operations and call the method we want to test
for

  iii) Assert: We check if the output of the method we’re testing matches the
expectation we have (e.g. dummy / static data of the outcome)

## Step 3: Create Patch File

  A git patch file is just a file that you can apply to a repository to get the
changes / modifications / additions another developer did on his / her machine
onto your local machine. This isn’t the only way to do that ofcourse but this is
a viable method for a head/lead developer to check your code first before
merging it into the repository’s main/master branch.

   1) git init
   
   ii) git add -A
   
   iii) git config user.email "<your_email_address>"

  iv) git config user.name "<your_name>"

  v) git commit -m 'Create Patch File'

  vi) git format-patch -1 HEAD
  
Patch file created and updated, [Source Code]()
  
