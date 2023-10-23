# Odev-3
Odev  3
                                                                    SORU 1

                                                                    
Yazılımda karşılaşılan hatalardan en büyük kısım fonksiyonel hatalar, söz dizisi (sözdizimi) hataları, çalışma zamanı (çalışma zamanı) hataları ve mantıksal hatalardır. 
Ama yine de tamamını listeleyecek olursak aşağıdaki gibi sıralanabilir.
 
1) İşlevsellik Hataları:
İşlevsellik, yazılımın nasıl davranması gerektiğidir. Yazılımın yapmasını beklediğiniz bir şey zor, garip, kafa karıştırıcı veya imkansızsa, yazılımda bir
 işlevsellik hatası vardır. İptal butonu için Beklenen İşlevsellik, “Yeni Proje Oluştur” penceresinin kapanması ve hiçbir değişikliğin kaydedilmemesidir
(yani yeni proje oluşturulmamalıdır). İptal düğmesi tıklanamıyorsa bu bir işlevsellik hatasıdır.

3) İletişim Hataları:
Bu hatalar yazılımdan son kullanıcıya iletişim kurulurken ortaya çıkar. Yazılımı kullanmak için son kullanıcının bilmesi gereken her şey ekranda sunulmalıdır.

İletişim hatalarına birkaç örnek: Yardım talimatlarının/menüsünün sağlanmaması, sürümün parçası olan ancak yardım menüsünde belgelenmeyen özellikler, "Kaydet" adlı 
düğmenin bir dosyayı silmemesi vb.

 
3)Eksik komut hataları:
Bu, beklenen bir komut eksik olduğunda meydana gelir. Bu pencere, kullanıcının yeni bir proje oluşturmasına olanak tanır. Ancak kullanıcının projeyi oluşturmadan bu pencereden
çıkma seçeneği bulunmamaktadır. Kullanıcıya “İptal” seçeneği/düğmesi sunulmadığı için bu bir eksik komut hatasıdır.

4)Sözdizimsel Hata:
Sözdizimsel hatalar, yanlış yazılmış kelimeler veya dilbilgisi açısından yanlış cümlelerdir ve yazılım GUI'sini test ederken çok belirgindir. Lütfen koddaki sözdizimi hatalarından
bahsetmediğimizi unutmayın. Derleyici, geliştiriciyi kodda meydana gelen sözdizimi hataları konusunda uyaracaktır.

5) Hata işleme hataları:
Kullanıcının yazılımla etkileşimi sırasında ortaya çıkan hataların açık ve anlamlı bir şekilde ele alınması gerekir. Değilse, buna Hata İşleme Hatası denir. Yazılımın, bilgileri bir
forma kaydetmeden önce doldurulması gereken belirli zorunlu alanları varsa, doğrulama mesajları açık olmalı ve kullanıcı tarafından yapılması gereken eylemi belirtmelidir.
7) Hesaplama Hataları:
Bu hata aşağıdaki nedenlerden herhangi biri nedeniyle oluşur:

Kötü mantık
Yanlış formüller
Veri türü uyumsuzluğu
Kodlama hataları
İşlev çağrısı sorunları vb.
1999'da NASA, Mars iklim yörünge aracını kaybetti çünkü NASA'nın çalıştırdığı taşeronlardan biri, amaçlanan metrik sistem yerine İngiliz birimlerini kullanmıştı ve bu da yörünge aracının
iticilerinin yanlış çalışmasına neden olmuştu. Bu hata nedeniyle yörünge aracı Mars'a varır varmaz düştü.

7) Kontrol akışı hataları:
Bir yazılımın kontrol akışı, bundan sonra ne yapacağını ve hangi durumda olacağını açıklar.
Örneğin, kullanıcının bir formu doldurması gereken ve kullanıcıya sunulan seçeneklerin şunlar olduğu bir sistemi düşünün: Kaydet, Kaydet, Kapat ve İptal. Kullanıcının “Kaydet ve Kapat”
 butonuna basması durumunda formdaki kullanıcı bilgileri kaydedilmeli ve form kapatılmalıdır. Düğmeye tıklamak formu kapatmıyorsa bu bir kontrol akışı hatasıdır.

