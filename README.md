# taraliAlan

import java.util.Scanner;

public class alan {
    public static void main(String[] args) {
        int r;
        double pi = 3.14;
        double a;
        Scanner inp = new Scanner(System.in);
        System.out.println("Dairenin yarı çapını giriniz: ");
        r = inp.nextInt();
        System.out.println("Açıyı giriniz: ");
        a = inp.nextInt();
        double alan = pi * r *r ;
        double cevre = 2 * pi *r ;
        double taraliAlan = (pi*(r*r)*a)/360;
        System.out.println("Dairenin Alanı: " + alan);
        System.out.println("Dairenin Çevresi: " + cevre);
        System.out.println("Taralı Bölgenin Alanı: " + taraliAlan);
    }

