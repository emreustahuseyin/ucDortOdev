   
   
             import java.util.Scanner;

     public class üçDörtÖdev {
      public static void main(String[] args) {

        int k;
        int toplam = 0;
        int bölünebilenSayısı = 0;

        Scanner inp = new Scanner(System.in);

        System.out.println("Sayı Giriniz");
        k = inp.nextInt();

        for (int i = 0; i <= k; i++) {
            if (i % 3 == 0 && i % 4 == 0) {
                System.out.println(i);
                toplam += i;
                bölünebilenSayısı++;
            }
        }

        double ortalama = (double) toplam / bölünebilenSayısı;
        System.out.println("Ortalama: " + ortalama);
        }
      }
