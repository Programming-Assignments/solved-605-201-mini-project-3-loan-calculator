Download Link: https://assignmentchef.com/product/solved-605-201-mini-project-3-loan-calculator
<br>
The purpose of this project is to provide non-trivial practice in the use of Java objectoriented GUI programming features to implement an object-oriented GUI design and have a bit of fun doing it.

<strong>Resources Needed: </strong>

You will need a computer system with Java 7 or greater SE edition run-time and Java

Development Kit (JDK). You may optionally use a Java IDE for example NetBeans, Eclipse, etc.

<strong>Submitted Files: </strong>

Source files:

Each public class <em>must</em> be contained in a separate Java source file.

The format of the Java source must meet the general Java coding style guidelines discussed so far during the course. Pay special attention to naming guidelines, use of appropriate variable names and types, variable scope (public, private, protected, etc.), indentation, and comments. Please use course office hours or contact the instructor directly if there are any coding style questions.

<strong>Collaboration: </strong>

It is encouraged to discuss technical or small design parts of this project with your fellow students. However, the resulting design and implementation must be your own. For example, it is acceptable to discuss different ways of maintaining the system state but not detailed design or implementation information on processing the purchase command. When in doubt, ask during office hours or contact your instructor.

<strong>Program Specification: </strong>

This project involves implementing a Java program that performs a calculation of payments associated with loans. The program shall allow a user to enter the following data: annual interest rate, the term of the loan (i.e., number of years), and the loan amount. A GUI like the one below must be used.

When the user presses the calculate button, the monthly payment and total amount of payments shall be displayed.

The formula for computing the monthly payment (<em>P</em>) is:

i  A

1−(1+ i)<sup>-n </sup>




where <em>i</em> = periodic interest rate, <em>A</em> = amount of loan, <em>n</em> = number of compounding periods (12).




For example, if the annual interest rate is 5 percent, the term of the loan is 2 years, and the loan amount is $2,000, and interest is compounded monthly:




i = .05/12 = .00417 n = 2 * 12 = 24 P = $87.74 Total Payment = 24 * $87.74







Requirements are WHAT the program performs.  Design describes HOW the program meets the requirements.  If you are exactly performing what the assignment states with no changes the requirements can be a copy, summary, or list of the stated assignment requirements.  If you are adding more functionality please state what you are adding. Design can be captured in a UML Diagram, a tool created diagram (Powerpoint, Visio, etc), hand drawn on paper diagram, or a written paragraph describing how the program is designed to meet the requirements.  The design can be minimal such as one diagram or one short paragraph. You should always capture requirements and design before starting to implement in code.  Submit the requirements, design, source code and screen shots of each program’s output in a zip file named as follows:  Project3 followed by an underscore (_) followed by your first name initial, followed by your last name, followed by your course section number. For example, if your name is Jane Smith and you are in section 81 your zip file would be <em>Project3_jsmith81.zip</em>.














