# The-area-of-the-triangle
/*I created this code to find out the area of triangle which is useful for the students to have less time in solving the area of the triangle if the given height and breadth are in decimal number.*/


import java.util.Scanner;
public class vishal {
    public static void main(String[] args){
    Scanner scan = new Scanner(System.in);
    System.out.println("enter the height of the triangle");
        double a= scan.nextDouble();
    System.out.println("Enter the breadth of the triangle");
        double b = scan.nextDouble();
        
    System.out.print("the area of rectangle is " + 0.5*a*b);    
       
} 
}
