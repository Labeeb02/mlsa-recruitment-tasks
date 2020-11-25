//Code in java for task 1 of mlsa
import java.util.*;
class task1
{
  int x,y,z,n=0;
  Scanner sc=new Scanner(System.in);
  public void input()
  {
      System.out.println("Enter the value of x-");
      x=sc.nextInt();
      System.out.println("Enter the value of y-");
      y=sc.nextInt();
      System.out.println("Enter the value of z-");
      z=sc.nextInt();
  }
  public void task()
  {
       if((y%x)!=0)   //Checking if i am already at a station
       {
           n=x-(y%x);  // n is the distance between me and the next station
       }
       if(n>z)
       {
           System.out.println("Output-NO");
       }
       else
       {
           System.out.println("output-YES");
       }
   }
   public void main()
   {
        task1 obj=new task1();
        obj.input();
        obj.task();
   }
}
