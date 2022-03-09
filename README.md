Program that exponentially calculates the entered value

For döngüsü kullanılmalı.

import java.util.Scanner;

public class Odev21 {
    public static void main(String[] args) {

        int k,n,total =1;
        Scanner input = new Scanner(System.in);

        System.out.println("Enter the number to be exponentiated : "); // Üssü alınacak sayıyı giriniz.
        k = input.nextInt();

        System.out.println("Enter the power of the number : "); //Üssü giriniz.
        n = input.nextInt();

        for(int i=1 ; i<=n ; i++){  // Üssü kadar döndür
            total *= k;             // Sayının üssünü al.
        }

        System.out.println("Result : " + total); // Sonucu bastır


    }
}
