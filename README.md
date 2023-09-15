package ss;


	 import java.util.*;
	 
	 public class StrQ2 {

	 	
	 	public static void StringOperations(String str)
	 	{
	 		String newstr="";
	 		
	 		for(int i=0;i<str.length();i++)
	 		{
	 			
	 			
	 			
	 			if(str.charAt(i)== 'a'||str.charAt(i)== 'e'|| str.charAt(i)== 'i'|| str.charAt(i)== 'o'|| str.charAt(i)== 'u')
	 			{
	 			 
	 				char ch=  (char)((int)(str.charAt(i))+1);
	 				newstr+=ch; 
	 				continue;
	 			}
	 			char ch1=str.charAt(i);
	 			newstr+=ch1; 
	 			
	 		}
	 		System.out.println(newstr);
	 	}
	 		
	 	public static void main(String args[])
	 	{   String str;
	 		Scanner sc = new Scanner(System.in);
	 		System.out.println("enter a string ");
	 		 str= sc.nextLine();
	 		StringOperations(str);
	 	}
	 }
