# codes

public class Main
{
	public static void main(String[] args) {
	   // Scanner in=new Scanner(System.in);
	    String str="a1b2c3";
	    convertchr(str);
	}
	public static void convertchr(String s){
	   for(int i=0;i<s.length();i++){
	   if(Character.isAlphabetic(s.charAt(i))){
	      // System.out.print(s.charAt(i));
	   }else{
	       int a=Character.getNumericValue(s.charAt(i));
	       for(int j=0;j<a;j++){
	           System.out.print(s.charAt(i-1));
	       }
	   }
	   } 
	}
}
