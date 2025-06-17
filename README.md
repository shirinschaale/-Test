public class main {
    public static int quadratzahl(int n) {
      return (n + 1) * (n + 1); 
    }
    
    public static void main(String[] args) {
      int zahl = 8;
      int ergebnis = quadratzahl(zahl);
      System.out.println(ergebnis);
    }
}
