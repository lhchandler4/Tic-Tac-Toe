# Tic-Tac-Toe
Full Cloud Deployment Pipeline of Tic Tac Toe

## Instructions
### Download the Required Packages
1. Install Python (https://www.python.org/downloads/) preferably 2.7
2. Install Flask and AWS SDK for Python (Boto) using the Python Package Installer (PIP)
    - PIP can installed (9https://pip.readthedocs.io/en/stable/installing/) 
        - when installing PIP make sure you are working as an administrator (sudo)
    - In the terminal type```python.exe get-pip.py```
    - Install Flask and Boto ```pip install Flask```
                             ```pip install boto```
                             ```pip install configparser ```
3. Set up a local DynamoDB (https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/DynamoDBLocal.html)
4. Go to the desired location in the terminal and clone the tic-tac-toe application repository. In the terminal type:
 ```git clone https://github.com/awslabs/dynamodb-tictactoe-example-app.git```   

### Testing the Game Application
1. Start DyanamoDB locally
2. In your terminal type ```python application.py --mode local --serverPort 5000 --port 8000 ```
    - got to localhost:5000 in your browser
3. 
