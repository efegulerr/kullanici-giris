# kullanici-giris
patika.dev kullanıcı girişi

import java.util.Scanner;
public class main {
    public static void main(String[]args) {
        String userName, password;
        Scanner inp = new Scanner(System.in);
        System.out.print("Kullanıcı adınızı giriniz (Büyük küçük harf duyarlıdır.):");
            userName = inp.nextLine();
        Scanner abc = new Scanner(System.in);
        System.out.print("Şifrenizi giriniz (Büyük küçük harf duyarlıdır.);");
            password = abc.nextLine();
        if (userName.equals("patika") && password.equals("java101")) {
            System.out.print("Giriş başarılı");
        }else {
            System.out.print("Hatalı giriş yaptınız");
        }
        }
    }
