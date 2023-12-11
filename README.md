# java-not-ort-uyg-
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        //değişkenleri oluştur.
        int mat, fizik,kimya,turkce,tarih,muzik;

        //scanner clası oluştur.
        Scanner inp = new Scanner(System.in);

        // kullanıcıdan değerleri al
        System.out.println("Matematik notunuz: ");
        mat = inp.nextInt();
        System.out.println(mat);

        System.out.println("Fizik notunuz: ");
        fizik= inp.nextInt();

        System.out.println("Kimya notunuz: ");
        kimya = inp.nextInt();

        System.out.println("Turkce notunuz: ");
        turkce = inp.nextInt();

        System.out.println("tarih notunuz : ");
        tarih= inp.nextInt();

        System.out.println("muzik notunuz : ");
        muzik= inp.nextInt();

        int toplam = (mat+fizik+kimya+turkce+tarih+muzik);
        double ortalama = toplam/6;
        System.out.println("Ortalamanız :" + ortalama);
        String conclusion = ortalama >= 60 ? "Tebrikler geçtiniz."  : " kaldınız." ;
        System.out.println(conclusion);

    }
}
