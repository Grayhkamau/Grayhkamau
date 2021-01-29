# Bus Fare Challenge - Week 1

## Challenge

Write a program that does the following:

1. gets today's date and stores it in a variable `'date'`
2. uses today's date to get the name on the day of the week written in short form with the first letter capitalized eg. `'Fri'` if today were Friday and assigns it a variable `'day'`
3. uses if statements to determine the today's fare following these bus fare schedule:

   - monday - friday --> 100
   - saturday --> 60
   - sunday --> 80
4. Prints the results in this format  
    >Date:    2021-01-05  
    >Day:     Tue  
    >Fare:    100  

## Evaluation

Run the [Checker](checker.py) file to evaluate your code. If all tests pass, your code will be the correct solution. If any fail, check the error messages and make changes to your code and repeat.

## Note

1. Your solution must be written in the [bus_fare_challenge](bus_fare_challenge.py) file and its name should never be changed.  
2. Your program must make use of the following variable names:
   - `'date'`
   - `'day'`
   - `'fare'`  
*Failure to which all your tests will fail.*  
3. The **Checker** file should **never** be **altered** at any cost.


## bus fare solution pseudocode

date= today's date
day= print "day thur"

thursday="Day thur"
friday="Day: fri"
saturday="Day: sat"
sunday= "Day: sun"
monday="Day: mon"
tuesday="Day: tue"
wednesday="Day: wed"

if today_date =thursday
print "Date: 2020 1 28"
print "Day: thur"
print "fare: 100"

elif today_date =friday
print "Date: 2020 1 28"
print "Day: fri"
print "fare: 100"

elif today_date =saturday
print "Date: 2020 1 28"
print "Day: sat"
print "fare: 60"

elif today_date =sunday
print "Date: 2020 1 28"
print "Day: sun"
print "fare: 80"

elif today_date =monday
print "Date: 2020 2 1"
print "Day: mon"
print "fare: 100"
elif today_date =tuesday
print "Date: 2020 2 2"
      "Day: tue"
      "fare: 100"
else today_date =wednesday
print "Date: 2020 2 3"
      "Day: wed"
      "fare: 100"


