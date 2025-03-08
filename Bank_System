package Bank;

import java.util.Scanner;

class bankHDFC
{
	void deposite(Double amount)
	{
		double depo;
		Scanner s1 = new Scanner(System.in);
		System.out.println("Enter amount to deposite");
		depo = s1.nextDouble();
		amount = amount + depo;
		System.out.println("Amount after deposite = "+ amount);
		
	}
	void withdraw(Double amount)
	{
		double with=0;
		Scanner s1 = new Scanner(System.in);
		System.out.println("Enter amount to withdraw");
		with = s1.nextDouble();
		
		if(amount >= with)
		{			
			amount = amount - with;
			System.out.println("Amount after withdraw = "+ amount);
		}
		else
		{
			System.out.println("Less Balance in account");
		}
	}
	
}
class HDFC extends bank
{
	void wel()
	{
		System.out.println("Wellcome to HDFC Bank :");
	}
	void user1(Double amount)
	{
		super.deposite(amount);
	}
	
	void user2(Double amount)
	{
		super.withdraw(amount);
	}
}
public class Simple_Bank_Ex2 
{

	public static void main(String[] args) 
	{


		HDFC ob = new HDFC();
		ob.wel();
		double amount;
		Scanner s2 = new Scanner(System.in);
		System.out.println("Enter amount : ");
		amount =s2.nextDouble();
		System.out.println("1.deposite\n2.withdraw");
		int ch;
		System.out.println("Enter Choice : ");
		ch = s2.nextInt();
		
		
		
		switch(ch)
		{
		case 1:
			ob.deposite(amount);
			break;
			
		case 2:
			ob.withdraw(amount);
			break;
		
		default:
			System.out.println("Invalid Choice!!");
		}
		
		
		
	}

}
