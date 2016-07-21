# ReverseNumber
import java.util.Scanner;

public class ReverseADigit {

	public static void main(String[] args) {
		Scanner get=new Scanner(System.in);
		System.out.println("Enter number");
		int in=get.nextInt();
		int nn=in;
		int sub=0;
		while(nn!=0)
		{
			sub=sub*10;
			sub=sub+nn%10;
			nn=nn/10;
		}
		System.out.println("output number is");
		System.out.println(sub);

	}

}
