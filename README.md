# patika.dev 

taksiMetre
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        double km, perKm = 2.20, total= 10;

        Scanner inp = new Scanner(System.in);
        System.out.print("km giriniz: ");
        km  = inp.nextInt();

        total += (km*perKm);
        total = (total < 20)  ? 20 : total;

        System.out.println("tutar : " + total);
    }
}
