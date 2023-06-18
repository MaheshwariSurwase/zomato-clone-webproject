# Abstract
                                       
  Our website is an online food ordering system that enables ease for the customers. It overcomes the disadvantages of the traditional queueing system.  Our proposed system is a medium to order online food hassle free from restaurants . This system improves the method of taking the order from customer. The online food ordering system sets up a food menu online and customers can easily place the order as per their wish. Also with a food menu. 
  This system also provides a review system in which user can rate the food items and the delivery. Also, the proposed system can recommend hotels, food, based on the ratings given by the user, the hotel staff will be informed for the improvements along with the quality. The payment can be made online by upi, card, wallet
  
#  Introduction
## About Project:
Online food ordering system is a web-based restaurant
management application with order booking functionality. It connects 
clients, restaurants, and stylists in an online community allowing users to 
browse restaurants, and food Order. User can see the overview of a 
restaurants. Users can also give and read reviews of restaurants given by 
other Users. User can also see menu photos and restaurant photos . 
Our application includes Some of the major use cases user 
account registration, login/logout, food ordering , view Orders ,manage 
cart, give review of food orders at customer side and payment . 
## Technology:
My project uses MongoDB Atlas and Express-js to backend the 
interface is created with React Framework as frontend. Online food 
ordering system integrates AWS technology as a cloud storage for 
Dynamic image upload, google map picker for view map , Google cloud 
console for Google Authentication , razorpay for payment . This project 
will target the major web browsers as the initial platform.
## Tools:
- Visual Studio Code (editor)
- MongoDb compass
- Github

# SOFTWARE REQUIREMENTS SPECIFICATION (SRS)
# Online Food Ordering System 
## Functional Requirement :
### 1. User Side : 
#### 1.1 Authentication : 
Description :- If user is new to the system then First he/she 
must sign up to the system otherwise user can directly 
login and then enter to the system.
#### 1.1.1: Sign Up
Input: User details.
Process: Validate details.
Output: Redirect to home page.
#### 1.1.2: Sign In
Input: User details.
Process: Validate details.
Output: Redirect to Home page.
#### 1.1.3: Log Out
Input: User Selection.
Output: Redirect to Home page.
#### 1.2 Restaurant Details :
Description : as per user selection system shows restaurant 
details view .
#### 1.2.1: Overview : 
Input : User Selection .
Output : Show Restaurant details .
#### 1.2.2: Food Items :
Input : User selection .
7
Output : List of food Items .
#### 1.3 Manage Cart :
Description : The Customer Can View Their Selected
Food item And Can Add New food As Well As Delete The 
food from cart
#### 1.3.1: Add Food :
Input : Select food .
Output : Cart Will be updated (added food in cart ) .
#### 1.3.1: Remove Food :
Input : Select food .
Output : Cart Will be updated (Remove food )
#### 1.3.1: Place order :
Description : Customer has to Select Address details 
To Place order
Input : Select Address .
Output : Direct to the Payment page .
#### 1.3 Manage Payment :
Description : The Customer Can Pay With The many
Modes Of Payment like Netbanking , through Cards , Upi , 
wallet etc .
#### 1.3.1: Payment using Net-banking:
Input : Bank details.
Process : Validate details
Output : Confirmation Message.
#### 1.3.2: Payment using Card :
Input : Card-No, Expiry-Date, Card-Holder No , CVV.
Process: Validate details
Output : Confirmation Message.
8
#### 1.3.3: Payment using Upi :
Input : Enter Upi-id.
Process: Validate details
Output : Confirmation Message.
#### 1.3.4 Payment using Wallet :
Input : Select a wallet.
Process: Validate details
Output : Confirmation Message.
#### 1.3.5 Pay Later :
Input : Select a method.
Process: Validate details
Output : Confirmation Message.
#### 1.4. Manage Reviews :
Description : Customers Can View As Well As Give The 
Reviews And Ratings On The Quality Of Food .
#### 1.4.1 Add Review :
Input : Review And Rating
Output : Confirmation
#### 1.4.2 View Review :
Output : View The Review .
9
# Non Functional Requirement :-
N-1 Database :- A database should be there to store the data.
N-2 Availability :- our system should be available at all times.
N-3 System Independence :- our website should be platform independent. It 
should work on all the platforms.
N-4 device independence :- our website should work on all kinds of smart 
devices.
N-4 Privacy :- Personal data of the customers should not be disclosed to 
anyone.
N-5 Maintainability :- our system should work 24x7 and should be maintained 
properly

![1](https://github.com/MaheshwariSurwase/zomato-clone-webproject/assets/97899505/caa617e6-df87-48da-8c06-1bb267070b06)
