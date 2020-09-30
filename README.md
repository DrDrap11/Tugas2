# Tugas2
Tugas Pengenalan Variable, Tipe data, Operator

Coding pembuatan program Ganjil dan Genap

package mengenaljava;
import java.util.Scanner;

public class GanjilGenap {
public static void main(String[] args){
    Scanner Input = new Scanner (System.in);
    int x ;
    System.out.println("----------Program Bilangan Ganjil dan Genap----------");
    System.out.println("Masukkan Angka : ");
    x = Input.nextInt();
    
    if (x %2==0) {
        System.out.println(" Bilangan Genap");
    
    }
    else {
        System.out.println("Bilangan Ganjil");
    }
            
    }
}


Coding Pembuatan Program Mengitung Luas Segitiga

package mengenaljava;
import java.io.BufferedReader;
import java.io.InputStreamReader;
import java.io.IOException;

public class LuasSegitiga {
public static BufferedReader Stdin = new BufferedReader (new InputStreamReader(System.in));
public static void main(String[] args) throws IOException{
    System.out.println("---------Luas Segitiga---------");
    System.out.println("Masukkan Alas : ");
    String Input = Stdin.readLine();
    int a = Integer.parseInt(Input);
    System.out.println("Masukkan Tinggi : ");
    Input = Stdin.readLine();
    int t = Integer.parseInt(Input);
    System.out.println("Luas "+"= "+(a*t*0.5));
    }
}
