# Reverse-Word

package programs;

import java.util.Scanner;

public class Reverseword {

	public static void main(String[] args) {
		
		String S = "World Is Beautiful";
		System.out.println(""+S);
		
		String reverse = "";
		
		for(int i=S.length()-1; i>=0; i--)
			
		{
			reverse +=  new Character(S.charAt(i));
			
			
		}
		
		System.out.println("" +reverse);
		
		String[] SS = reverse.split(" ");
		
		System.out.println(""+SS[2]);
		System.out.println(""+SS[1]);
		
		System.out.println(""+SS[0]);
	}

}
