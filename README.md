# hello-world
Olvin's New Repository

Hello Humans,

I am new to Git, and I look forward to using this tool in the future.

Here's my Pre-Work submission.


package ReverseNumber;

import java.util.Scanner;

public class ReverseNumber {

	public static void main(String[] args) {
		/*Must import java Scanner from existing library, in order to prompt user to input int*/
		
		Scanner scanner = new Scanner(System.in);
		
		System.out.println("Enter number value to compute its reverse : ");
		//See comment above regarding user's input
		
		int original = scanner.nextInt();
		int reverse = 0;
		int remainder;
		
		//original = 476; original = 254; original = 908
		
		while(original != 0)   {
			
			remainder = original % 10; 
			reverse = reverse * 10 + remainder;
			original = original / 10;
			
			/*This loop will continue until "original = 0", in which the loop will terminate */
			
				}
		
		System.out.println("Reverse of number is : " + reverse);
		
	}

}
