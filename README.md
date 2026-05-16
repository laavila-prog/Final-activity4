# Final-activity4
<?php
$age = 18;

if ($age >= 18) {
    echo "You are eligible to vote";
}
?>
<?php
$number = -5; // example number

if ($number > 0) {
    echo "Positive number";
} else {
    echo "Negative number";
}
?>
<?php
$grade = 85; // example grade

if ($grade >= 90 && $grade <= 100) {
    echo "Excellent";
} elseif ($grade >= 80 && $grade <= 89) {
    echo "Good";
} elseif ($grade >= 70 && $grade <= 79) {
    echo "Average";
} else {
    echo "Failed";
}
?>
# Input a number
number = int(input("Enter a number: "))

# Check if even or odd
if number % 2 == 0:
    print("Even")
else:
    print("Odd")
# Input three numbers
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

# Find the largest number
if a >= b and a >= c:
    print("Largest number is:", a)
elif b >= a and b >= c:
    print("Largest number is:", b)
else:
    print("Largest number is:", c)
# Fixed password
password = "admin123"

# User input
user_input = input("Enter password: ")

# Check password
if user_input == password:
    print("Access Granted")
else:
    print("Access Denied")
# Input year
year = int(input("Enter a year: "))

# Check if leap year
-if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
    print(year, "is a Leap Year")
else:
 <?php
$day = 3;

switch($day){
    case 1:
        echo "Monday";
        break;
    case 2:
        echo "Tuesday";
        break;
    case 3:
        echo "Wednesday";
        break;
    case 4:
        echo "Thursday";
        break;
    case 5:
        echo "Friday";
        break;
    case 6:
        echo "Saturday";
        break;
    case 7:
        echo "Sunday";
        break;
    default:
        echo "Invalid input";
}
?>
   print(year, "is not a Leap Year")

<?php
$grade = "B";

switch($grade){
    case "A":
        echo "Excellent";
        break;
    case "B":
        echo "Very Good";
        break;
    case "C":
        echo "Good";
        break;
    case "D":
        echo "Passing";
        break;
    case "F":
        echo "Failed";
        break;
    default:
        echo "Invalid Grade";
}
?>
<?php
$num1 = 10;
$num2 = 5;
$operator = "+";

switch($operator){
    case "+":
        echo "Answer: " . ($num1 + $num2);
        break;

    case "-":
        echo "Answer: " . ($num1 - $num2);
        break;

    case "*":
        echo "Answer: " . ($num1 * $num2);
        break;

    case "/":
        if($num2 != 0){
            echo "Answer: " . ($num1 / $num2);
        } else {
            echo "Cannot divide by zero";
        }
        break;

    default:
        echo "Invalid Operator";
}
?>
<?php
echo "MENU\n";
echo "1 = Add\n";
echo "2 = Edit\n";
echo "3 = Delete\n";

$choice = readline("Enter your choice: ");

switch($choice) {
    case 1:
        echo "You selected Add";
        break;

    case 2:
        echo "You selected Edit";
        break;

    case 3:
        echo "You selected Delete";
        break;

    default:
        echo "Invalid choice";
}
?>
<?php
$month = readline("Enter month number (1-12): ");

switch($month) {
    case 1:
        echo "January";
        break;

    case 2:
        echo "February";
        break;

    case 3:
        echo "March";
        break;

    case 4:
        echo "April";
        break;

    case 5:
        echo "May";
        break;

    case 6:
        echo "June";
        break;

    case 7:
        echo "July";
        break;

    case 8:
        echo "August";
        break;

    case 9:
        echo "September";
        break;

    case 10:
        echo "October";
        break;

    case 11:
        echo "November";
        break;

    case 12:
        echo "December";
        break;

    default:
        echo "Invalid month number";
}
?><?php
$month = readline("Enter month number (1-12): ");

switch($month) {
    case 1:
        echo "January";
        break;

    case 2:
        echo "February";
        break;

    case 3:
        echo "March";
        break;

    case 4:
        echo "April";
        break;

    case 5:
        echo "May";
        break;

    case 6:
        echo "June";
        break;

    case 7:
        echo "July";
        break;

    case 8:
        echo "August";
        break;

    case 9:
        echo "September";
        break;

    case 10:
        echo "October";
        break;

    case 11:
        echo "November";
        break;

    case 12:
        echo "December";
        break;

    default:
        echo "Invalid month number";
}
?>
<?php
$month = readline("Enter month number (1-12): ");

