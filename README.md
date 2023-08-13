# Print_Numbers_Using_Java
Programming Techniques 
Java has been used by numerous companies and organizations for various purposes, including web development, software applications, mobile apps, server-side development, and more. Some notable companies that have used Java include:
Microsoft: While C# is Microsoft's primary programming language, Java is used in various contexts within Microsoft, including Minecraft, Azure services, and more.
Google: Java is used extensively in various Google products, including the Android operating system, which is primarily built using Java.

1)Print Name:

class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Farid");
    }
}
Output:
Farid
 
2)Print 0 to 9 numbers:

class HelloWorld {
    public static void main(String[] args) {
        System.out.println("123456789");
    }
}
Output:
123456789
 


3)Print 0 to 9 numbers using FOR loop:

public class PrintNumbers {
    public static void main(String[] args) {
        for (int i = 0; i <= 8; i++) {
            System.out.println(i);
        }
    }
}
Output:
0
1
2
3
4
5
6
7
8
 
4)Print 0 to 99 numbers using WHILE loop:

public class PrintNumbers {
    public static void main(String[] args) {
        int i = 0;
        while (i <= 98) {
            System.out.println(i);
            i++;
        }
    }
}
Output:
 

5)User input print start number to 99 end number:

 import java.util.Scanner;

public class PrintNumbers {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("Enter a number: ");
        int startNumber = scanner.nextInt();
        
        for (int i = startNumber; i <= startNumber + 99; i++) {
            System.out.println(i);
        }
        
        scanner.close();
    }
}

 

