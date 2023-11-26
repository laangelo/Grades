import java.util.Scanner;
public class Grades{
public static void main(String[]args){

Scanner object = new Scanner(System.in);
System.out.println("Enter marks for javaprogramming");
double javaprogrammingMarks = object.nextDouble();

//get networking marks
System.out.println("Enter marks for Networking");
double networkingMarks = object.nextDouble();

//getting maths marks
System.out.println("Enter marks for maths");
double mathsMarks =object.nextDouble();

//calculate average marks
double averageMarks = (javaprogrammingMarks + networkingMarks + mathsMarks)/3;

//Display marks and average
System.out.println("Marks for javaprogramming is" + javaprogrammingMarks);
System.out.println("Marks for networking is" + networkingMarks);
System.out.println("Marks for maths is" + mathsMarks);
System.out.println("The average is" + averageMarks);
}
}

