# conditional-statement-
# WriteaJavaprogramtogetanumberfromtheuserandprintwhetheritispositive or negative.
import java.util.*;

public class Main {
    public static void main(String[] args) {
        Scanner sc= new Scanner(System.in);
        System.out.println("enter a number:");
        int n= sc.nextInt();
        if (n>=0){
            System.out.print("positive");
        }else{
            System.out.print("negative");
        }
        System.out.println();
    }
}
