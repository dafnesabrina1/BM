# BM
import java.util.Scanner;
public class BM {
	public static void main(String[] args){
		Scanner scanner = new Scanner(System.in);
		System.out.print("Enter a number: ");
		double number1 = scanner.nextDouble();
		double result = Math.sqrt(number1);
		System.out.println("The square root is: "+result);
	}

}
