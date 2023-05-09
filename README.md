# usulAlma
import java.util.Scanner;
public class usalma {
    public static void main (String[]arsg){

        Scanner input= new Scanner(System.in);

        int n ,r,total=1;
        System.out.println("Taban Sayıyı Giriniz: ");
        n=input.nextInt();

        System.out.println("Üs Sayısını Giriniz: ");
        r=input.nextInt();

        for (int i=1; i<=r;i++){
            total*=n; 
        }
        System.out.println("Cevap: "+total);

    }
}
