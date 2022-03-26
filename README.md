# Tek-Sayilarin-Toplami
Patika.dev > Java101 > Döngüler > Pratik2 - Tek Sayıların Toplamını Bulan Program

Java döngüler ile negatif bir değer girilene kadar kullanıcıdan girişleri kabul eden ve girilen değerlerden tek sayıları toplayıp ekrana basan programı yazıyoruz.

### Ödev

Java döngüler ile tek bir sayı girilene kadar kullanıcıdan girişleri kabul eden ve girilen değerlerden çift ve 4'ün katları olan sayıları toplayıp ekrana basan programı yazıyoruz.

      import java.util.*;

      public class tek_sayilarin_toplami {

        public static void main(String[] args) {
          Scanner sc = new Scanner(System.in);

          int n;
          int sum = 0;
          do {
            System.out.print("Please enter a number: ");
            n = sc.nextInt();

            if(n % 4 == 0)
              sum += n;
          } while(n % 2 == 0);

          System.out.println("Sum: " + sum);
          }
      }
