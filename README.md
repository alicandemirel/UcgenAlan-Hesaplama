//UcgenAlanıHesaplama

import java.util.Scanner;

public class DikUcgendeHipotenus {
    public static void main(String[] args) {

        int a, b, c;


        Scanner girdi = new Scanner(System.in);

        System.out.print("Lütfen a kenarı uzunluğunu giriniz: ");
        a = girdi.nextInt();
        System.out.print("Lütfen b kenarı uzunluğunu giriniz: ");
        b = girdi.nextInt();
        System.out.print("Lütfen c kenarı uzunluğunu giriniz: ");
        c = girdi.nextInt();

        double u = (a+b+c)/2;


        System.out.print("Üçgenin alanı: " + Math.sqrt(u * (u - a) * (u - b) * (u - c)) );
    }

}
