# Java Basics & fundamentals - 4-11-26

# # What this covers
This log documents the fundamental rules of java programming ,focusing on variable naming conventions, basic I/0 operations using this Scanner class, single and multiline comments, and the arithmetic behavior of the modulus operator.


# # Key Concepts

* Variable Naming Rules: Identifiers must start with an alphabet letter or '$'.Special characters (except "-" and "$"),-,",",keywords, and leading numbers are not permitted.
* Scanner Input: Reading dynamic user inputs using 'Scanner sc = new Scanner(System.in); and obtaining primitive data types using methods like "nextInt()' and 'nextDouble()'.
* Comments: Writing inline notes using '//' for single-line comments and '/*../*' for multi-line comments.
* Modulus Operator Properties: Computing remainders using '%',understanding behavior when $a < b$ (yields $a$),and evaluating expressions involving negative operands.

* ## Commands used
* 
* //Variable Naming Examples
* int x = 3;
* //Valid: GEEKYGRAPHY, _basic, Public, publicx, accheVariableNames
* //Invalid: raghav-garg,#MEAN, group@, geeks for geeks, Raghav"students, 420

* //User Input Handling
* import java.util.Scanner;
* Scanner sc = new Scanner(System.in);
  System.out.println("Enter radius");
  double r = sc.nextDouble();  //Correct method for double input

  //Module Operator (%) Calculations
  int rem1 = 5 % 6; //Output : 1
  int rem2 = 5 % 3; //Output: 2
  int rem3 = 2 % 4 //Property 1 : a % b = a if a < b ->Output: 2
  
  
WHAT I LEARNED

Today I learned Java variable naming rules,how to take user input using Scanner class, and how to write  single-line and multi-line comments.I also learned how to use the modulus (%) operator to find remainders,including calculations with negative numbers.what happens when the first number is smaller than the second number.