Daha az hata ile kod yazmak:
En son kodunuzu derleyiciye ilk kez gönderdiğinizde çok sayıda sözdizimi hatası alıyorsanız, bir şeyi doğru yapıyor olabilirsiniz.

Derleyiciler sözdizimi hatalarını bulur. İyi derleyiciler aynı zamanda nedeni hızlı bir şekilde bulmak için yeterli ayrıntıyı sağlayan yüksek kaliteli mesajlar da verirler.

Kodunuzu derleyiciye göndermeden önce sözdizimi hatalarını aramak için harcadığınız süre, verimsiz kullandığınız zamandır. Bir bilgisayarın hızlı bir şekilde yapabildiğini yavaş yavaş yapıyorsunuz.

Kaliteli bir yazım sistemine sahip bir dil kullanacak kadar şanslıysanız, aynı durum yazım hataları için de geçerlidir.

Elbette derlemeden önce kodunuzu kontrol etmelisiniz. Ancak sözdizimi doğruluğunu veya yazım doğruluğunu kontrol etmeyin, derleyicinin neyi yapamayacağını kontrol edin: amacınız.

Bir derleyiciyi sizin değerli bir programcı olup olmadığına karar veren bir bekçi olarak düşünmeyin. Bunu sizin için bazı vasıfsız işleri yapan bir robot asistanı olarak düşünün.


                                                                    SORU 2
import java.awt.Image;
import java.awt.Toolkit;
import java.net.URL;
public class Zar {
    public static void main(String[] args) throws Exception {
        URL url1 = new URL("");
        Image image1 = Toolkit.getDefaultToolkit().createImage(url1);
        URL url2 = new URL("");
        Image image2 = Toolkit.getDefaultToolkit().createImage(url2);
        URL url3 = new URL("");
        Image image3 = Toolkit.getDefaultToolkit().createImage(url3);
        URL url4 = new URL("");
        Image image4 = Toolkit.getDefaultToolkit().createImage(url4);
        URL url5 = new URL("");
        Image image5 = Toolkit.getDefaultToolkit().createImage(url5);
        URL url6 = new URL("");
        Image image6 = Toolkit.getDefaultToolkit().createImage(url5);
        {
            // math random; () = 0-1 arası rastgele sayı üretir
            int zar1 = (int) (Math.random() * 6) + 1;
            if (zar1 == 1) System.out.println(image1);
            if (zar1 == 2) System.out.println(image2);
            if (zar1 == 3) System.out.println(image3);
            if (zar1 == 4) System.out.println(image4);
            if (zar1 == 5) System.out.println(image5);
            if (zar1 == 6) System.out.println("e");
            int zar2 = (int) (Math.random() * 6) + 1;
            System.out.print(zar2);

        }

    }
}                                                                    
açıklama: hocam bu soruda fotoğraf kısmını yapamadık arkadaşımla da yardımlaştık web den de çok yardım almak istemedim.

                                                                    SORU 3
javax.swing.JOptionPane;

public class Main {
    public static void main(String[] args) {
        int rastgeleSayi = (int) (Math.random() * 100 + 1);                  // math random 0 ile 1 arasında sayı üretirken 100 ile çarparak 0 ile 100 arası sayı üretimini deniyoruz.
        int tahminSayisi = 0;
        boolean dogruTahmin = false;

        JOptionPane.showMessageDialog(null, "1-100 arasında bir sayı tuttum. Bakalım bulabilecek misin ?");            //bizden kullanılması istenilen yapı

        do {
            String tahmin = JOptionPane.showInputDialog(null, "Tahminin nedir?");
            tahminSayisi++;

            try {
                int tahminInt = Integer.parseInt(tahmin);

                if (tahminInt < 1 || tahminInt > 100) {
                    JOptionPane.showMessageDialog(null, "Lütfen 1-100 arasında bir sayı girin.");
                } else if (tahminInt < rastgeleSayi) {
                    JOptionPane.showMessageDialog(null, "Daha yüksek bir sayı girin.");
                } else if (tahminInt > rastgeleSayi) {
                    JOptionPane.showMessageDialog(null, "Daha düşük bir sayı girin.");
                } else {
                    dogruTahmin = true;
                    JOptionPane.showMessageDialog(null, "Tebrikler! " + tahminSayisi + " tahminde doğru sayıyı buldunuz.");
                }
            } catch (NumberFormatException e) {
                JOptionPane.showMessageDialog(null, "Lütfen geçerli bir sayı girin.");
            }
        } while (!dogruTahmin);

        JOptionPane.showMessageDialog(null, "Oyun bitti. ");
    }
}                                                                    
                                                                   SORU 4


