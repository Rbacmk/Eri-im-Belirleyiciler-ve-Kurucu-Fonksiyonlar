# Eri-im-Belirleyiciler-ve-Kurucu-Fonksiyonlar
// Erişim Belirleyiciler ve Kurucu Fonksiyonlar
            Calısan.calısan1 = new Calısan("ayşe", "kara", 141514, "İnsan kaynakları");

        }
    }
    class Calısan
    {
        public string Ad;
        public string Soyad;
        public int No;
        public string Departman;

        // Yapıcı Metotların isimleri sınıf isimleri ile aynı olmalıdır.
        //Public olarak  bildirilmeleri gerekir.
        // Classın özellikleri hakkında değişiklik yapabiliriz.
        public Calısan(string ad, string soyad,int no ,string departman)
        {
            this.Ad = ad; ;
            this.Soyad = soyad;
            this.No = no;
            this.Departman = departman;

        }
        public Calısan()
        {

        }
