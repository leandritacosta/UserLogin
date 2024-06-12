# UserLogin
Simple user login in Java :)



    import java.util.Scanner;
    
    public class userlogin  {  
    public static void main(String[] args)  { 
    
     Scanner input = new Scanner(System.in);
        
        System.out.print("Enter your email: ");
        String email = input.nextLine();
        
        System.out.print("Enter your password: ");
        String password = input.nextLine();
       
        System.out.println("Email: " + email);
        System.out.println("Password: " + password);         
    
    input.close();
        
    }
    }
