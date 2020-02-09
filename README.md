import java.util.*;
public class tugas1 {
  public static void main(String[] args) {
    int harga;
    String jenis, pilih, merek;
    Scanner masuk = new Scanner(System.in);
    System.out.print("pilih kendaraan (mobil/motor) = ");
    pilih = masuk.next();
    if (pilih.equalsIgnoreCase("mobil")) {
      System.out.print("pilih merek (Honda/Suzuki) = ");
      jenis = masuk.next();
      if (jenis.equalsIgnoreCase("Honda")) {
        System.out.print("pilih merek (Jazz, Brio, Mobilio) = ");
        merek = masuk.next();
        switch (merek) {
          case "Jazz":
          System.out.println("harga Rp. 170.000.000");
          break;
          case "Brio":
          System.out.println("harga Rp. 120.000.000");
          break;
          case "Mobilio":
          System.out.println("harga Rp. 170.000.000");
          break;
        }
      }
      else if (jenis.equalsIgnoreCase("Suzuki")) {
        System.out.print("pilih merek (APV, Swift, Ertiga) = ");
        merek = masuk.next();
        switch (merek) {
          case "APV":
          System.out.println("harga Rp. 180.000.000");
          break;
          case "Swift":
          System.out.println("harga Rp. 155.000.000");
          break;
          case "Ertiga":
          System.out.println("harga Rp. 160.000.000");
          break;
        }
      }
    }
    else if (pilih.equalsIgnoreCase("motor")) {
      System.out.print("pilih merek (Honda/Yamaha) = ");
      jenis = masuk.next();
      if (jenis.equalsIgnoreCase("Honda")) {
        System.out.print("pilih merek (Vario, Supra) = ");
        merek = masuk.next();
        switch (merek) {
          case "Vario":
          System.out.println("harga Rp. 15.000.000");
          break;
          case "Supra":
          System.out.println("harga Rp. 12.000.000");
          break;
        }
      }
      else if (jenis.equalsIgnoreCase("Yamaha")) {
        System.out.print("pilih merek (Mio, Vizxion) = ");
        merek = masuk.next();
        switch (merek) {
          case "Mio":
          System.out.println("harga Rp. 14.000.000");
          break;
          case "Swift":
          System.out.println("harga Rp. 20.000.000");
          break;
        }
      }
    }
  }
}
