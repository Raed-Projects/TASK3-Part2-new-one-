package raed;
import java.util.Scanner;

public class JavaPracts {

	    public static void main(String[] args) {
	        Scanner scanner = new Scanner(System.in);

	        System.out.print(" أدخل اسم: ");
	        String noun = scanner.nextLine();
	        
	        System.out.print("أدخل فعل: ");
	        String verb = scanner.nextLine();
	        
	        System.out.print("أدخل صفة: ");
	        String adjective = scanner.nextLine();
	        
	        System.out.print("أدخل ظرفف: ");
	        String adverb = scanner.nextLine();

	        String output = "هل تمشي حيوانك ؟؟؟  " + adjective + " " + noun + " " + adverb + "هذا مضحك جدا";
	        
	        System.out.println(output);
	        
	        scanner.close();
	    }
	}
