Download Link: https://assignmentchef.com/product/solved-cmsc403-chapter-12-problem-set
<br>
Create a Java program that uses monitors to control access to a Food Bank.  You will create a Food Bank class that has a food amount and methods to give and take food.  You will create two threads for this program that will with either put food into the food bank or take food from the food bank.  Food cannot be taken if there is no food available to take.  This is not a true producer/consumer problem.  You really only have one condition, which is to wait if there is no food available to take.  Both actions of giving and taking food will be monitors and will involve locking the lock object and unlocking it when done.  The methods to take and give food must print out exactly what is happening with each action in the method, i.e. “Waiting to get food”, “Taking 10 items of food, the balance is now 20 items”.

In your code, you will have two classes that are the taker of food and the giver of food.  The Taker class will have a run method that randomly generates a food amount to take from the Food Bank object and will call the method in the Food Bank class to take that amount from the Food Bank.  It will also print out exactly what it is doing each time its run method is called, i.e. “Submitting a request to get 10 items of food”.  The Giver class will have a run method that randomly generates a

food amount to give to the Food Bank object and will call the method in the Food Bank class to give that amount from the Food Bank.  It will also print out exactly what it is doing each time its run method is called.


