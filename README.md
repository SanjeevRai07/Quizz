# Quizz
import java.util.Scanner;
public class mcq{
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        
        System.out.println("WElcome to Quiz Competition in Arka JAin University!!");
        
        System.out.print("Enter your Name:");
        String name = sc.nextLine();
        System.out.println("Welcome " + name);
      
        
        System.out.println("Enter your Enrollment Number");
        int Enrollment = sc.nextInt();


        int count = 0;
        //Question No 1
        System.out.println("Question 1 - What is the capital of india");
        System.out.println("1.Lolkata\n2.new DElhi\n3.mumbai\n4.jamshedpur");
        System.out.println("Enter your answer");
        int ans1 = sc.nextInt();
        if(ans1 == 2){
            System.out.println("Correct Answer");
            count++;


        }else{
            System.out.println("Incorrect Answer");
        }

      //Question No 2
      System.out.println("Question 2 - Who is the founder of java");
        System.out.println("1.Sanjeev\n2.JAmes goshling\n3.Nargis Gunda\n4.Sumit");
        System.out.println("Enter your answer");
        int ans2 = sc.nextInt();
        if(ans2 == 2){
            System.out.println("Correct Answer");
            count++;


        }else{
            System.out.println("Incorrect Answer");
        }
      //question number 3
      System.out.println("Question 3 - who is the prime minister of india");
        System.out.println("1.Lolkata\n2.new DElhi\n3.mumbai\n4.Narendra modi");
        System.out.println("Enter your answer");
        int ans3 = sc.nextInt();
        if(ans3 == 4){
            System.out.println("Correct Answer");
            count++;


        }else{
            System.out.println("Incorrect Answer");
        }
    //question number 4
    System.out.println("Question 4 - Who is the founder of android");
        System.out.println("1.Sanjeev rai\n2.new DElhi\n3.mumbai\n4.jamshedpur");
        System.out.println("Enter your answer");
        int ans4 = sc.nextInt();
        if(ans4 == 1){
            System.out.println("Correct Answer");
            count++;


        }else{
            System.out.println("Incorrect Answer");
        }
    //question number 5
    System.out.println("Question 5 - who is the founder of python");
        System.out.println("1.Lolkata\n2.new DElhi\n3.Sumit\n4.jamshedpur");
        System.out.println("Enter your answer");
        int ans5 = sc.nextInt();
        if(ans5 == 3){
            System.out.println("Correct Answer");
            count++;


        }else{
            System.out.println("Incorrect Answer");
        }

        System.out.println("Your total score is " + count);

    }
}


# Run the codee
