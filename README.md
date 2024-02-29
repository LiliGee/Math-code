import java.util.Scanner;
import java.math.*;
public class Math {

	public static void main(String[] args) {
		Scanner input = new Scanner(System.in);
		System.out.println("Enter x value: ");
		double x = input.nextDouble();
		System.out.println("Enter y value: ");
		double y = input.nextDouble();
		
		
		double z = java.lang.Math.sqrt((x*x)+(y*y));
		System.out.println("The hypotenuse of the triangle is equal to: " + z);
	}
}
