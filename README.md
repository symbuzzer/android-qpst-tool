# ROOT'lu Qualcomm Snapdragon 865 cihazlar için QPST Tool  
Qualcomm Snapdragon 865 cihazlar için ba(ğ)zı gizli özellikleri çalıştırma aracı. Bence bir ekran görüntüsüne bakın aşağıdan :)    
  
## Nasıl kullanırım:
- Ne işe yaradığını bilmiyorsanız lütfen ama lütfen indirmeyin! Cihazınıza kalıcı zararlar verebilir.
- En güncel APK dosyasını [Releases](https://github.com/symbuzzer/android-qpst-tool/releases) sayfasından indirip rootlu cihazınıza kurun.  
- Uygulamayı çalıştırıp ROOT yetkisi verin. Uygulamanın diğer izinlerine ellemeyin ya da elleyin siz bilirsiniz.
- "EFS'yi  sil" ve "Yeniden başlat" seçeneklerini kullanabilmek için önce bir kere basmanız, kırmızı olunca da basılı kalmanız gerekmektedir. Bastıktan 5 saniye sonra hiç bir şey yapmazsanız butonlar tekrar kırmızıdan beyaza döner.    

## Özellikleri:  
- QPST (QUALCOMM DIAG) modunu ve ADB ile geliştirici seçeneklerini tek tuşla aktifleştirme    
- Bozuk EFS bölümlerini tek tuşla silme (/dev/block/sdf8, /dev/block/sdf9, /dev/block/sdf7, /dev/block/sdf10)   
- Tek tuşla cihazı yeniden başlatma
- Tamamen ücretsiz, reklamsız, sade ve hafif bir uygulama
- Otomatik güncelleme özelliği (İndirme ve Yüklemeyi manuel yapmanız gerekmektedir.)

## Notlar:  
- Xiaomi Mi 10T Pro da tarafımca denenmiştir. Diğer Snapdragon 865 cihazlarda da çalışması olasıdır.  
- ! Kullanımdan kaynaklı bütün risk size aittir. Ne işe yaradığını ve ne yaptığını bilmiyorsanız lütfen kullanmayın !  
- EFS'yi sil seçeneği /dev/block/sdf8, /dev/block/sdf9, /dev/block/sdf7, /dev/block/sdf10) bölümlerini tamamen sileceğinden, lütfen bunların yedeğini aldığınıza emin olun.  
  
## Nasıl derlerim:  
- Bu uygulama Tasker (v6.1.3-beta) ve Tasker App Factory (v6.1.3-beta) ile geliştirilmiştir.  
- Bu uygulamaların en aşağı yukarıdaki versiyonlarını indirip cihazınıza kurmanız gerekmektedir.    
- QPST_Tool.prj.xml indirin ve Tasker uygulaması içerisinden proje olarak içe aktarın.  
- Profil seçeneklerinden, Main and HtmlViewer sahnelerinden uygulama ikonu ayarlayın. İsterseniz icon.jpg'yi kullanabilirsiniz.  
- Uygulama olarak dışa aktarırken "Başlangıç görevi: Start", "min android version: 21" and "target android version: 29" olarak ayarlamanız gerekmektedir.
  
## Değişiklik listesi:  
- Şuraya bir bakın: [CHANGELOG.md](https://github.com/symbuzzer/android-qpst-tool/blob/main/CHANGELOG.md)
  
## Ekran görüntüleri:
![](https://github.com/symbuzzer/android-qpst-tool/blob/main/screenshot1.jpg?raw=true)
