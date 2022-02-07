import java.util.Scanner;
public class Main
{
public static void main(String[] args) {
	    Scanner in = new Scanner(System.in);
	    System.out.println("");
	    short num1 = in.nextShort();
	    System.out.println("");
	    short num2 = in.nextShort();
	    in.close();
	
	    System.out.println(num1+num2);
}
}
