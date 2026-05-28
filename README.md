1. What is Programming Language 
 - A Language through which a Human is able to talk with the computer . Eg: Java, C++, Python, JavaScript 

2. What is Syntax in Programming 
 - The rules we have to follow in order to write code in that language, then only the computer able to userstand. If we write wrongly then it show Syntax Error in Programming 

3. Data type & Variable 
 - Data Type - Integer, Number, String, Boolean 
 - Variable - let, var, const

4. Keyword in programming Language(code word)
 - Special reserved words in the language 
 - There are special reserved words, wihich we can't use in programming language anything but for the purpose only 
 - Eg: if , else

5. Operators in Programming: 
 - Arithmetics Operators: +, -, *, /
 - Modulo: % (To find Remainder)
 - Increment Operator:  ++a (Prefix), a++ (Postfix) eg: a=10, ++a=10, a++=11
 - Decrement Operator: --a , a--
 - Logical Operators: 
 eg: && => And Pencil & Pen,
     || => Or black or blue pen only 

6. Conditional Statement
- To Excute some piece of code only when the condition is valid 
eg: A=5, Print code only when A is greater than 15.
if(a>15){
    Print
} else {

}

7. Looping Statements: n number of times if we wanna execute some piece of code, until the condition is meant. (keep executing the code until the condition is meant, In that we use looping statement)

8. Java is the Object Oriented Programming => Objects, Classes 

eg: // Humans - Talk,walk,think,(Template, blueprint)
// class => template, blurprint to create object (anything in java is reveled of object)
// Thenvanathi is object in the type of class Human

9. - byte, short, int, long - whole number 
   - float, double - Factional number 
   - char - "Hello"
   - String - 'Hello'
   - boolen - true or false (0 means false, 1 means true)

import java.util.Scanner;

class Main{
    public static void main(Sting[] args){
        System.out.println("Enter Input");
        Scanner scan = new Scanner(System.in);
        int num = scan.nextInt();
        System.out.println(num);
    }
}

- double num - nextDouble();
- String = nextLine();
- String = next() -> first 
         = next() -> second 
