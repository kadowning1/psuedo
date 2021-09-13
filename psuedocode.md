Start

Variables
-Kuerig
-Pod
-Cup
-Cream
-Sugar
-Power
-Water

Program
makeCoffeeCup

Functions
-Insert KCUP
-Set size
-Brew Cup
-Add Sugar/Creamer

Steps
1. Turn machine on
2. Add Water
    If water < minimum
        add water
    else if cup >= 2
        add water = maximum
3. Insert new KCUP
    if KCUP = 1
    Discard
    Replace with new KCUP
4. Place Cup Under Coffee Output/Machine
5. Set size (array of ounces) -- possible add of increment/decrement
    a.  INPUT ounces
        case ounces of 
        6: PRINT "6oz"
        8: PRINT "8oz"
        10: PRINT "10oz"
        12: PRINT "12oz"
        ENDCASE

    b.
        If you want 8oz
        print oz = 8
        Else if you want 10oz
        print oz = 10
        else if you want 12 oz
        print oz = 12
        else if you want 6oz
        print oz = 6
6. Hit Brew Coffee
7. Add Sugar
    If sugar = false (0)
    Skip
    If sugar = true (>= 1)
    Add Sugar (Amount)
8. Add Creamer
    if creamer = false (0)
    Skip
    if creamer = true (>= 1)
    add Creamer (amount)
9. Stir Coffee
10. Enjoy Coffee
    if not enjoyed
    Repeat from step 2

End

--Possible additions
    -Boolean Coffee
        -If Coffee == false (not like it)
         return zero (end process)
    