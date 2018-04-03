# Coding-Game-Logika

package AI;
import java.util.Scanner;

public class Game_AI {
    
public static void main(String[] args) {
   
    int langkah1, langkah2, langkah3, langkah4, langkah5, langkah6, langkah7;
    Scanner panggil = new Scanner(System.in);
    System.out.println("============GAME LOGIKA=============");
    System.out.println("1.Kambing Menyebrang ");
    System.out.println("2.Serigala Menyebrang ");
    System.out.println("3.Sayuran Menyebrang ");
    System.out.println("4.Kambing Kembali ");
    System.out.println("5.Serigala Kembali ");
    System.out.println("6.Sayuran Kembali ");
    System.out.println("7.Perahu Kembali");
    System.out.println("=====================================");
    
    System.out.print("Langkah 1 :");
    langkah1 = panggil.nextInt();

    if (langkah1 == 1) {
        System.out.print("Langkah 2 :");
        langkah2 = panggil.nextInt();
        if (langkah2 == 7) {
            System.out.print("Langkah 3 :");
            langkah3 = panggil.nextInt();
            if (langkah3 == 2) {
                System.out.print("Langkah 4 :");
                langkah4 = panggil.nextInt();
                if (langkah4 == 4) {
                    System.out.print("Langkah 5 :");
                    langkah5 = panggil.nextInt();
                    if (langkah5 == 3) {
                        System.out.print("Langkah 6 :");
                        langkah6 = panggil.nextInt();
                        
                        if (langkah6 == 7) {
                            System.out.print("Langkah 7 :");
                            langkah7 = panggil.nextInt();
                            if (langkah7 == 1) {
                                System.out.println("Permainan Selesai:) ");
			System.out.println("1-7-2-4-3-7-1");
                            } else {
                                System.out.println("=============================");
                                System.out.println("Upss! Coba Lagi");
                            }
                        } else {
                            System.out.println("=================================");
                            System.out.println("Upss! Coba Lagi");
                        }
                    } else {
                        System.out.println("====================================");
                        System.out.println("Upss! Coba Lagi");
                    }
                } else {
                    System.out.println("=======================================");
                    System.out.println("Upss! Coba Lagi");
                }
            } else {
                System.out.println("===========================================");
                System.out.println("Upss! Coba Lagi");
            }
        } else {
            System.out.println("=================================================");
            System.out.println("Upss! Coba Lagi");
        }
    } else {
        System.out.println("=====================================================");
        System.out.println("Upss! Coba Lagi");
    }
}

}

