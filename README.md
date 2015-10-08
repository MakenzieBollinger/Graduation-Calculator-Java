# Graduation-Calculator-Java

import java.util.Scanner;

	public class GraduationCalculator {
		public static void main(String[] args){
			int num1, num2, total, hoursRequired;
			Scanner keyboard = new Scanner(System.in);
			System.out.println("Welcome to the UNC Graduation Calculator!");
			System.out.println("How many credit hours have you taken up until this semester?");
			num1 = keyboard.nextInt();
			System.out.println("How many credit hours are you enrolled in this semester?");
			num2 = keyboard.nextInt();
			total = num1 + num2;
			System.out.println("You have taken " + total + " total hours.");
			hoursRequired = (total - 120);
			System.out.println("You have " + hoursRequired + " hours left before you can graduate");
			
			
		}
	}
