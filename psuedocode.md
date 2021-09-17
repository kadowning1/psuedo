# Making Cup of Coffee - Kuerig

![Kuerig](img/107605441957745p.jpeg)

## Start

>>Functionality - User is wanting to make a cup of coffee.  User confirms power is on. User inserts KCUP.  User adds CoffeeMug.  User makes CoffeeCup. User decides to addSugar or not.  User decides to addCreamer or not.  User enjoys Coffee or not.

## Object/Data Structures

### Objects
* User
* Machine
* Display
    * Array of Ounces to tell Machine how much to dispense


### Variables for Machine
* Kuerig
* Pod
* Cup
* Cream
* Sugar
* Power
* Water
* User (for User Object)

### INIT
* CREATE Patron
* CREATE Kuerig
* CREATE KCup
* CREATE Water Level
* CREATE Coffee

### Program
* userPresent
* turnCoffeeOn
* addWater
* insertKCup
* addCoffeeMug
* makeCoffeeCup
* addSugar
* addCreamer
* turnCoffeeOff

### Functions
* Confirm user is present
* Insert KCUP
* Set size
* Add Water
* Brew Cup
* Add Sugar/Creamer

### Steps
1. Turn machine on - turnCoffeeOn
    * if machine = off
    * user submits "on"
2. Add Water -addWater
    * If water < minimum
        * add water
    * Else if water === max
        * alert User
    * else cup >= 2
        * add water < maximum
3. Insert new KCUP - insertKCup
    * if KCUP = 1
        * Discard
    * Replace with new KCUP
4. Place Mug Under Coffee Output/Machine - addCoffeeMug
5. Display alerts "Ready to Brew"
6. Set size (array of ounces) -- possible add of increment/decrement. 
    * INPUT ounces
        
        * 6: PRINT "6oz"
        * 8: PRINT "8oz"
        * 10: PRINT "10oz"
        * 12: PRINT "12oz"
        

    * Default Option
        * If you want 8oz
            * print oz = 8
        * Else if you want 10oz
            * print oz = 10
        * else if you want 12 oz
            * print oz = 12
        * else if you want 6oz
            * print oz = 6
7. Initiate Brew Coffee -makeCoffeeCup
8. Alert User "Machine Hot, Do Not Interupt!"
9. Machine dispenses ozs from #5 array
10. Add Sugar -addSugar
    * If sugar = false (0)
        * Skip/End
    * If sugar = true (>= 1)
        * Add Sugar (Amount)
11. Add Creamer - addCreamer
    * If creamer = false (0)
        * Skip/End
    * If creamer = true (>= 1)
        * Add Creamer (amount)
12. Stir Coffee
    * if all contents added 
        * then stir coffee
13. Enjoy Coffee
    * IF not enjoyed
        * Repeat from step 2
    * ELSE
        * end program
14. User turns off coffee machine - turnCoffeeOff

### End

* Possible additions/stretch
    * Boolean 
        * Coffee
            * If Coffee == false (not like it)
            return zero (end process)
        * Power
            * on = true; off = false;
    * Add Clean Function
        * if makeCoffeeCup > (num) THEN clean machine 
    * Heating Element
        
    