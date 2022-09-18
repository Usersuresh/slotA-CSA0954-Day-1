import java.util.*;
public class Main
{
	public static void main(String[] args) 
	{
	    double t,b,bou;
	    String g;
	    Scanner sc =new Scanner(System.in);
		System.out.print("Enter grade of employee: ");
		g=sc.nextLine();
		char c=g.charAt(0);
		System.out.print("Enter the employee salary: ");
		if(!sc.hasNextDouble())
		{
		    System.out.println("Invalid");
		    return;
		}
		double s=sc.nextDouble();
		if(s<0)
		{
		    System.out.println("Invalid Salary can not be negative");
		    return;
		}
		if(c=='A' || c=='B')
		{
		    System.out.println();
		}
		else
		{
		    System.out.println("Invalid Grade");
		    return;    
		}
		if(g.equals("A"))
		{
		    b=0.05*s;
		    if(s<10000)
    		{
    		    bou=b+(0.02*s);
    		    t=s+bou;
    		    System.out.println("Salary: "+s);
    		    System.out.println("Bonus: "+bou);
    		    System.out.println("Total be paid: "+t);
    		}
    		else
    		{
    		    t=s+b;
    		    System.out.println("Salary: "+s);
    		    System.out.println("Bonus: "+b);
    		    System.out.println("Total be paid: "+t);
    		}
		}
		else if(g.equals("B"))
		{
		    b=0.1*s;
		    if(s<10000)
    		{
    		    bou=b+(0.02*s);
    		    t=s+bou;
    		    System.out.println("Salary: "+s);
    		    System.out.println("Bonus: "+bou);
    		    System.out.println("Total be paid: "+t);
    		}
    		else
    		{
    		    t=s+b;
    		    System.out.println("Salary: "+s);
    		    System.out.println("Bonus: "+b);
    		    System.out.println("Total be paid: "+t);
    		}
		}
		else
		{
		    System.out.print("Invalid grade");
		}
	}
}
