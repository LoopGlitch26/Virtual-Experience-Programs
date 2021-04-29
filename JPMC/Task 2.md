### Typically, traders monitor stock prices and trading strategies by having data displayed visually on their screens in chart form. Often these charts will be accompanied by alerts that notify users when certain events occur or when preset price thresholds are hit.

## Step 1: Setup Dev Environment to use JPMC frameworks

  i) Inside Source Code directory, install `npm` by `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash` and then `export NVM_DIR="/Users/loopglitch/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"`

  ii) Check `nvm --version` == `0.38.0`
  
  iii) Install the right npm version `nvm install v11.0.0` and use `nvm use v11.0.0`
  
  node and npm version:
  
  ```
  (base) loopglitch@Not-A-MacBook ~ % node -v
  v11.0.0
  (base) loopglitch@Not-A-MacBook ~ % npm -v
  6.4.1
  ```
  
  iv) `npm install` and `npm start` 
  
  I was facing some issues with my node installation, so my results were like this:
  ![Screenshot 2021-04-29 at 3 33 06 PM](https://user-images.githubusercontent.com/53336715/116534578-8d5ad380-a897-11eb-83a5-5e62ea9583d1.png)
  
  But after some fucking troubleshooting, this is the result:![Screenshot 2021-04-29 at 3 56 04 PM](https://user-images.githubusercontent.com/53336715/116537299-e710cd00-a89a-11eb-9c66-b47f9dcf8426.png)

  And this is the working app: ![Screenshot 2021-04-29 at 3 57 23 PM](https://user-images.githubusercontent.com/53336715/116537348-f6901600-a89a-11eb-85ef-866745fcfa36.png)

  Troubleshooting steps: I had to delete the source code `node_modules` and then followed [this](https://github.com/insidesherpa/JPMC-tech-task-2/issues/24#issuecomment-623924068)
