# take_fit
Bu proje Ensar Meşe ve Hakan Biradlı tarafından İstinye Üniversitesi Bilgisayar Programcılığı, Mobil Programlama dersinin projesidir.
Projenin amacı günlük spor aktivitelerini tutan bir sağlık uygulamasıdır.
Proje hakkında:
Projedeki amaç her bireyin yaptığı yürüyüş ve spor etkinlikleri ayrıca aldığı besinlerin tutmasını sağlıyan ve karşılaştırma yaparak kişinin günlük ne kadar spor yaparak aldığı besinleri eritmesini sağlayacak bir proje geliştirmek.Ayrıca kişinin kendisi ile ilgili başkalarına danışmak yerine projede olan yapay zeka(gemini) sayesinde sağlıklı bir vücut geliştirmesine katkıda bulunmaktır.
 
 
Yapılan teknolojiler anlatılması:
Porejede ilk başta veritabanı olarak telefonda tutulması kararını aldık. Onun için gerekli olan shared preferences kütüphanesi ekledik ve kişilerin bilgileri telefona kaydeterek başladık bu işlemde Bloc cubit mimarisi ile tasarladık.Daha sonra kişilerin spor etkinliklerini yazdık. Ve her spro yaptığında bellekte tutarak ilerleme sağladık.Yürüyüş için telefondaki sensörler yardımı ile kişinin kaç adım attığınıda aynı şekilde bellekte tutmuş olduk. Sonrasında kişinin aldığı besinleri bellekte tutaraktan gün bazında kaç besin aldığı ve kaç spor etkinliği ve süresini karşılaştırarak besinlerin ve sporların anasayfada özet olarak karşılaştırma yaptık. Profil sayfasında kişinin id sine göre düzenleme yapmasını sağladık .Projede gemini entegrasyonu yaparak kişilerin spor hakkında bilgi alması için bazı soru baloncukları ekleyerek yapay zeka tarafınıda entegre ettik projeye. Ayarlar bölümünde tema ve dil desteğin getx kullanarak projeye entegre ettik.Ayrıca font olarak Roboto medium kullanarak daha estetik bir proje yaptık.
 
Projede  kullanılan  yapılar.
Hafıza için gerekli kütüphaneler(Shared preferences,secure_storage)
Tema ve dil desteği için (Getx )
Bloc cubit mimarisi
Sensor kütüphaneleri(sensor_plus)
gemini kütüphanesi
Bazı gerekli ui kütüphaneleri (chat bubbles,gap,dynamic_themes …)
