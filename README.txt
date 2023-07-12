1) Import essential classes
2) Write the constructor that takes 4 arguments
	customer , which is an instance of Customer class and contains custumer’s personal data (name, surname, etc.)
	date, which is an instance of date class
	time which is an instance of time class
	currency which is an instance of currency class
   After checking types and values of given arguments assign them to corresponding data members and and other essential data members
	locked _until, which will be used to set the time until when is the bank account locked
	Login_attempts - will be used for verification, indicates how many times the user has tried to log into their for under some conditions
	__transactions_history - this will be a list, that contains objects that are instances of Transaction class and contain information about transactions made with current account
	__deposits - will contain information about deposits 
	_limit - defines the max amount that can be used in one transaction, by default its value is 1000 USD
3) Add __repr__ to return what will be show when printing the instance of BankAccount class
4) Add a methos for verification. After 3 wrong attempts in a row the account will be locked for 5 minutes
5) Transfer_to_another_account - does all essential type and value checks, makes the transaction and adds information to __transactions data member
6) Add magic methods __add__ and __sub__ to add and withdraw money from account
7) Deposit - a method that adds the deposit and shows current balance and the balance after given period 
8) Add calculate_interest method, which gets 2 arguments
	Interest_rate - an instance of Rational class
	Time_period 
10) Add methods to freeze and activate account
11) Write a function to return the current balance of the account
12) Add a function to return Transactions’ information (transaction amount, description, status and time when it was made)
13) Add methods to get and set limit the max amount that can be used in one transaction
14) Write a function for password change
