import java.util.Scanner;
public class ReadAndPri
nt {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Prompt the user to enter some text
        System.out.print("Enter something: ");
        String input = scanner.nextLine();

        // Print the entered text
        System.out.println("You entered: " + input);

        scanner.close();
    }
}


 
OUTPUT:

PS C:\Users\MY\OneDrive\Pictures\Documents\java emc 1>  'C:\Users\MY\AppData\Roaming\Code\User\workspaceStorage\09ba20b68fc885bcf32d210e84cb47ec\redhat.java\jdt_ws\java emc 1_2ecfe798\bin' 'ReadAndPrint' 
Enter something: java program is complex
You entered: java program is complex
PS C:\Users\MY\OneDrive\Pictures\Documents\java emc 1> 