public class Odev {
    public static void main(String[] args)
    {
        run();
    }

    public static void run()
    {
        int x1 = 0;
        int x2 = 0;
        int x3 = 0;
        int i = 100;

        while (i <= 999)
        {
            while (i <= 999)
            {
                int val = i;
                x1 = val % 10;
                val = val / 10;
                x2 = val % 10;
                val = val / 10;
                x3 = val;
                break;
            }

            boolean[] control = new boolean[7];

            control[0] = kosul1(x3,x2,x1,i); 
            control[1] = kosul2(i);
            control[2] = kosul3(x3,x2,x1);
            control[3] = kosul4(x3,x2);
            control[4] = kosul5(x2,x1);
            control[5] = kosul6(x2,x1);
            control[6] = kosul7(x3,x2);

            if (control[0] && control[1] && control[2] && control[3] && control[4] && control[5] && control[6])
                System.out.println(i);

            i++;
        }
    }

    public static boolean kosul1 (int a, int b, int c, int i)
    {
        int val = c * 100 + b * 10 + a;

        if (val > i)
            return true;
        else
            return false;
    }

    public static boolean isPrime (int val)
    {
        for (int i = 2; i * i <= val; i++)
            if (val % i == 0)
                return false;

        return true;
    }

    public static boolean kosul2 (int i)
    {
        return isPrime(i);
    }

    public static boolean kosul3 (int a, int b, int c)
    {
        int val = c * 100 + b * 10 + a;

        return isPrime(val);
    }

    public static boolean kosul4 (int a, int b)
    {
        int val = a * 10 + b;

        return isPrime(val);
    }

    public static boolean kosul5 (int b, int c)
    {
        int val = b * 10 + c;

        return isPrime(val);
    }

    public static boolean kosul6 (int b, int c)
    {
        int val = c * 10 + b;

        return isPrime(val);
    }

    public static boolean kosul7 (int a, int b)
    {
        int val = b * 10 + a;

        return isPrime(val);
    }
}


   açıklama: hocam bu soruda da zorlandım baya internetten yardım aldım biraz kodu inceleyip algoritmasını anlamaya çalıştım


                                                                   SORU 5

public class Odev {

    public static void main(String[] args)
    {
        java.util.Scanner kb = new java.util.Scanner(System.in);
        System.out.println("Bir sayi giriniz");
        System.out.print(isPrimeX(Integer.parseInt(kb.nextLine())));
    }

    public static boolean isPrime(int val)
    {
        if (val <= 1)
            return false;

        if (val % 2 == 0)
            return val == 2;

        if (val % 3 == 0)
            return val == 3;

        if (val % 5 == 0)
            return val == 5;

        if (val % 7 == 0)
            return val == 7;

        if (val % 11 == 0)
            return val == 11;

        for (int i = 13; i * i <= val; i += 2)
            if (val % i == 0)
                return false;

        return true;
    }

    public static boolean isPrimeX(int val)
    {
        int temp = 0;

        while(true)
            if (isPrime(val))
            {
                while (val != 0)
                {
                    temp += val % 10;
                    val /= 10;
                }

                val = temp;

                if (val == 2)
                    return true;

                if (val == 3)
                    return true;

                if (val == 5)
                    return true;

                if (val == 7)
                    return true;
            } else
                return false;
    }
}










                                            




 
