# Beginner
The New Quantum Programming Basics.

Install Qiskit by the command pip install qiskit.
Go To "https://www.ibm.com/in-en"
create a ibmid account in IBM official Page
Then Log in to "https://quantum-computing.ibm.com" the official IBM Q Experience website
Use the ibmid to log in 
Then in right corner you find a button for your Account
Click that button and go to My Accounts
In My Account a unique token is generated 
Copy that token and paste in the code in the place of "MY_API_TOKEN"
Code follows

from qiskit import IBMQ
IBMQ.save_account('MY_API_TOKEN')

Run this Program before you code in qiskit
