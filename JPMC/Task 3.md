### Given there is a lot of information and data being produced at once, visualizing data in a clear manner with UI/UX considerations accounted for is critical to providing traders with the tools to improve their performance. Basically, to display data visually for traders.

## Step 1: Setup the dev environment

        i) git clone https://github.com/insidesherpa/JPMC-tech-task-3-PY3.git
        
        ii) cd JPMC-tech-task-3-py3
        
        iii) python3 datafeed/server3.py
        
![Screenshot 2021-05-03 at 8 55 15 AM](https://user-images.githubusercontent.com/53336715/116838797-8debb680-ab84-11eb-93de-90d2c7440570.png)

        iv) I already have node installed from the previous task
        
        v) npm start
        
![Screenshot 2021-05-03 at 3 38 38 PM](https://user-images.githubusercontent.com/53336715/116864618-feaec500-abbc-11eb-940d-0cd716405d96.png)

## Step 2: Code changes

        i) Objectives ● There are two things we have to achieve here to complete this task
            ○ (1) We now want to make this graph more useful to traders by making it
              track the ratio between two stocks over time and NOT the two stocks’
              top_ask_price over time.
            ○ (2) As mentioned before, traders want to monitor the ratio of two stocks
              against a historical correlation with upper and lower thresholds/bounds.
              This can help them determine a trading opportunity.That said, we also want
              to make this graph plot those upper and lower thresholds and show when
              they get crossed by the ratio of the stock
              
![Screenshot 2021-05-03 at 5 50 59 PM](https://user-images.githubusercontent.com/53336715/116875251-7259cd80-abcf-11eb-88df-7f7e2c32310f.png)

Completion:

![Screenshot 2021-05-03 at 6 07 19 PM](https://user-images.githubusercontent.com/53336715/116877025-3bd18200-abd2-11eb-9229-512a5737642f.png)

![Screenshot 2021-05-03 at 6 07 36 PM](https://user-images.githubusercontent.com/53336715/116877078-4c81f800-abd2-11eb-9250-ede7be9712c8.png)
