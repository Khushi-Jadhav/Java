import java.util.Scanner;
public class Age {

    public static void main(String[] args){

        System.out.println("Hello");

        Scanner input=new Scanner(System.in);
        
        int age;
        System.out.println("Enter the age :");
        age=input.nextInt();
        System.out.println("Your Age is "+age);

        System.out.println("Enter the average :");
        double average = input.nextDouble();
        System.out.println("Your Average is "+average);
        
        input.close();
    }
}
