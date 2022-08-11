# patika.dev-Java101-Vucut-Kitle-Indeksi-Hesaplayan-Program
Java ile kullanıcıdan boy ve kilo değerlerini alıp bir değişkene atayın. Aşağıdaki formüle göre kullanıcının "Vücut Kitle İndeks" değerini hesaplayıp ekrana yazdırın.
## Code
import java.util.Scanner;
import java.io.*;
import java.util.*;

public class Giris
{
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        double height_in_meter = s.nextDouble();
        double mass_in_kg = s.nextDouble();
        double bodyMassIndex = mass_in_kg/(height_in_meter*height_in_meter);
        System.out.println(bodyMassIndex);
    }
}
