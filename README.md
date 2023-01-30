# Not-Ortalamas-Hesaplama


public class Main {
    public static void main(String[] args) {

         int mat,fizik,kimya,muzik,tarih,turkce;

         Scanner amp = new Scanner(System.in);

         System.out.print("Matematik Notunuz : ");
         mat = amp.nextInt();

         System.out.print("Türkçe Notunuz : ");
         turkce = amp.nextInt();

         System.out.print("Müzik Notunuz :" );
         muzik = amp.nextInt();

         System.out.print("Tarih Notunuz : " );
         tarih = amp.nextInt();

         System.out.print("Kimya Notunuz :" );
         kimya = amp.nextInt();

         System.out.print("Fizik Notunuz :");
         fizik = amp.nextInt();

         int toplam = (mat+fizik+muzik+tarih+kimya+turkce);
         double sonuc = toplam / 6;
         System.out.println("Not Ortalamanız :"+sonuc);

        String  str = sonuc>=60 ? "Geçti" : "Kaldı";
        System.out.println("Sınıfı Geçme Durumu : " + str);
         }

    }
