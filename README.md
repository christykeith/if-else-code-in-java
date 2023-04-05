# if-else-code-in-java

import java.util.Scanner;

public class Login {
    public static void main(String[] args) {
        // set the correct username and password
        String username = "myusername";
        String password = "mypassword";
        
        // prompt the user to enter their username and password
        Scanner input = new Scanner(System.in);
        System.out.print("Enter username: ");
        String user = input.nextLine();
        System.out.print("Enter password: ");
        String pass = input.nextLine();
        
        // check if the entered username and password are correct
        if (user.equals(username) && pass.equals(password)) {
            System.out.println("Login successful!");
        } else {
            System.out.println("Incorrect username or password.");
        }
    }
}