switch($month) {
    case 1:
        echo "January";
        break;

    case 2:
        echo "February";
        break;

    case 3:
        echo "March";
        break;

    case 4:
        echo "April";
        break;

    case 5:
        echo "May";
        break;

    case 6:
        echo "June";
        break;

    case 7:
        echo "July";
        break;

    case 8:
        echo "August";
        break;

    case 9:
        echo "September";
        break;

    case 10:
        echo "October";
        break;

    case 11:
        echo "November";
        break;

    case 12:
        echo "December";
        break;

    default:
        echo "Invalid month number";
}
?>
<?php
$month = readline("Enter month number (1-12): ");

switch($month) {
    case 1:
        echo "January";
        break;

    case 2:
        echo "February";
        break;

    case 3:
        echo "March";
        break;

    case 4:
        echo "April";
        break;

    case 5:
        echo "May";
        break;

    case 6:
        echo "June";
        break;

    case 7:
        echo "July";
        break;

    case 8:
        echo "August";
        break;

    case 9:
        echo "September";
        break;

    case 10:
        echo "October";
        break;

    case 11:
        echo "November";
        break;

    case 12:
        echo "December";
        break;

    default:
        echo "Invalid month number";
}
?>
<?php
$month = readline("Enter month number (1-12): ");

switch($month) {
    case 1:
        echo "January";
        break;

    case 2:
        echo "February";
        break;

    case 3:
        echo "March";
        break;

    case 4:
        echo "April";
        break;

    case 5:
        echo "May";
        break;

    case 6:
        echo "June";
        break;

    case 7:
        echo "July";
        break;

    case 8:
        echo "August";
        break;

    case 9:
        echo "September";
        break;

    case 10:
        echo "October";
        break;

    case 11:
        echo "November";
        break;

    case 12:
        echo "December";
        break;

    default:
        echo "Invalid month number";
}
?><?php
$month = readline("Enter month number (1-12): ");

switch($month) {
    case 1:
        echo "January";
        break;

    case 2:
        echo "February";
        break;

    case 3:
        echo "March";
        break;

    case 4:
        echo "April";
        break;

    case 5:
        echo "May";
        break;

    case 6:
        echo "June";
        break;

    case 7:
        echo "July";
        break;

    case 8:
        echo "August";
        break;

    case 9:
        echo "September";
        break;

    case 10:
        echo "October";
        break;

    case 11:
        echo "November";
        break;

    case 12:
        echo "December";
        break;

    default:
        echo "Invalid month number";
}
?>
<?php
$month = readline("Enter month number (1-12): ");

switch($month) {
    case 1:
        echo "January";
        break;

    case 2:
        echo "February";
        break;

    case 3:
        echo "March";
        break;

    case 4:
        echo "April";
        break;

    case 5:
        echo "May";
        break;

    case 6:
        echo "June";
        break;

    case 7:
        echo "July";
        break;

    case 8:
        echo "August";
        break;

    case 9:
        echo "September";
        break;

    case 10:
        echo "October";
        break;

    case 11:
        echo "November";
        break;

    case 12:
        echo "December";
        break;

    default:
        echo "Invalid month number";<?php
$month = readline("Enter month number (1-12): ");

switch($month) {
    case 1:
        echo "January";
        break;

    case 2:
        echo "February";
        break;

    case 3:
        echo "March";
        break;

    case 4:
        echo "April";
        break;

    case 5:
        echo "May";
        break;

    case 6:
        echo "June";
        break;

    case 7:
        echo "July";
        break;

    case 8:
        echo "August";
        break;

    case 9:
        echo "September";
        break;

    case 10:
        echo "October";
        break;

    case 11:
        echo "November";
        break;

    case 12:
        echo "December";
        break;

    default:
        echo "Invalid month number";
}
?>
<?php
$month = readline("Enter month number (1-12): ");

switch($month) {
    case 1:
        echo "January";
        break;

    case 2:
        echo "February";
        break;

    case 3:
        echo "March";
        break;

    case 4:
        echo "April";
        break;

    case 5:
        echo "May";
        break;

    case 6:
        echo "June";
        break;

    case 7:
        echo "July";
        break;

    case 8:
        echo "August";
        break;

    case 9:
        echo "September";
        break;

    case 10:
        echo "October";
        break;

    case 11:
        echo "November";
        break;

    case 12:
        echo "December";
        break;

    default:
        echo "Invalid month number";
}
?>

}
?>
