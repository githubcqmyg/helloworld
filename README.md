# helloworld
my first repository
import java.util.Scanner;
public class math1 {
static int x;
static int y;
	public static void main(String args[]){
	@SuppressWarnings("resource")
	Scanner in =new Scanner(System.in);
	    System.out.print("输入列数：");
		x=in.nextInt();
		System.out.print("输入行数：");	
		y=in.nextInt();
		int num=0;
		for(int i=0;i<x;i++)
		{
			System.out.print(" "+i);
			if(i==x-1)
				System.out.print("\n");
		}
		for(int m=1;m<y;m++){
			System.out.print(" "+m);
			for(int n=1;n<x;n++){
				num=m*n;
			System.out.print(" "+num);
			if(n==x-1)
				System.out.print("\n");
			}
		}
	
	}

}

