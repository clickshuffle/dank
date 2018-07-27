# dankpackage lmao;
import java.util.Scanner;


public class donuts {
	public static void main(String args[]) {
	    startNode();
	    }
	    
	    public static void startNode(){
	        Scanner keyboard = new Scanner(System.in);
	    
	    System.out.print("Homer Simpson is laying on the couch at home. Use 1 or 2 to progress through the game. Press ENTER to continue.");
	    keyboard.nextLine();
	    donut();
	    }
	    
	    public static void donut(){
	    Scanner keyboard = new Scanner(System.in);
	    System.out.println("He wants to get a donut from the kwik e mart. What does he do?");
	    System.out.println("1) Goes to the Kwik e mart to buy a donut");
	    System.out.println("2) Gets Bart or Lisa to get his donut");
	    System.out.println("3) Calls the kwik e mart to deliver his donut");
	    
	    int userInput = keyboard.nextInt();
	    try {
	        if(userInput == 1){
	            kwik();
	        } else if (userInput == 2){
	            bart();
	        } else if (userInput == 3){
	            call();
	        }
	    } catch {
	        System.out.println("GAME OVER. PRESS ENTER TO RESTART");
	        keyboard.nextLine();
	        donut();
	        }
	    }
	    
	    public static void kwik(){
	     Scanner keyboard = new Scanner(System.in);
	     System.out.println("How does he go to the Kwik E Mart?");
	     System.out.println("1) His car");
	     System.out.println("2) Uses Marge's car");
	     System.out.println("3) Walks to the Kwik E Mart");
	     
	     int userInput = keyboard.nextInt();
	    if(userInput == 1){
	        Car();
	    } else if (userInput == 2){
	        Car();
	    } else if (userInput == 3){
	        Car();
	    } else {
	        System.out.println("INVALID INPUT. GAME OVER. PRESS ENTER TO RESTART");
	        keyboard.nextLine();
	        startNode();
	    }
	    }
	    public static void bart(){
	       Scanner keyboard = new Scanner(System.in);
	       System.out.println("Homer gets off the couch and goes to the stairs. How does he get Bart or Lisa to get him the donut?");
	       System.out.println("1) He shouts the heck out of them");
	       System.out.println("2) He goes upstairs to try and find them");
	       System.out.println("3) He somehow can speak to dogs and tells it to go and get one of them");
	        
	        int userInput = keyboard.nextInt();
	    if(userInput == 1){
	        System.out.println("Nobody replies and then Homer remembers that Bart and Lisa are at school so he decides to go to the Kwik E Mart by himself");
	        kwik();
	    } else if (userInput == 2){
	        System.out.println("He doesn't find them and remembers that Bart and Lisa are at school so he decides to go to the Kwik E Mart by himself");
	       kwik();
	    } else if (userInput == 3){
	        System.out.println("The dog comes back alone and at that moment, Homer realizes, that Bart and Lisa are at school so he decides to go to the Kwik E Mart by himself");
	        kwik();
	    } else {
	        System.out.println("GAME OVER. PRESS ENTER TO RESTART");
	        keyboard.nextLine();
	        startNode();
	    }
	    }
	    public static void call(){
	       Scanner keyboard = new Scanner(System.in);
	       System.out.println("Homer calls the Kwik E Mart using:");
	       System.out.println("1) His phone");
	       System.out.println("2) Marge's phone");
	       System.out.println("3) The phone in the kitchen");
	       
	       int userInput = keyboard.nextInt();
	        if(userInput == 1){
	            System.out.println("Nobody picks up the phone. Homer then decides to just go to the Kwik E Mart himself");
	            kwik();
	        } else if (userInput == 2){
	            System.out.println("Nobody picks up the phone. Homer then decides to just go to the Kwik E Mart himself");
	            kwik();
	        } else if (userInput == 3){
	            System.out.println("Nobody picks up the phone. Homer then decides to just go to the Kwik E Mart himself");
	            kwik();
	        } else {
	        System.out.println("GAME OVER. PRESS ENTER TO RESTART");
	        keyboard.nextLine();
	        startNode();
	        }
	    }
	        public static void Car(){
	            Scanner keyboard = new Scanner(System.in);
	        System.out.println("Homer arrives at the Kwik E Mart and sees Apu. He then buys a donut. How many does he buy?");
	        System.out.println("1 )2000 donuts for $4000");
	        System.out.println("2) 5000 donuts for $8000");
	        System.out.println("3) 10000 donuts for $10000 ");
	        
	        
	        int userInput = keyboard.nextInt();
	        if(userInput == 1){
	            System.out.println("Homer pays Apu and goes back home");
	            home();
	        } else if (userInput == 2){
	            System.out.println("Homer pays Apu and goes back home");
	            home();
	        } else if (userInput == 3){
	            System.out.println("Homer pays Apu and goes back home");
	            home();
	        } else {
	        System.out.println("GAME OVER. PRESS ENTER TO RESTART");
	        keyboard.nextLine();
	        startNode();
	        }
	        }
	        public static void home(){
	            Scanner keyboard = new Scanner(System.in);
	        System.out.println("On the way home homer realizes that he spent a crap load of money on donuts. Does he go back and return the donuts?");
	        System.out.println("1) Yes");
	        System.out.println("2) No");
	        
	        int userInput = keyboard.nextInt();
	        if(userInput == 1){
	            System.out.println("He goes back and returns the donuts. On the way home he realizes that the donuts were a waste of money and he should have not bought them in the first place");
	            homev2();
	        } else if (userInput == 2){
	            System.out.println("He continues on his way home");
	            homev();
	        
	        } else {
	        System.out.println("GAME OVER. PRESS ENTER TO RESTART");
	        keyboard.nextLine();
	        startNode();
	        }
	        }
	        public static void homev(){
	            Scanner keyboard = new Scanner(System.in);
	            System.out.println("When Homer gets home he sees a ton of bills and realizes he is broke now because he spent all of his money on donuts. Does he go back to return the donuts?.");
	            System.out.println("1) Yes");
	            System.out.println("2) No");
	            
	            int userInput = keyboard.nextInt();
	        if(userInput == 1){
	            System.out.println("He goes back and returns the donuts. On the way home he realizes that the donuts were a waste of money and he should have not bought them in the first place");
	            homev2();
	        } else if (userInput == 2){
	            System.out.println("Homer dies a sad death unemployed and homeless because he spent all of his money on donuts. Sucks...");
	            homev3();
	        
	        } else {
	        System.out.println("GAME OVER. PRESS ENTER TO RESTART");
	        keyboard.nextLine();
	        startNode();
	        }
	        }
	            
	            public static void homev2(){
	            Scanner keyboard = new Scanner(System.in);
	            System.out.println("Homer makes an oath to never buy donuts ever again. Do you think this oath will be held?");
	            System.out.println("1) Yes");
	            System.out.println("2) No");
	            
	            int userInput = keyboard.nextInt();
	        if(userInput == 1){
	            System.out.println("Haha no it wont");
	            homev3();
	        } else if (userInput == 2){
	            System.out.println("You are probably right");
	            homev3();
	        
	        } else {
	        System.out.println("GAME OVER. PRESS ENTER TO RESTART");
	        keyboard.nextLine();
	       startNode();
	        }
	            }
	            
	             public static void homev3(){
	            Scanner keyboard = new Scanner(System.in);
	            System.out.println("THE END. PRESS ENTER TO RESTART.");
	            keyboard.nextLine();
	    startNode();
	             }
}
