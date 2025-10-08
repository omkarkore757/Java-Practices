
 1. Print "Hello, World"
 public class HelloWorld {
 public static void main(String[] args) {
 System.out.println("Hello, World!");
 }
 }
 
 2. Add Two Numbers
 public class AddNumbers {
 public static void main(String[] args) {
 int a = 10, b = 20;
 int sum = a + b;
 System.out.println("Sum: " + sum);
 }
 }
 
 3. Check Even or Odd
 public class EvenOdd {
 public static void main(String[] args) {
 int num = 7;
 if (num % 2 == 0)
 System.out.println("Even");
 else
}
 System.out.println("Odd");
 }
 
 4. Reverse a String
 public class ReverseString {
 public static void main(String[] args) {
 String str = "Selenium";
 String rev = "";
 for (int i = str.length() - 1; i >= 0; i--) {
 rev = rev + str.charAt(i);
 }
 System.out.println("Reversed: " + rev);
 }
 }
 
 5. Find Largest of Three Numbers
 public class LargestNumber {
 public static void main(String[] args) {
 int a = 25, b = 78, c = 87;
 if (a > b && a > c)
 System.out.println("Largest: " + a);
 else if (b > c)
 System.out.println("Largest: " + b);
 else
}
 System.out.println("Largest: " + c);
 }
 
 6. Print a Table of a Number
 public class Table {
 public static void main(String[] args) {
 int num = 5;
 for (int i = 1; i <= 10; i++) {
 System.out.println(num + " x " + i + " = " + (num * i));
 }
 }
 }
 
  7. Count Vowels in a String
 public class VowelCount {
 public static void main(String[] args) {
 String str = "Automation";
 int count = 0;
 for (int i = 0; i < str.length(); i++) {
 char ch = Character.toLowerCase(str.charAt(i));
 if (ch == 'a' || ch == 'e' || ch == 'i' || ch == 'o' || ch == 'u')
 count++;
 }
}
 System.out.println("Vowels count: " + count);
 }
 
 8. Check if String is Palindrome
 public class Palindrome {
 public static void main(String[] args) {
 String str = "madam", rev = "";
 for (int i = str.length() - 1; i >= 0; i--) {
 rev = rev + str.charAt(i);
 }
 if (str.equals(rev))
 System.out.println("Palindrome");
 else
 System.out.println("Not Palindrome");
 }
 }
 
 9. Factorial of a Number
 public class Factorial {
 public static void main(String[] args) {
 int num = 5, fact = 1;
 for (int i = 1; i <= num; i++) {
 fact *= i;
}
 System.out.println("Factorial: " + fact);
 }
 }
 
 10. Fibonacci Series
 public class Fibonacci {
 public static void main(String[] args) {
 int n = 10, a = 0, b = 1;
 System.out.print(a + " " + b + " ");
 for (int i = 2; i < n; i++) {
 int next = a + b;
 System.out.print(next + " ");
 a = b;
 b = next;
 }
 }
 }
