# Not Hesaplama
Java 101 Dersinde hazırladığım Not Hesaplama Kodu



    {public static void main(String[] args) {
        //değişkenleri oluştur
        int mat,kimya,fizik,turkce,tarih,muzik;

        //scanner sınıfımızı tanımla
        Scanner inp=new Scanner(System.in);

        //kullanıcıdan değer al
        System.out.println("Matematik notunuz=");
        mat= inp.nextInt();

        System.out.println("fizik notunuz=");
        fizik= inp.nextInt();

        System.out.println("kimya notunuz=");
        kimya= inp.nextInt();

        System.out.println("Türkçe notunuz=");
        turkce = inp.nextInt();

        System.out.println("Müzik notunuz=");
        muzik= inp.nextInt();

        System.out.println("tarih notunuz=");
        tarih= inp.nextInt();

        int  toplam=(mat+fizik+turkce+tarih+muzik+kimya);
        double sonuc=toplam/6.0;
        System.out.println("Ortalamanız : "+ sonuc);


        String son= ( sonuc >=60 ) ? "Geçti" : "Kaldı";
        System.out.println(son);

    }

}

