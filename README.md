# Lavasa Food Ordering System

## Submitted by
1. Simran Adwani (Reg no. 22112335) (add github profile link)
2. Homita Ganguly (Reg no. 22112314) (add github profile link)

## Description
This is a basic Python "food ordering project" that allows users to create a personal account and place food orders from various restaurants located in Lavasa, Pune and their menus and calculates the total cost of the order, gives the user options of view cart to view order summary, checkout to make payment and lastly an option to quit the program. The project provides a simple command-line interface (CLI) for users to interact with.

## Features
* Allows user to login if an account exists by entering valid username and password otherwise allows user to create a personal account
   * with unique username
   * with validated password
* Allows user to place an order
   * allows user to select restaurants from given options
   * allows user to select items and quantities from the available category of food and  based on the selected restaurant
   * allows user to see the order summary including specific items and their quantities and final price
   * allows uset to make payment
* Allows user to quit the program with or without ordering any item

## Functionality
1. class User : A class providing user information which includes name, adress and payment information
2. class Order : A class to represent the order of an user which includes user details, items and total cost
3. Packages imported: 
   * csv: To read and edit the "user" csv file and to read from the "menu" csv file
   * pandas: To display the order summary in a structured format
   * random: To randomly assign delivery boys and generate delivery timings.
   * os (readlink): To read the value of symbolic link and return the path it points to.
   * simple_colors: To enhance/beautify the command line interface.
4. Functions defined: 
   * Used for creating user account interface:
      * is_user_exists(username)  
      * create_user_account(x,y) 
      * validate_password(password) 
      * login_user(username, password)  
   * Used for creating the main menu and ordering interface:
      * load_menu() 
      * display_categories(menu) 
      * display_menu_items(menu, restaurant, category) 
      * calculate_order_price(order, menu) 
      * view_cart(order)
      * assign_delivery_boy(delivery_boys, order)
      * checkout(order)
      * generate_order_summary(order, delivery_boy)
   * Used for exiting the program: 
      * exit_program() 

## Requirements 
1. Ensure the menu dataset file (menu.csv) is in the desired directory.
2. Ensure the users dataset file (users.csv) is in the desired directory. 
3. 


## Usage
1. Clone this repository to your local machine or download the source code.
2. Open a terminal or command prompt and navigate to the project directory.
3. Run the following command to start the food ordering system: (to be written)(name at command prompt (eg. python, py or conda) after importing the collab or jupyter file)
4. Follow the prompts in the CLI to select food items, quantities, and provide any special instructions or dietary restrictions.
5. Once you have completed your order, the system will keep on giving you the following options : 
   1. Browse the menu
   2. View my cart
   3. Checkout
   4. Quit
hence you can select from the options and go on to view order summary using 'view my cart' or pay using 'checkout' and lastly exit the program using 'quit' which will show you "____________________*Thank you for using our food ordering system! Please visit again!*____________________"  

## Sample Output
Here is an example of how the CLI would look:
* User Account: (add ss)
* Order : (add ss)



