Vücut Kitle İndeksi Hesaplama

import java.util.Scanner;

public class Main {
public static void main(String[] args) {
double kg,boy,vki;

        Scanner input = new Scanner(System.in);
        System.out.println("Boyunuzu girinz:");
        boy = input.nextDouble();
        System.out.println("Kilonuzu giriniz:");
        kg = input.nextDouble();

input.close();
vki = kg / ((boy*boy));
System.out.println("Vücut Kitle İndeksi :" + vki);


    }
}