# Geliştirme kaydı

## 2026-11-16T16:47:31+03:00

Island Controls klasörünü Git çalışma ağacı olarak hazırladım. 7fe506e kaynak dosyasının Windhawk kataloğundaki ve kurulu 1.4.0 dosyasındaki Git nesne kimliğiyle eşleştiğini kontrol ettim. Hedef depo boştu. Derleme ve pencere davranışı henüz kontrol edilmedi.

## 2026-11-16T16:55:35+03:00

Oyun algılama, Windows Game Bar ile tam yürütülebilir dosya yolu eşleşmesi ve hedef monitörü kaplayan ön plan penceresi şartlarıyla uygulandı. Tam ekran oyundaki şerit 5 px (100% ölçek) yüksekliğinde ve tıklama geçiren bir yüzey. PreviousConfigs.txt dosyasındaki 100 ayar varsayılanlara işlendi. x86 ve x64 Windhawk 1.7.3 derlemeleri geçti. Ayrı doğrulama programı gerçek RDR2 penceresinin oyun ve tam ekran koşullarını geçtiğini, normal bir tam ekran pencerenin oyun olarak algılanmadığını, küçük pencerenin ve farklı monitörün dışlandığını doğruladı. Bu kayıt anında mod Windhawk'ta etkinleştirilmedi.

## 2026-11-16T17:17:54+03:00

Forkun ilk sürümü e06b308 ile GitHub main dalına gönderildi. Windhawk 1.7.3 altında etkinleştirildi. Kurulu 100 ayar PreviousConfigs.txt ile eşleşti. RDR2 ön plandayken tıklama geçiren 5 px şerit masaüstü pikselleri üzerinden doğrulandı.

1.4.0.2 ile şerit üzerinde hover açılışı ve fare ayrılınca şeride dönüş eklendi. Canlı RDR2 oturumunda iki durum geçişi gözlendi ve kullanıcı dönüşü doğruladı. İlk dönüşün ani olduğu geri bildirimiyle 1.4.0.3, normal boyut animasyonunu şerit hedefi ve içerik sönümüyle birleştirdi. Kullanıcı RDR2'de yeni dönüşün çalıştığını doğruladı.

1.4.0.3 genişletilmiş medya paneline seçili uygulama için ses seviyesi ve sessize alma kontrolleri ekledi. Yerel medya kaynaklarından YouTube Music ve XZF Browse, uygulama kimlikleriyle ilgili ses oturumlarına bağlandı. Yalıtılmış sessiz ses oturumu yüzde 37 ve sessizde olarak doğrulandı, Windows ana ses seviyesi ve sessiz durumu sabit kaldı. Windhawk x86/x64 derlemeleri başarılı ve yerel 1.4.0.3 etkin.
