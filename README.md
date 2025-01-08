import java.util.*;
public class Main{
    public static void main(String[]args){
        //Scanner sc=new Scanner(System.in);
        //int c=sum();
        System.out.print(sum());
    }
    public static int sum(){
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        int c=0;
        while(a>0){
            int d=a%10;
            c=c+1;
            a=a/10;
            //return sum;
            
        }
         return c;
    }
}
