# Dik-gende-Hipoten-s-Bulan-Program
Kodluyoruz Eğitimi kapsamında açtığım bir proje
import java.util.Scanner;

public class HipotenusHesaplayici {
    
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Kullanıcıdan dik kenarların uzunluklarını al
        System.out.print("Birinci dik kenarın uzunluğunu giriniz: ");
        double dikKenar1 = scanner.nextDouble();

        System.out.print("İkinci dik kenarın uzunluğunu giriniz: ");
        double dikKenar2 = scanner.nextDouble();

        // Hipotenüsü hesapla
        double hipotenus = Math.sqrt((dikKenar1 * dikKenar1) + (dikKenar2 * dikKenar2));

        // Sonucu ekrana yazdır
        System.out.println("Hipotenüs uzunluğu: " + hipotenus);
    }
}
