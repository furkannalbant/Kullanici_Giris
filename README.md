# Kullanici_Giris


## Code
```Java

int i=0;
    while ()
    String un,ps,ss="0",dataun="Furkan",dataps="123";
    Scanner inp = new Scanner(System.in);
    System.out.println("Hoş geldiniz \n Kullanıcı Adınızı Giriniz :");
    un=inp.nextLine();
    System.out.println("Şifrenizi Giriniz");
    ps=inp.nextLine();
    if ((dataun.equals(un))&&(dataps.equals(ps))){
      System.out.println(" Giriş Başarılı");
    }
    else
    {
      System.out.println("Şifreniz Yanlış \n şifrenizi sıfırlamak için \" 1 \"e basınız tekrar denemek için  \"2\" ye basınız ");
          ss=inp.nextLine();
      if (ss.equals("1")){
        System.out.println("Yeni şifrenizi Giriniz");
        ps= inp.nextLine();
        while (i==0)
        if (ps.equals(dataps))
        {
          System.out.println("Giridiğiniz şifre bir önceki ile ayni Yeni şifrenizi Giriniz");
          ps= inp.nextLine();
          i=0;
        }
        else{
          dataps=ps;
          System.out.println("Şifreniz Başarlı bir şekilde değiştirildi");
          i++;
        }
      }

```
## Printer


* Kullanıcı Adınızı Giriniz :
* 1
* Şifrenizi Giriniz
* 2
* Şifreniz Yanlış 
* şifrenizi sıfırlamak için " 1 "e basınız tekrar denemek için  "2" ye basınız 
* 1
* Yeni şifrenizi Giriniz
* 123
* Giridiğiniz şifre bir önceki ile ayni Yeni şifrenizi Giriniz
* 23
* Şifreniz Başarlı bir şekilde değiştirildi
